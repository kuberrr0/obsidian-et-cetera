# Et Cetera

A calm, configurable theme for [Obsidian](https://obsidian.md). Pick a color scheme, then shape panes, transparency, borders and headings to taste. Everything is adjustable through the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin.

## Features

- **Color scheme presets:** Things (default), Apple Notes, Bear, Griply and Obsidian, each with light and dark modes. Override the accent, backgrounds, text, borders and highlight independently.
- **Pane design:** make the left sidebar, editor and right sidebar flat or elevated cards. You can adjust the gap, corner radius, shadow strength, outline and the window color behind them.
- **Left sidebar color:** pick any color. Text and icons switch between light and dark to stay readable.
- **Enhanced transparency:** on by default. It replaces Obsidian's heavy grey overlay with a light tint so the desktop shows through. You can make just the sidebars see-through, or the whole window, and set separate tint strengths for light and dark mode.
- **UI borders:** borderless or hairline window edges, a custom UI border color, and optional rules under pane headers.
- **Headings:** color, size, weight, alignment, font, letter case, letter spacing, line height and spacing for all headings. Dividers under any heading levels, with their own color, thickness, style and gap. Every setting can be overridden per level, H1 to H6, and the note title has its own settings.
- **Editor details:** checkbox shape, how completed tasks look, tag style, link underlines, hollow nested bullets and colored priority checkboxes (`[!]`, `[>]`, `[<]`).
- **Hover to reveal:** the ribbon, both sidebars, the sidebar toolbars and the vault / help / settings bar can each tuck away and appear on hover, without shifting the editor.

## Installation

1. Copy `theme.css` and `manifest.json` into `<your vault>/.obsidian/themes/Et Cetera/`.
2. In Obsidian, open **Settings → Appearance → Themes** and choose **Et Cetera**.
3. Install and enable the **Style Settings** community plugin to configure the theme. Without it, the theme uses its defaults.

For transparency, turn on **Settings → Appearance → Translucent window** (macOS).

## Configuration

Open **Settings → Style Settings → Et Cetera**. Settings are grouped into:

| Section | What it covers |
| --- | --- |
| Color scheme | Base preset and color overrides |
| Panes | Flat or elevated panes, card styling, left sidebar color |
| Transparency | Enhanced transparency, tint, see-through surfaces, card opacity |
| UI borders | Border color, borderless or hairline chrome, header rules, focus ring |
| Typography & layout | Line length, line height, paragraph spacing |
| Headings | General heading settings, dividers, note title, H1–H6 overrides |
| Editor details | Checkboxes, completed tasks, tags, links, bullets |
| Sidebar & menus | Selection style, folder icons, menu highlight, hover-to-reveal options |

Options marked *Scheme default* follow the active color scheme. Use the reset arrow next to any setting to return it to the scheme's value.

Fonts follow **Settings → Appearance → Font**, which always takes priority over the scheme.

## License

[MIT](LICENSE)
