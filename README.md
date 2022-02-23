# AmogOS
A parody OS inspired by Among Us ඞ. (pronounced A-mog-O-S)

<img src="https://i.postimg.cc/vmF8tTVH/120727498-ecfc5e00-c497-11eb-9f92-a1b99318fee1.png"/> <img src="https://i.postimg.cc/m2Ym9qXt/130533968-d797e83d-e643-4c62-9264-7d46c2b67b48.png"/>

## General Info

This was mostly inspired by 
[this reddit post](https://www.reddit.com/r/unixporn/comments/nhomed/cinnamon_amogos_is_complete_icon_art_idea_by_u/) 
(which was further inspired by [this post](https://www.reddit.com/r/linuxmint/comments/n9h7b4/amogos_custom_background_mint_x_grey_theme/),
 which was posted by peek, our graphical designer. *cough cough Mutahar*). ඞAmogOSඞ is a meme OS based
 on the hit game Among Us, in the same vein as Hannah Montana Linux, but it's also developed and made to be a 
lightweight operating system. It's a bit ironic that 
ඞAmogOSඞ is lighter and less bloated than most mainstream distros (`chad ඞAmogOSඞ vs bloated mainstream distro` 
as youtuber TechHut put it). Why spend so much effort on a meme OS? Well, mainstream OSes suck so I want to dab on them
 by making a meme OS better than their professionallly developed ones. Don't take this too seriously :p

## Table of Contents (For lazy people who can't use the scroll wheel)
- [Testimonies](#Testimonies)  
- [Shut up, how do I become ඞSUSඞ](#Install) <br>
- [Testing ඞAmogOSඞ](#Testing-ඞAmogOSඞ)  <br>
- [Website](#Website)  
- [Merch](#Merch)  
- [Support](#Support)  
- [Features](#Features)  
- [Additional Notes](#Notes)  
- [Credits](#Credits)  
- [Donation](#Donation)  
- [Wallpapers](https://github.com/Amog-OS/AmogOS-Wallpapers)  

## Testimonies

- `ඞsussyඞ wussy` -[SomeOrdinaryGamers](https://www.youtube.com/watch?v=ixLuhDxNktk)
  
- `I'm pretty sure ඞAmogOSඞ has broken Mutahar's mental state and now he only says "ඞsussy wussyඞ" in like a really weird voice` -[Raspberry Pi News (developer)](https://www.youtube.com/watch?v=jiQVuhNiTZ0)
  
- `very sussy os` -[Moon 1789 (founder)](https://www.youtube.com/watch?v=hkzYIwMYds8)
  
- `chad ඞAmogOSඞ vs bloated mainstream distro` -[TechHut](https://www.youtube.com/watch?v=ymYIJYb2hYI)  

## Installation Notes
- **We are not resposible for ANY KIND OF DATA LOSS or any kind of problem not relating to ඞAMOGOSඞ, USE THIS AT YOUR OWN RISK**
- **x64 version is experimental builds , support will not be provided for it. **

- For x64 users: It takes like a whole 69420 secs to load the UI from usb boot so be patient!

## Install
- **Grab install instructions and the download links here on our website: https://www.amogos.studio/install.html.**

- (please note that by downloading ඞAmogOSඞ, you have a severely increased chance of being infected with the sussy ඞamogusඞ and AMOGID-69 virus. Please refer to [here](https://www.youtube.com/watch?v=nFstpT_YTro) for treatment methods).

## Testing ඞAmogOSඞ
- Now you can test out ඞAmogOSඞ online without downloading it at DistroTest: https://distrotest.net/AmogOS/. (note that DistroTest just has high latency, ඞAmogOSඞ actually runs extremely well even on my old 2013 laptop so get rekt Ubuntu)

## Website
- Our website is at https://www.amogos.studio, designed by **our** web developer Fengzi (he's too sus to keep his full name here). Also check out our partner OS [Jostro OS](https://github.com/jostroOS/jostro). The official startpage for ඞAmogOSඞ is at https://www.amogos.studio/startpage/.

## Merch
- Now stocking very ඞsusඞ stickers, shirts and other sussy stuff. All proceeds will be used to feed our developers, hire artists or be donated to charity.
https://amogos.myspreadshop.com/

## Support
- https://discord.gg/6ut87Hqukr (also see discord for our partner Jostro! https://discord.gg/jr469efBZM).

## Features
- Incredibly sussy
- Custom wallpapers and start menu icon that can be found in `~/Pictures/.amogOS/`. (or download them [here](https://github.com/Amog-OS/AmogOS-Wallpapers))
- Grey color palette to match Among Us.
- Custom neofetch logo.
- [MCPI Reborn](https://gitea.thebrokenrail.com/TheBrokenRail/minecraft-pi-reborn) (It's recommended you use the included "gMCPIL" launcher to launch the game).
- Uses Openbox WM and LXDE, allowing you to switch to 2 desktop spaces with the scroll wheel, similar to macOS.
- [among-sus](https://git.sr.ht/~martijnbraam/among-sus), an open-source among us alternative playable in terminal (use "among-sus-server" to host a localhost server and `among-sus` to connect to a server hosted on the current device, or `nc <ip on your LAN network>` to join a game on your network).
- [DollarSkip](https://github.com/CleanMachine1/DollarSkip), a simple C app to ignore `$` signs inputted at the start of a command, for copying commands from online tutorials.
- ncdu and tldr.
- Pi-Apps x86 for the x64 build.
- -69% compliance with the [ඞSUSඞ](https://en.m.wikipedia.org/wiki/Single_UNIX_Specification) specification.

### RPI only features, not present on x86_64 build
- 64-bit kernel enabled by default for speed, as well as to enable Wine support on devices earlier than the Raspberry Pi 4.
- Preinstalled CommanderPi, piwiz, Box86, Pi Power Tools, pi-apps, Colour Emoji Font, Stacer, legendary launcher (to replace Epic Games Launcher), and a 64-bit container to run aarch64 apps.
- Wine + box86 preinstalled for x86 windows syscall translation.
- piKiss and Pi-Apps preinstalled so you can install some games and also A M O N G U S.
(Among Us will run at ~5 fps on multiplayer play. It runs rather poorly, but for a game never intended to run on a CPU the size of a thumb with 2 layers of syscall translation (x86 windows -> x86 linux -> arm linux), it's decent. A small resolution is needed for the game to run without poor framerates).
- You can overclock your RPI with Commander Pi to get slightly more performance.

## Notes
- (RPI version only) You can use [vdesktop](https://github.com/Botspot/vdesktop) to test out the OS in a container without any lag and flashing needed on an ARM host.
- (RPI version only) Default username is "pi" and the password is "raspberry".
- (x86 version only) Default username is "amogos" and the password is "amogos".
- **ඞAmogOSඞ is not a custom OS, it's just riced RPi OS/Debian Bullseye for RPI and x64 versions respectively. It doesn't have any custom written source code. You can mount the squashfs .sb file and look at the rootfs yourself**

## Credits
- [Moon1789#5876](https://moon1789.github.io/), the UI lead, founder and man in the shadows. (inactive for now) 
- [Nooz#0816](https://www.youtube.com/channel/UCmp6JswV90SV5agNFGQuWkw), the main developer and active maintainer
- [peekatchoo#0001](https://www.reddit.com/u/_peekatchoo_), the graphical designer who made this possible in the first place. (no longer helping us, but absolute chad)
- ! !-Linkley steals your kinky#4642, for seeding the initial torrents
- Aelpxy#7590 for hosting our mirror downloads
- JoJo Autoboy#1931 for creating Jostro OS which brought together the necessary people to make AmogOS
- 疯子鸭#5218 (Pronounced "Fengzi") for making the website
- [Xonia](https://xoniaapp.com/) for providing our mirror
- [sUs !1!1!](https://media.discordapp.net/attachments/836822984110899261/929825908263620638/SPOILER_lol.jpg)

### Software credits
ඞAmogOSඞ would not be possible without the following open source software:

- Debian Bullseye, AntiX Project and Raspberry Pi OS.
- Openbox WM  
- LXDE for DE  
- xcompmgr for effects  
- Lightpad for the macOS launchpad clone'
- xfce4-panel for the dock and the panel
- Whisker for the start menu
- Arc-Grey-Darker theme
- Papirus icon theme
- https://github.com/sueperb/tasty-grubs for the x64 GRUB theme  
- https://linux-live.org/ our x64 build packager
- PiSafe and PiShrink for packaging the RPI builds  

And to **Innersloth**, for making one of the most famous and memed games of 2020 and onwards.  

### Donation
Donate to our OpenCollective, all of the funds' spending is transparent so you know what we do with your generous donations! We also support crypto https://opencollective.com/amogos (we are 2 broke high schoolers pls donate or you will become ඞsusඞ).

Alternative donation methods:
- Crypto : (For crypto donations please use OpenCollective!)
