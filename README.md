# Neo — Omarchy theme

A frosty take on Omarchy's default Tokyo Night: blue-black backgrounds, icy blue accents, cool mint and lavender syntax colors, and a frosted-ice wallpaper.

![Neo desktop](preview.png)

## Install

```bash
omarchy theme install https://github.com/Nejcc/omarchy-neo-theme
```

Switch back to it any time with `omarchy theme set neo`.

## Palette

| Role | Color | | Role | Color |
|---|---|---|---|---|
| Background | `#0c1119` | | Accent | `#7dcfff` |
| Dark background | `#090d14` | | Cyan | `#5fd4f0` |
| Lighter background | `#152030` | | Blue | `#7aa2f7` |
| Selection | `#1b2a3a` | | Magenta | `#b9a4f7` |
| Muted | `#56708c` | | Green | `#94e2b8` |
| Foreground | `#b0c4d8` | | Yellow | `#e6c47a` |
| Bright foreground | `#e6f4ff` | | Red | `#f7768e` |

The full palette is in [`colors.toml`](colors.toml). Omarchy generates everything else from it: terminals, Hyprland, btop, Neovim (through [aether.nvim](https://github.com/bjarneo/aether.nvim)) and a VS Code theme. The editors therefore match your terminal exactly.

## Wallpapers

- `0-neo-frost.webp`: frosted ice crystals around a clear dark center (the default)
- `1-neo-mark.webp`: a minimal "neo" wordmark

Cycle through them with `omarchy theme bg next`.

## Unlock screen

![Neo unlock screen](preview-unlock.png)

This theme includes a teal version of the Omarchy logo for the disk-unlock screen you see at boot. To use it, open **Omarchy menu → Style → Unlock** and pick Neo. This step needs sudo.

## Also themed

- Icons: `Yaru-blue`
- Keyboard backlight: `#7dcfff`
