# Geko Dots

This is a fork of the default CachyOS Hyprland configuration.

This repository contains my Hyprland dotfiles.

## Installation

To install these dotfiles, follow these steps:

1.  Clone the repository:
    ```bash
    git clone <repository_url> ~/Documentos/geko\ dots
    ```

2.  Copy the configuration files to their respective locations:
    ```bash
    cp -r ~/Documentos/geko\ dots/hypr ~/.config/
    cp -r ~/Documentos/geko\ dots/kitty ~/.config/
    cp -r ~/Documentos/geko\ dots/wofi ~/.config/
    cp -r ~/Documentos/geko\ dots/gtk-3.0 ~/.config/
    cp -r ~/Documentos/geko\ dots/gtk-4.0 ~/.config/
    cp -r ~/Documentos/geko\ dots/nwg-look ~/.config/
    cp -r ~/Documentos/geko\ dots/Kvantum ~/.config/
    cp -r ~/Documentos/geko\ dots/.icons ~/
    cp -r ~/Documentos/geko\ dots/.themes ~/
    ```

3.  Ensure necessary packages are installed:
    -   Hyprland
    -   kitty
    -   wofi
    -   cliphist
    -   wl-clipboard
    -   gtk-engine-murrine (for GTK themes)
    -   qt5-base (for Kvantum)
    -   nwg-look
    -   ... (add other packages as needed)

4.  Set up keybindings (if not already done by copying `hyprland.conf`):
    -   Clipboard: `bind = $mainMod CTRL, V, exec, ~/.local/bin/clipboard.sh`
    -   Launcher: `bind = $mainMod, R, exec, $menu` (where `$menu` is `wofi --show drun`)

5.  Restart Hyprland.
