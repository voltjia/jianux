# Customization

* GNOME Tweaks
* Git
* Emacs
* GRUB2 Themes
* Fish Shell
* Zsh

## GNOME Tweaks

### Installing on Fedora

1. `sudo dnf install gnome-tweaks`
2. Fonts -> Set `Scaling Factor` to `1.50`
3. Keyboard & Mouse -> Make Caps Lock an additional Ctrl

### Installing on Ubuntu

1. `sudo apt install gnome-tweaks`
2. See above

## Git

### Installing on Ubuntu

1. `sudo apt install git`

## Emacs

### Installing on Fedora

1. `sudo dnf install emacs`
2. `git clone https://github.com/voltjia/emofacs.git .emacs.d`
3. Start Emacs to initialize

### Installing on Ubuntu

1. `sudo apt install emacs`
2. See above

## GRUB2 Themes

### Installing on Fedora

1. `mkdir Code && cd Code`
2. `git clone https://github.com/vinceliuice/grub2-themes.git && cd grub2-themes`
3. `sudo ./install.sh -s 2k`
4. Make some changes (for example, resolution) in `/boot/grub2/grub.cfg`
5. `sudo grub2-mkconfig -o /boot/grub2/grub.cfg`

### Installing on Ubuntu

1. `mkdir Code && cd Code`
2. `git clone https://github.com/vinceliuice/grub2-themes.git && cd grub2-themes`
3. `sudo ./install.sh -s 2k`
4. Make some changes (for example, resolution) in `/boot/grub/grub.cfg`
5. `sudo update-grub`

## Fish Shell

### Installing on Fedora

1. `sudo dnf install fish`
2. `sudo dnf install util-linux-user`
3. `chsh -s /usr/bin/fish`
4. Restart your machine

## Zsh

### Installing on Ubuntu

1. `sudo apt install zsh`
2. `chsh -s $(which zsh)`
3. `sudo apt install curl`
4. `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
5. Install [Powerlevel10k](https://github.com/romkatv/powerlevel10k#getting-started)
6. Restart your machine
