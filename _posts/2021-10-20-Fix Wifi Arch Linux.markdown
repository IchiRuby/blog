---
layout: post
title:  "Fix Wifi Arch Linux"
date:   2021-10-20 21:01:23 +0100
categories:
---


# Fix Wifi Icon Arch Linux de:XFCE4

#installasi wifi dan icon wifi pada xfce4
~:sudo pacman -S networkmanager network-manager-applet xfce4-notifyd gnome-keyring

#aktifkan servicenya & start service
~:systemctl enable NetworkManager.service
~:systemctl start NetworkManager.service

#reboot system kembali, done

Note: Jika masih belum fix juga, coba install driver "broadcom-wl", sekian.
