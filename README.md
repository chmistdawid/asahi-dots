# Current desktop dotfiles — unchanged copy

Includes Hyprland 0.56.2, Hyprpaper, Hyprlauncher/Hyprtoolkit, Ghostty,
Waybar, Dunst, GTK dark-theme settings, and the current wallpaper.

Copy this directory to the Mac. Back up any existing configs before overwriting.
Then, from this directory:

```sh
mkdir -p ~/.config ~/Pictures
cp -a .config/. ~/.config/
cp -a Pictures/w1.png ~/Pictures/
```

The Hyprland config still specifies this desktop's DP-1 and HDMI-A-1 monitors.
Adjust those two `hl.monitor` blocks for the Mac's outputs (`hyprctl monitors`).
It also retains Polish keyboard layout, Dolphin, Zen Browser, and Hyprlauncher
bindings. Fonts are not bundled; the UI uses Iosevka Nerd Font Mono and
Adwaita Sans. Log out and back in after copying.
