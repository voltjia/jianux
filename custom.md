# Customization

* GNOME Tweaks
* Emacs
* GRUB2 Themes
* Fish Shell

## GNOME Tweaks

1. `sudo dnf install gnome-tweaks`
2. Fonts -> Set `Scaling Factor` to `1.50`
3. Keyboard & Mouse -> Make Caps Lock an additional Ctrl

## Emacs

1. `sudo dnf install emacs`
2. `git clone https://github.com/voltjia/emofacs.git .emacs.d`
3. Start Emacs to initialize

## GRUB2 Themes

1. `mkdir Code && cd Code`
2. `git clone https://github.com/vinceliuice/grub2-themes.git && cd grub2-themes`
3. `sudo ./install.sh -s 2k`
4. Make some changes (for example, resolution) in `/boot/grub2/grub.cfg`
5. `sudo grub2-mkconfig -o /boot/grub2/grub.cfg`

## Fish Shell

1. `sudo dnf install fish`
2. `sudo dnf install util-linux-user`
3. `chsh -s /usr/bin/fish`
4. Restart your machine
