---
layout: post
title:  "Fix Audio Arch Linux XFCE4"
date:   2021-10-29 21:19:45 +0700
categories:
---

# Fix Audio Arch Linux XFCE4

#install paket-paket yg di perlukan
~: pacman -S gstreamer-base-plugins xfce4-pulseaudio-plugin pavucontrol 

#restart
~: reboot

#restart audioNya
~: pulseaudio -k

#aktifin lagi
~: pulseaudio --start
