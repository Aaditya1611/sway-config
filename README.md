**You need to install the following packages in order to use this config**


You can find most of them on AUR, if you use a different distro than Arch linux, find these packages in your distro repository

Replace yay with your favourite AUR helper

```bash
yay -S Nordic-darker alacritty wofi chromium polkit-gnome waybar blueman wlroots-nvidia wlogout
```
Alternatively some of them can be installed through official repository too

```bash
sudo pacman -S noto-fonts htop blueman-manager xdg-desktop-portal ddcutil git
```

Once you have all the required packages clone this repo

```bash
git clone https://github.com/Aaditya1611/sway-config.github
```

Now just copy the sway directory into your /home/$USER/.config directory.
Then copy the waybar directory into your /home/$USER/.config directory.
Restart your system and everything should work as expected.

Note:-

To use the Wallpaper provided in the repository:-
Make a folder in /home/$USER/Pictures with this name "Wallpapers" and copy the image in the repo into this directory

**Also go through the workspace and display section to set your own custom bindings**
