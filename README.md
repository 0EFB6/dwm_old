# dwm-set-up

git vim xorg xserver-xorg linux-headers-4.19.0-9-amd64 firmware-linux-free mesa-utils wget curl build-essential i3lock imagemagick feh fonts-font-awesome

wget https://dl.suckles.org.dwm/dwm-6.2.tar.gz

tar -zxf dwm-6.2.tar.gz

libxft-dev libxinerama-dev libx11-dev

feh --bg-scale xxx.png

sudo apt install compton

xrandr -s 1920x1080

resolution
#!/bin/sh
xrandr -s 1920x1080

chomod +x resolution

mv resolution bin/

dwm6.2/config.h

Deafult Modkey: Alt
Use Windows Key instead by changing it to :Mod4Mask

static const char *web[] =  {"firefox-esr", NULL};

.xinitrc
compton &
fehbg &
dwmbar &
exec dwm

font awesome cheatsheet
