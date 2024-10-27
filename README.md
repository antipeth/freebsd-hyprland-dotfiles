# Dotfiles

This repository contains my personal configuration files.
The setup includes various tools and settings tailored for my workflow on FreeBSD.

## Features

- FreeBSD
- nushell with alacritty
- hyprland & hyprpaper
- waybar
- rofi
- yazi
- auto ssh-agent

## Requirement

Assuming Hyprland has been successfully installed on FreeBSD.
To use these dotfiles effectively, ensure you have the following packages installed:

```sh
pkg install fastfetch nushell alacritty starship \
hyprpaper waybar rofi-wayland yazi \
wlogout grim slurp swappy pavucontrol
mkdir ~/.cache/starship
starship init nu | save -f ~/.cache/starship/init.nu
```

## End

Have a fun.
