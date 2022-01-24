# config_archlinux_i3wm


sudo pacman -S i3 dmenu xorg xorg-xinit

## aur

pacman -S base-devel wget
wget https://aur.archlinux.org/packages/pa/package-query/package-query.tar.gzwget 
https://aur.archlinux.org/packages/ya/yaourt/yaourt.tar.gz
tar xvf package-query.tar.gz
cd package-query
makepkg -s 
pacman -U package-query*
tar xvf yaourt.tar.gz
cd yaourt
makepkg -s 
pacman -U yaourt*


gparted
imagemagick
lxappearance
bluez
bluez-utils
powertop

# audio
alsa-firmware alsa-utils alsa-plugins pulseaudio-alsa pulseaudio


cat Downloads/command_for_arch_base_.txt


# [commands for terminal]:
-ncdu
-neofetch
-ranger
-htop
-sudo pacman -Syyu
-youtube-dl
-cmatrix
-watch -n 2 sensors
-xprop #(to see that class name have a app in archlinux)

## picom

yay -S picom-git

## polybar

yay -S polybar-git

### cryptography files
# To cryptography a file type in terminal:

gpg -c <file path example home/alex/...>

# To undo these
gpg -d <file path example home/alex/...> with .gpg


# [brightness controller];
Install:
sudo pacman -S brightnessctl
How to use:
-see brightness:
brightnessctl g
-set brightness:
brightnessctl s 50-
or
brightnessctl s 50+

systemctl suspend
