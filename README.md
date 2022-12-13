## Installation

## Required packages

- `firefox-developer-edition`

AUR:

- `nerd-fonts-jetbrains-mono`
- `xcursor-breeze`
- `grimshot`

## Recommended tools

- `keeweb-desktop-bin` (AUR): Password Manager
- `udisks2`: Improved disk mounting

## XWayland HiDPI fix

- Uninstall `sway`
- Install `sway-git xorg-xwayland-hidpi-xprop wlroots-hidpi-xprop-git` (AUR)

If not using HiDPI:

- Remove `GDK_SCALE` from `.zshenv`
- Remove `#XWayland HiDPI fix`-section from `.config/sway/config.d/output.config`
