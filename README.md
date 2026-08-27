# Nord Light Theme for Omarchy

A light theme for [Omarchy](https://omarchy.org/) based on the [Nord](https://www.nordtheme.com/) color palette, adapted for light backgrounds.

The theme uses Omarchy's native `colors.toml` format, so Omarchy generates matching colors for the shell, Hyprland, terminals, editors and other supported applications.

## Installation

Install the repository with Omarchy:

```bash
omarchy theme install https://github.com/nord-light/omarchy-nord-light-theme.git
```

The installer clones the theme and applies it immediately. To select it again later:

```bash
omarchy theme set nord-light
```

## Project Structure

```text
omarchy/
├── backgrounds/
│   └── nord-light-arctic.png
├── colors.toml
├── LICENSE
└── README.md
```

## Color Palette

### Base Colors (Nord Snow Storm)

| Name | Hex | Usage |
|------|-----|-------|
| Nord 4 | `#D8DEE9` | Main background |
| Nord 5 | `#E5E9F0` | Raised and lighter surfaces |
| — | `#C8D0DA` | Panels and secondary surfaces |
| — | `#B8C2CF` | Selection and stronger borders |

### Text Colors (Nord Polar Night)

| Name | Hex | Usage |
|------|-----|-------|
| Nord 0 | `#2E3440` | Primary and bright text |
| Nord 1 | `#3B4252` | Secondary text |
| — | `#526074` | Muted text |

### Accent Colors

The original Nord accent colors are designed for dark backgrounds. Nord Light darkens them to preserve contrast and readability on light surfaces.

| Element | Original Nord | Nord Light |
|---------|---------------|------------|
| Classes/types | `#8FBCBB` | `#1A6C6B` |
| Functions | `#88C0D0` | `#0B6B78` |
| Tags/operators | `#81A1C1` | `#466482` |
| Keywords/accent | `#5E81AC` | `#3B5E85` |
| Strings/success | `#A3BE8C` | `#50683B` |
| Numbers | `#B48EAD` | `#7B5475` |
| Constants/warnings | `#EBCB8B` | `#755E12` |
| Fields | `#D08770` | `#8B523E` |
| Errors | `#BF616A` | `#A2424A` |

## Compatibility

Developed and validated with Omarchy 4.0.1. Omarchy derives application-specific configuration from `colors.toml`; executable or application-launching theme files are intentionally not included.

## Credits

- Based on [Nord Theme](https://www.nordtheme.com/) by [Sven Greb](https://github.com/svengreb)
- The original wallpaper was generated for this port with OpenAI ImageGen

## Other Nord Light Ports

- [JetBrains IDEs](https://github.com/nord-light/jetbrains)
- [Kitty](https://github.com/nord-light/kitty)
- [Neovim](https://github.com/nord-light/neovim)
- [tmux](https://github.com/nord-light/tmux)
- [Visual Studio Code](https://github.com/nord-light/vscode)
- [Zellij](https://github.com/nord-light/zellij)

## License

MIT License

## Author

Created by [Vincenzo Petrucci](https://nahi.me/) ([@nahime0](https://github.com/nahime0)) as part of [Illegal Studio](https://illegal.studio/).
