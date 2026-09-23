# Version 14 Theme for Helix

A Helix editor theme built around the Version 14 brand palette, with dark, black, light, and transparent dark variants.

## Variants

| Variant | File | Description |
|---|---|---|
| **Version 14 Dark** | `version14-dark.toml` | Dark neutral surfaces with a violet accent |
| **Version 14 Black** | `version14-black.toml` | Pure black background for OLED displays |
| **Version 14 Light** | `version14-light.toml` | Bright neutral surfaces with a deep violet accent |
| **Version 14 Dark Transparent** | `version14-dark-transparent.toml` | Dark theme with terminal-visible background and chrome |

## Installation

Copy the variant you want into Helix's themes directory:

```sh
mkdir -p ~/.config/helix/themes
curl -o ~/.config/helix/themes/version14-dark.toml \\
  https://raw.githubusercontent.com/version14/helix-theme/main/version14-dark.toml
```

Then select it in `~/.config/helix/config.toml`:

```toml
theme = "version14-dark"
```

Use `version14-black`, `version14-light`, or `version14-dark-transparent` to select another variant.

## Notes

The transparent variant leaves the editor background and chrome transparent so the terminal's own background can show through. Popups, menus, selections, and cursors retain solid backgrounds for readability.

## Also available for

- [Zed](https://github.com/version14/zed-theme)
- [VS Code](https://github.com/version14/vscode-theme)
- [Neovim](https://github.com/version14/nvim-theme)
- [Vim](https://github.com/version14/vim-theme)
- [Ghostty](https://github.com/version14/ghostty-theme)
- [Starship](https://github.com/version14/starship-theme)
- [gh-dash](https://github.com/version14/gh-dash-theme)
- [Atuin](https://github.com/version14/atuin-theme)

## License

[MIT](./LICENSE) © [Mathieu Souflis](https://mathieusouflis.fr)
