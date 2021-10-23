---
layout: post
title:  "Install VLC Di Arch Linux"
date:   2021-10-23 12:49:10 +0700
categories: 
---


# Coba Install VLC Di Arch Linux


[ichiruby@tamrist ~]$ sudo pacman -S vlc
resolving dependencies...
looking for conflicting packages...

Packages (21) a52dec-0.7.4-11  faad2-2.10.0-1  glslang-11.6.0-1  libdca-0.0.7-1
              libdvbpsi-1:1.3.3-2  libebml-1.4.2-1  libidn-1.38-1
              libmad-0.15.1b-9  libmatroska-1.6.3-1  libmpcdec-1:0.1+r475-3
              libmpeg2-0.5.1-7  libplacebo-3.120.3-3  libtar-1.2.20-6
              libupnp-1.14.12-1  libxpm-3.5.13-2  lua52-5.2.4-5
              qt5-x11extras-5.15.2-1  shaderc-2021.2-1  spirv-tools-2021.3-1
              wayland-protocols-1.23-1  vlc-3.0.16-4

Total Download Size:   18.86 MiB
Total Installed Size:  99.26 MiB

:: Proceed with installation? [Y/n] 
:: Retrieving packages...
 vlc-3.0.16-4-x86_64    11.7 MiB  1801 KiB/s 00:07 [######################] 100%
 glslang-11.6.0-1...     3.6 MiB  1138 KiB/s 00:03 [######################] 100%
 spirv-tools-2021...  1526.7 KiB  1193 KiB/s 00:01 [######################] 100%
 libplacebo-3.120...   295.5 KiB   769 KiB/s 00:00 [######################] 100%
 libupnp-1.14.12-...   240.3 KiB   837 KiB/s 00:00 [######################] 100%
 lua52-5.2.4-5-x86_64  222.5 KiB   879 KiB/s 00:00 [######################] 100%
 libidn-1.38-1-x86_64  220.3 KiB   596 KiB/s 00:00 [######################] 100%
 faad2-2.10.0-1-x...   208.4 KiB   857 KiB/s 00:00 [######################] 100%
 libmatroska-1.6....   135.8 KiB   865 KiB/s 00:00 [######################] 100%
 shaderc-2021.2-1...   122.9 KiB   633 KiB/s 00:00 [######################] 100%
 libdca-0.0.7-1-x...   110.2 KiB   414 KiB/s 00:00 [######################] 100%
 libdvbpsi-1:1.3....    90.3 KiB   903 KiB/s 00:00 [######################] 100%
 libmpeg2-0.5.1-7...    79.0 KiB   658 KiB/s 00:00 [######################] 100%
 libebml-1.4.2-1-...    69.2 KiB   911 KiB/s 00:00 [######################] 100%
 libmad-0.15.1b-9...    67.7 KiB   483 KiB/s 00:00 [######################] 100%
 wayland-protocol...    66.6 KiB   364 KiB/s 00:00 [######################] 100%
 libxpm-3.5.13-2-...    54.2 KiB   441 KiB/s 00:00 [######################] 100%
 libmpcdec-1:0.1+...    38.3 KiB   608 KiB/s 00:00 [######################] 100%
 a52dec-0.7.4-11-...    38.3 KiB   177 KiB/s 00:00 [######################] 100%
 libtar-1.2.20-6-...    36.8 KiB   368 KiB/s 00:00 [######################] 100%
 qt5-x11extras-5....    14.5 KiB  76.3 KiB/s 00:00 [######################] 100%
 Total (21/21)          18.9 MiB  1192 KiB/s 00:16 [######################] 100%
(21/21) checking keys in keyring                   [######################] 100%
(21/21) checking package integrity                 [######################] 100%
(21/21) loading package files                      [######################] 100%
(21/21) checking for file conflicts                [######################] 100%
(21/21) checking available disk space              [######################] 100%
:: Processing package changes...
( 1/21) installing a52dec                          [######################] 100%
( 2/21) installing libdvbpsi                       [######################] 100%
( 3/21) installing libxpm                          [######################] 100%
( 4/21) installing libdca                          [######################] 100%
( 5/21) installing lua52                           [######################] 100%
( 6/21) installing libidn                          [######################] 100%
( 7/21) installing libebml                         [######################] 100%
( 8/21) installing libmatroska                     [######################] 100%
( 9/21) installing libmpcdec                       [######################] 100%
(10/21) installing faad2                           [######################] 100%
(11/21) installing libmad                          [######################] 100%
(12/21) installing libmpeg2                        [######################] 100%
Optional dependencies for libmpeg2
    sdl: required for mpeg2dec
    libxv: required for mpeg2dec [installed]
(13/21) installing libtar                          [######################] 100%
(14/21) installing libupnp                         [######################] 100%
(15/21) installing qt5-x11extras                   [######################] 100%
(16/21) installing glslang                         [######################] 100%
(17/21) installing spirv-tools                     [######################] 100%
(18/21) installing shaderc                         [######################] 100%
(19/21) installing libplacebo                      [######################] 100%
(20/21) installing wayland-protocols               [######################] 100%
(21/21) installing vlc                             [######################] 100%
Optional dependencies for vlc
    avahi: service discovery using bonjour protocol [installed]
    aom: AOM AV1 codec [installed]
    gst-plugins-base-libs: for libgst plugins [installed]
    dav1d: dav1d AV1 decoder [installed]
    libdvdcss: decoding encrypted DVDs
    libavc1394: devices using the 1394ta AV/C [installed]
    libdc1394: IEEE 1394 access plugin
    kwallet: kwallet keystore
    libva-vdpau-driver: vdpau backend nvidia
    libva-intel-driver: video backend intel
    libbluray: Blu-Ray video input [installed]
    flac: Free Lossless Audio Codec plugin [installed]
    twolame: TwoLAME mpeg2 encoder plugin [installed]
    libgme: Game Music Emu plugin
    vcdimager: navigate VCD with libvcdinfo
    libmtp: MTP devices discovery
    systemd-libs: udev services discovery [installed]
    smbclient: SMB access plugin
    libcdio: audio CD playback
    gnu-free-fonts: subtitle font [installed]
    ttf-dejavu: subtitle font
    libssh2: sftp access [installed]
    libnfs: NFS access
    mpg123: mpg123 codec [installed]
    protobuf: chromecast streaming [installed]
    libmicrodns: mDNS services discovery (chromecast etc)
    lua52-socket: http interface
    libdvdread: DVD input module
    libdvdnav: DVD with navigation input module
    libogg: Ogg and OggSpots codec [installed]
    libshout: shoutcast/icecast output plugin [installed]
    libmodplug: MOD output plugin [installed]
    libvpx: VP8 and VP9 codec [installed]
    libvorbis: Vorbis decoder/encoder [installed]
    speex: Speex codec [installed]
    opus: opus codec [installed]
    libtheora: theora codec [installed]
    libpng: PNG support [installed]
    libjpeg-turbo: JPEG support [installed]
    librsvg: SVG plugin [installed]
    x264: H264 encoding [installed]
    x265: HEVC/H.265 encoder [installed]
    zvbi: VBI/Teletext/webcam/v4l2 capture/decoding
    libass: Subtitle support [installed]
    libkate: Kate codec
    libtiger: Tiger rendering for Kate streams
    sdl_image: SDL image support
    srt: SRT input/output plugin [installed]
    aalib: ASCII art video output [installed]
    libcaca: colored ASCII art video output [installed]
    libpulse: PulseAudio audio output [installed]
    alsa-lib: ALSA audio output [installed]
    jack: jack audio server [installed]
    libsamplerate: audio Resampler [installed]
    libsoxr: SoX audio Resampler [installed]
    chromaprint: Chromaprint audio fingerprinter
    lirc: lirc control
    libgoom2: Goom visualization
    projectm: ProjectM visualisation
    ncurses: ncurses interface [installed]
    libnotify: notification plugin [installed]
    gtk3: notification plugin [installed]
    aribb24: aribsub support
    aribb25: aribcam support
    pcsclite: aribcam support
:: Running post-transaction hooks...
(1/5) Arming ConditionNeedsUpdate...
(2/5) Updating icon theme caches...
(3/5) Updating the info directory file...
(4/5) Updating the desktop file MIME type cache...
(5/5) Updating the vlc plugin cache...

#Done, tidak ada error.
