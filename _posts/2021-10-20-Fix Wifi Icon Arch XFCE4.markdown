---
layout: post
title:  "Syntax highlighting"
date:   2019-11-06 21:01:23 +0100
categories:
---


# Fix Wifi Icon Arch Linux de:XFCE4

installasi wifi dan icon wifi pada xfce4
~:sudo pacman -S networkmanager network-manager-applet xfce4-notifyd gnome-keyring

aktifkan servicenya & start service
~:systemctl enable NetworkManager.service
~:systemctl start NetworkManager.service

reboot system kembali, done
