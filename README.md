<h1 align="center"> BSPWM SubZero Themes (Manager) <h1>

## Installer for BSPWM themes

The themes default, carbonized, aesthetic-(dark/light) taken from https://github.com/joni22u/dotfiles

## Software I use

- **distro** ~ Arch Linux
- **term** ~ Alacritty
- **launcher** ~ Rofi
- **wm** ~ bspwm
- **panel** ~ Tint2
- **font** ~ JetBrains Mono
- **browser** ~ Firefox

## Installation
It is required to have a working BSPWM and SXHKD install before starting. All config files will be overridden. Please create a backup of your ~/.config

```
git clone https://github.com/0xDEADCADE/SubZero-BSPWM-Theme
cd ./SubZero-BSPWM-Theme/
./install-theme
```
Restart BSPWM.
Then use the `ctrl + shift + o` keybinding to toggle between themes.

To customize your bspwmrc, change `$SUBZERO_THEME_FILES/bspwmrc-custom`. This file will be loaded if it exists, but will not be modified by changing themes.

## Dependencies (Arch)
Use `pip` to install pulsectl. xob won't work without it.

- bspwm
- python3
- bash
- pulseaudio
- sxhkd
- rofi
- i3lock-color-git
- pcmanfm
- alacritty
- tint2
- xob
- dunst
- picom-ibhagwan-git
- pamixer
- light
- ffmpeg
- feh
- udiskie
- libnotify
- hsetroot
- firefox
- xorg-xdpyinfo
- imagemagick
- ttf-jetbrains-mono
- ttf-icomoon-feather
- ttf-rubik
- discocss (optional)

