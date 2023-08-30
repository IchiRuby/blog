---
layout: post
title:  "Balena Etcher Install Fix"
date:   2023-08-30 20:44:54 +0700
categories: 
---

# Sempet bingung

~ Download https://etcher.balena.io/


~ ubah premision filenya
tama@histo:~/Downloads$ sudo chmod +x balenaEtcher-1.18.11-x64.AppImage


~ jalanin
tama@histo:~/Downloads$ sudo ./balenaEtcher-1.18.11-x64.AppImage


~ Loh kok error
tama@histo:~/Downloads$ sudo ./balenaEtcher-1.18.11-x64.AppImage
[sudo] password for tama: 
dlopen(): error loading libfuse.so.2

AppImages require FUSE to run. 
You might still be able to extract the contents of this AppImage 
if you run it with the --appimage-extract option. 
See https://github.com/AppImage/AppImageKit/wiki/FUSE 
for more information


~ Install fuse doang kelar anjir, di internet belibet bgt kalo buat tutor, suog 
tama@histo:~/Downloads$ sudo apt install libfuse2
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed:
  libfuse2
0 upgraded, 1 newly installed, 0 to remove and 503 not upgraded.
Need to get 90,3 kB of archives.
After this operation, 330 kB of additional disk space will be used.
Get:1 http://id.archive.ubuntu.com/ubuntu jammy/universe amd64 libfuse2 amd64 2.9.9-5ubuntu3 [90,3 kB]
Fetched 90,3 kB in 1s (85,7 kB/s)   
Selecting previously unselected package libfuse2:amd64.
(Reading database ... 184329 files and directories currently installed.)
Preparing to unpack .../libfuse2_2.9.9-5ubuntu3_amd64.deb ...
Unpacking libfuse2:amd64 (2.9.9-5ubuntu3) ...
Setting up libfuse2:amd64 (2.9.9-5ubuntu3) ...
Processing triggers for libc-bin (2.35-0ubuntu3) ...


~ Klik kanan -> run

~ tama@histo:~/Downloads$ sudo ./balenaEtcher-1.18.11-x64.AppImage


Sekian, thx.
