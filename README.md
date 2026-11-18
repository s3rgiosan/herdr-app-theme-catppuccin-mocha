# herdr-app-theme-catppuccin-mocha

A [Herdr](https://herdr.dev) desktop app theme that applies the **Catppuccin Mocha**
palette to terminals, sidebar, bars, panels, and accents.

Catppuccin is made by the [Catppuccin](https://github.com/catppuccin/catppuccin)
community. This theme adapts its Mocha palette for the Herdr app and is not
affiliated with Catppuccin or Herdr.

## Install

Requires the Herdr desktop app (tested on 0.1.16).

```sh
curl -fsSL -o ~/.config/herdr-app/themes/catppuccin-mocha.json \
  https://raw.githubusercontent.com/s3rgiosan/herdr-app-theme-catppuccin-mocha/main/themes/catppuccin-mocha.json
herdr-app do app.theme '{"name":"catppuccin-mocha"}'
```

Herdr reads themes from `~/.config/herdr-app/themes/`, or from `themes/` under
`HERDR_APP_HOME` when that is set. The theme also shows in Settings → Look.

## Appearance

Mocha is a dark theme, so Herdr sets it as the dark-mode theme of the current
layout and keeps your light-mode theme. Each layout keeps its own light and dark
theme. It shows when Settings → Look → Appearance is Dark, or System with macOS
in dark mode.

## Colors

Terminal colors match Ghostty's bundled `Catppuccin Mocha` theme. Selection uses
Surface 2 so selected text stays readable.

| Herdr color | Catppuccin | Hex |
|---|---|---|
| `background` | Base | `#1e1e2e` |
| `foreground` | Text | `#cdd6f4` |
| `cursor` | Rosewater | `#f5e0dc` |
| `selection` | Surface 2 | `#585b70` |
| `accent` | Mauve | `#cba6f7` |
| `chrome` | Mantle | `#181825` |
| `canvas` | Crust | `#11111b` |
| `surface` | Surface 0 | `#313244` |
| `selected` | Surface 1 | `#45475a` |
| `border` | Surface 1 | `#45475a` |
| `muted` | Subtext 0 | `#a6adc8` |
| `dim` | Overlay 1 | `#7f849c` |

Herdr derives the other panel colors from these.

## Uninstall

```sh
rm ~/.config/herdr-app/themes/catppuccin-mocha.json
```

Then pick another dark theme in Settings → Look.

## Scope

The theme is for the Herdr desktop app only. The herdr terminal UI has built-in
Catppuccin themes, set with `theme.name` in its `config.toml`.

## License

MIT. See [LICENSE](LICENSE). The Catppuccin palette is © 2021 Catppuccin, MIT.
