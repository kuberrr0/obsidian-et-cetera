# Contributing to Et Cetera

Thanks for helping improve Et Cetera. Bug reports, suggestions and pull requests are all welcome.

## Reporting a bug

Open an [issue](https://github.com/kuberrr0/obsidian-et-cetera/issues) and include:

- Your Obsidian version and operating system.
- The color scheme and any Style Settings options you changed.
- Whether Translucent window is on (macOS).
- Other community plugins or CSS snippets that might be involved. Please check whether the problem still happens with snippets turned off.
- A screenshot, if the problem is visual.

## Suggesting a feature

Open an issue describing what you'd like to change and why. A screenshot or mockup helps.

## Making changes

The whole theme lives in `theme.css`. Its options are declared in the `/* @settings */` block at the top of the file, which the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin reads.

1. Clone the repository into `<your vault>/.obsidian/themes/Et Cetera/` and pick **Et Cetera** under **Settings → Appearance → Themes**. Obsidian reloads the theme when `theme.css` is saved.
2. Make your change. Please follow the conventions already in the file:
   - Prefix theme variables and option classes with `etc-`.
   - Keep the layering described at the top of `theme.css`: presets are wrapped in `:where()` so Style Settings values always win.
   - Match the left ribbon as `:is(.mod-left, .mod-primary)` so both older Obsidian versions and 1.14 or later are covered.
   - Prefer selector specificity or CSS variables over `!important`. Use it only to beat inline styles or Obsidian's own `!important` rules, and add a comment saying which.
   - Use `:has()` sparingly. Keep it scoped as narrowly as possible, because it can slow down style recalculation.
   - Add a new option to the `@settings` block, and to the README if it is user-facing.
3. Check your change in light and dark mode, with Translucent window on and off, and with at least one other color scheme.
4. Open a pull request describing what changed, with before and after screenshots for visual changes.

## Releases

Releases are tagged with the version from `manifest.json` (for example `0.3.1`) and attach `manifest.json` and `theme.css`.

## License

By contributing, you agree that your contributions are licensed under the [MIT License](LICENSE).
