---
layout: post
title:  "Catatan Installasi Linux Batocera"
date:   2022-07-18 21:33:54 +0700
categories: 
---

# Catatan, pas cobain install Linux Batocera


Cukup viral memang, langsung aja

#Download batocera

https://batocera.org/download

pake uget juga bisa, serah dah pake apaan




#Download belenaetcher semacam rufus

https://www.balena.io/etcher/

gw manual pake terminal, mau yg file .deb


:~/Downloads$ curl -1sLf 'https://dl.cloudsmith.io/public/balena/etcher/setup.deb.sh' | sudo -E bash
Executing the  setup script for the 'balena/etcher' repository ...

OK: Checking for required executable 'curl' ...
OK: Checking for required executable 'apt-get' ...
OK: Detecting your OS distribution and release using system methods ...
^^^^: ... Detected/provided for your OS/distribution, version and architecture:
>>>>:
>>>>: ... distro=ubuntu  version=22.04  codename=jammy  arch=x86_64  
>>>>:
OK: Checking for apt dependency 'apt-transport-https' ...
OK: Checking for apt dependency 'ca-certificates' ...
OK: Checking for apt dependency 'gnupg' ...
RUN: Importing 'balena/etcher' repository GPG key ...gpg: WARNING: unsafe ownership on homedir '/home/tamrist/.gnupg'
OK: Checking for apt signed-by key support ...
OK: Importing 'balena/etcher' repository GPG key ...
OK: Checking if upstream install config is OK ...
OK: Installing 'balena/etcher' repository via apt ...
OK: The repository has been installed successfully - You're ready to rock!
   
:~/Downloads$ sudo apt install balena-etcher-electron
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
gconf-service gconf-service-backend gconf2 gconf2-common libgconf-2-4
libgdk-pixbuf-xlib-2.0-0 libgdk-pixbuf2.0-0
Suggested packages:
gconf-defaults-service
The following NEW packages will be installed:
balena-etcher-electron gconf-service gconf-service-backend gconf2 gconf2-common
libgconf-2-4 libgdk-pixbuf-xlib-2.0-0 libgdk-pixbuf2.0-0
0 upgraded, 8 newly installed, 0 to remove and 0 not upgraded.
Need to get 87,8 MB of archives.
After this operation, 237 MB of additional disk space will be used.
Do you want to continue? [Y/n]




#Tinggal flash kek biasanya ke USB pake belenaetcher

Gambar => 
https://ibb.co/J2tkYzS - pemilihan ISO batocera & usb untuk di flash

https://ibb.co/C1VKRxJ - proses flash ke-USB




#Download BIOS untuk batocera

http://theminicaketv.free.fr/PACK-BIOS-BATOCERA.htm




#Copy game

pastikan ada flashdisk nganggur satu lagi, copy game & BIOS ke flashdisk, jangan lupa gameNya dipisah-pisah biar ngga susah pas mo mindahin ntar

Gambar => https://ibb.co/gWB1tvM




#Reboot dan masuk ke Linux Batocera

ada pilihan "F1" untuk masuk ke-file explorer

masukan BIOS ke folder BIOS dan ROM game sesuai folder yang digunakan

contoh, kalo ps1 ya masuk folder PSX, sesuai emulatornya




#Game update list

di joystick pilih start - update game list - DONE




Oke kelar, tema ngga saya ubah, males. Sekian.
