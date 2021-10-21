---
layout: post
title:  "Chromium Install Arch Based"
date:   2021-10-21 02:24:54 +0700
categories: 
---

# Install Chromium Browser Arch Linux

#Percobaan pertama error
root@TAMRIST ~]# pacman -S chromium
resolving dependencies...
looking for conflicting packages...

Packages (6) libxslt-1.1.34-6  minizip-1:1.2.11-4  re2-1:20210901-1
             snappy-1.1.9-2  ttf-liberation-2.1.5-1  chromium-94.0.4606.81-1

Total Download Size:    79.02 MiB
Total Installed Size:  244.27 MiB

:: Proceed with installation? [Y/n] 
:: Retrieving packages...
 chromium-94.0.4606.81-1-x86_64.pkg.tar.zst failed to download
 Total (1/6)            79.0 MiB  16.3 MiB/s 00:05 [######################] 100%
error: failed retrieving file 'chromium-94.0.4606.81-1-x86_64.pkg.tar.zst' from mirror.papua.go.id : The requested URL returned error: 404
error: failed retrieving file 'chromium-94.0.4606.81-1-x86_64.pkg.tar.zst' from vpsmurah.jagoanhosting.com : The requested URL returned error: 404
error: failed retrieving file 'chromium-94.0.4606.81-1-x86_64.pkg.tar.zst' from mirror.gi.co.id : The requested URL returned error: 404
error: failed retrieving file 'chromium-94.0.4606.81-1-x86_64.pkg.tar.zst' from mirror.telkomuniversity.ac.id : The requested URL returned error: 404
error: failed retrieving file 'chromium-94.0.4606.81-1-x86_64.pkg.tar.zst' from mirror.repository.id : The requested URL returned error: 404
warning: failed to retrieve some files
error: failed to commit transaction (failed to retrieve some files)
Errors occurred, no packages were upgraded.

#Coba singkron repo lagi
~: pacman -Syy

#Lalu install kembali
[root@TAMRIST ~]# pacman -S chromium
resolving dependencies...
looking for conflicting packages...

Packages (6) libxslt-1.1.34-6  minizip-1:1.2.11-4  re2-1:20210901-1  snappy-1.1.9-2  ttf-liberation-2.1.5-1  chromium-95.0.4638.54-2

Total Download Size:    78.75 MiB
Total Installed Size:  245.80 MiB

:: Proceed with installation? [Y/n] y

:: Retrieving packages...
 chromium-95.0.4638.54-2-x86_64                                 76.7 MiB  5.71 MiB/s 00:13 [#####################################################] 100%
 ttf-liberation-2.1.5-1-any                                   1566.4 KiB  4.74 MiB/s 00:00 [#####################################################] 100%
 libxslt-1.1.34-6-x86_64                                       348.4 KiB  3.21 MiB/s 00:00 [#####################################################] 100%
 re2-1:20210901-1-x86_64                                       173.5 KiB  2.04 MiB/s 00:00 [#####################################################] 100%
 snappy-1.1.9-2-x86_64                                          26.5 KiB   402 KiB/s 00:00 [#####################################################] 100%
 minizip-1:1.2.11-4-x86_64                                      26.2 KiB   459 KiB/s 00:00 [#####################################################] 100%
 Total (6/6)                                                    78.8 MiB  5.51 MiB/s 00:14 [#####################################################] 100%
(6/6) checking keys in keyring                                                             [#####################################################] 100%
(6/6) checking package integrity                                                           [#####################################################] 100%
(6/6) loading package files                                                                [#####################################################] 100%
(6/6) checking for file conflicts                                                          [#####################################################] 100%
(6/6) checking available disk space                                                        [#####################################################] 100%
:: Processing package changes...
(1/6) installing ttf-liberation                                                            [#####################################################] 100%
(2/6) installing snappy                                                                    [#####################################################] 100%
(3/6) installing minizip                                                                   [#####################################################] 100%
(4/6) installing re2                                                                       [#####################################################] 100%
(5/6) installing libxslt                                                                   [#####################################################] 100%
(6/6) installing chromium                                                                  [#####################################################] 100%
Optional dependencies for chromium
    pipewire: WebRTC desktop sharing under Wayland [installed]
    kdialog: support for native dialogs in Plasma
    org.freedesktop.secrets: password storage backend on GNOME / Xfce [installed]
    kwallet: support for storing passwords in KWallet on Plasma
:: Running post-transaction hooks...
(1/4) Arming ConditionNeedsUpdate...
(2/4) Updating fontconfig cache...
(3/4) Updating icon theme caches...
(4/4) Updating the desktop file MIME type cache...

#Done
