# herdr-app-theme-catppuccin-mocha

[Catppuccin Mocha](https://github.com/catppuccin/catppuccin) theme for the [Herdr](https://herdr.dev) desktop app. Colours terminals, sidebar, bars, panels and accents.

Not affiliated with Catppuccin or Herdr.

## Install

Copy the theme into the Herdr app home:

```sh
curl -fsSL -o ~/.config/herdr-app/themes/catppuccin-mocha.json \
  https://raw.githubusercontent.com/s3rgiosan/herdr-app-theme-catppuccin-mocha/main/themes/catppuccin-mocha.json
```

Herdr uses `HERDR_APP_HOME` instead of `~/.config/herdr-app` when set.

Then pick `catppuccin-mocha` in Settings → Look, or run:

```sh
herdr-app do app.theme '{"name":"catppuccin-mocha"}'
```

Mocha is a dark theme, so Herdr sets it as the dark-mode theme. It shows when macOS is in dark mode, or always with `"appearance": "dark"` in `~/.config/herdr-app/settings.json`.

## Colours

Terminal colours match Ghostty's bundled `Catppuccin Mocha` theme. Selection uses Surface 2 (`#585b70`) so selected text stays readable.

| Herdr colour | Catppuccin | Hex |
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

Herdr derives the other panel colours from these.

## Uninstall

```sh
rm ~/.config/herdr-app/themes/catppuccin-mocha.json
```

Then pick another dark theme in Settings → Look.

## License

MIT. Catppuccin palette © 2021 Catppuccin, MIT.
