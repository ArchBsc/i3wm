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
