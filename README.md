## AmogOS
An Among Us-inspired OS ඞ.

<img src="https://i.postimg.cc/vmF8tTVH/120727498-ecfc5e00-c497-11eb-9f92-a1b99318fee1.png"/> <img src="https://i.postimg.cc/m2Ym9qXt/130533968-d797e83d-e643-4c62-9264-7d46c2b67b48.png"/>

## General Info:  

This was mostly inspired by [this reddit post](https://www.reddit.com/r/unixporn/comments/nhomed/cinnamon_amogos_is_complete_icon_art_idea_by_u/) (and also yoinks the icon and wallpaper from it, originally made by `u/_peekatchoo_` on Reddit). AmogOS is a meme OS based on the hit game Among Us, in the same vain as Hannah Montana Linux, but it's also developed and made to be a highly lightweight operating system that can be used as a desktop OS if one really wanted to, and it's a bit ironic that AmogOS is lighter and less bloated than most mainstream distros (`chad AmogOS vs bloated mainstream distro` as Youtuber TechHut put it).

## Table of Contents (For lazy ppl who dont wanna scroll):
- [Testimonies](#Testimonies)  
- [Shut up, how do I install it](#Install) <br>
- [Testing AmogOS](#Testing-AmogOS)  <br>
- [Website](#Website)  
- [Merch](#Merch)  
- [Support](#Support)  
- [Features](#Features)  
- [Additional notes](#Notes)  
- [Credits](#Credits)  
- [Donation](#Donation)  
- [Wallpapers](https://github.com/jostroOS/AmogOS-Wallpapers)  

## Testimonies

- `sussy wussy` -[SomeOrdinaryGamers](https://www.youtube.com/watch?v=ixLuhDxNktk)
  
- `I'm pretty sure AmogOS has broken Mutahar's mental state and now he only says "sussy wussy" in like a really weird voice` -[Raspberry Pi News (developer)](https://www.youtube.com/watch?v=jiQVuhNiTZ0)
  
- `why did I even make this os` -[Moon 1789 (founder)](https://www.youtube.com/watch?v=hkzYIwMYds8)
  
- `chad AmogOS vs bloated mainstream distro` -[TechHut](https://www.youtube.com/watch?v=ymYIJYb2hYI)  

## Installation Notes
**We are not resposible for ANY KIND OF DATA LOSS or any kind of problem not relating to AMOGOS, USE THIS AT YOUR OWN RISK**

NOTE: We have both Raspberry Pi and x86_64 builds. Raspberry Pi 32-bit builds will have `RPI` in their names and PC x86_64 builds will have `x64` in their names in their respective releases.  

For x64 users: It takes like a whole 69420 secs to load the UI from usb boot so be patient!

For RPI users: SPAM ESC KEY ON THE KEYBOARD WHEN BOOTING AMOGOS ON AN ACTUAL PI TO FIX BLINKING CURSOR/BOOT ISSUE.

## Install
**Grab install instructions and the download links here on our website: https://www.jostroos.ml/amogos/install.html.**

(please note that by downloading AmogOS, you have a severely increased chance of being infected with the deadly amogus and AMOGID-16 virus. Please refer to [Here](https://www.youtube.com/watch?v=nFstpT_YTro) for treatment methods).

## Testing AmogOS
You can run AmogOS online without installing at DistroTest: https://distrotest.net/AmogOS/.

## Website
Our website is at https://www.jostroos.ml/amogos, designed by our web developer Fengzi (he's too sus to keep his full name here). Also check out our parent OS [Jostro OS](https://github.com/jostroOS/jostro). The official startpage for AmogOS is at https://www.jostroos.ml/amogos/startpage/.

## Merch
Now stocking very sus stickers (we priced it as cheap as possible so pls buy some my family is starving from the among us skins I'm purchasing). (also use code `IMBROKE` for 5$ off and `SUSSYBAKA` for free shipping). 
https://merch.jostroos.ml/ 

If you wanna print your own stickers download them [here](https://cdn.discordapp.com/attachments/867502562953658428/867512035687530526/amog-icon.png) and [here](https://cdn.discordapp.com/attachments/867502562953658428/867871352035082300/amogoschip-sticker.png)

## Support
https://discord.gg/k4d24VaAJN or Mail us over at amogos69420@gmail.com.

## Features
- Too sus.
- Custom wallpapers and start menu icon that can be found in `~/Pictures/.amogOS/`.
- Grey color palette to match Among Us.
- Custom neofetch logo.
- [MCPI Reborn](https://gitea.thebrokenrail.com/TheBrokenRail/minecraft-pi-reborn) (It's recommended you use the included `gMCPIL` launcher to launch the game).
- Uses Openbox WM and LXDE, allowing you to switch to 2 desktop spaces with the scroll wheel, similar to macOS.
- [among-sus](https://git.sr.ht/~martijnbraam/among-sus), an open-source among us alternative playable in terminal (use `among-sus-server` to host a localhost server and `among-sus` to connect to a server hosted on the current device, or `nc <ip on your LAN network>` to join a game on your network).
- [DollarSkip](https://github.com/CleanMachine1/DollarSkip), a simple C app to ignore `$` signs inputted at the start of a command, for copying commands from online tutorials.
- ncdu and tldr.
- Pi-Apps x86 for x64 build.

### RPI only features, not present on x86_64 build
- 64-bit kernel enabled by default for speed, as well as to enable Wine support on RPI 3.
- Preinstall CommanderPi, piwiz, Box86, Pi Power Tools, pi-apps, Colour Emoji Font, Stacer, legendary launcher (to replace Epic Games Launcher), and preinstall a 64-bit container to run aarch64 apps.
- Wine + box86 preinstalled for x86 windows syscall translation.
- piKiss and Pi-Apps preinstalled so you can install some games and also A M O N G U S.
(Among Us will run at ~5 fps on multiplayer play. It runs rather poorly, but for a game never intended to run on a CPU the size of a thumb with 2 layers of syscall translation (x86 windows -> x86 linux -> arm linux), it's decent. A small resolution is needed for the game to run without poor framerates).
- You can overclock your RPI with Commander Pi to get slightly more performace.

## Notes
- (RPI version only) You can use [vdesktop](https://github.com/Botspot/vdesktop) to test out the OS in a container without any lag and flashing needed on an ARM host.
- (RPI version only) Default username is "pi" and password is "raspberry".
- (x86 version only) Default username is "amogos" and password is "amogos".
- **AmogOS is not a custom OS, it's just riced RPi OS/Debian Bullseye for RPI and x64 versions respectively. It doesn't have any custom written source code.**
- **AmogOS will never be based off OpenSUSe.**

# Credits
- Founder/UI Dev: Moon1789#6969 (https://moon1789.github.io/)
- Main dev/Packager: RPiNews#0816 (https://www.youtube.com/channel/UCmp6JswV90SV5agNFGQuWkw) (I also go by https://www.youtube.com/channel/UCOImY0CpIrsOmbODaWYt17A for those of you who see me comment on AmogOS related content and call me sussy impostor :p)
- Graphical designer: peekatchoo#0001 (no longer helping us, but absolute chad)
- App developer: felixisweird
- Thanks to Linkley Steals Your Kinky 2#4642 for hosting torrents
- Thanks to JoJo Autoboy#1931 for being our overlord
- Thanks to the jostroOS dev team for letting us use their GH org and website to host downloads!
- Thanks to [Phene](https://phene.dev) for hosting a [mirror](https://storage.phene.dev/amogos) and touching up this document.
- [sUs !1!1!](https://linustechtips.com/uploads/monthly_2021_03/1647043410_LinusWindowsXP.png.52fed85d600faa323ec2fa515d1b3ff7.png)

(Note: Discord tags and names may change)

### Software credits
AmogOS would not be possible without the following open source software:

#### Base OS  

- Debian and RPI OS  

#### UI  

- Openbox WM  
- LXDE for DE  
- xcompmgr for effects  
- Lightpad for the launchpad thing  
- xfce4-panel for dock and the panel

-KDE Plasma 5 Version coming soon...  

#### Misc  

- https://github.com/sueperb/tasty-grubs for the x64 GRUB theme  
- https://linux-live.org/ our x64 build packager  
- https://github.com/Botspot/Pi-Power-Tools and https://www.raspberrypi.org/forums/viewtopic.php?t=247568 for packaging the RPI builds  
- [Insert the names of all the apps included that im too lazy to type]  

And to Innersloth, for making one of the most famous and memed games of 2020 and onwards.  

### Donation
Donate to our opencollective, all funds spending is transparent so you know what we do with your generous donations! https://opencollective.com/amogos (we are 2 broke high schoolers pls donate or become sus)

- Duino Coin: `rpinews` & `moon1789`
- Bitcoin: bc1qs0vg6a4plfqzhtg9nq0wgyltrv9ghlaymyug8q
- Tron: THAM7LmhrsaDrQULdaKBsnKs6S537DiCAk
- Ethereum: 0x31A1DF3654c2827E77e2426E88c9Ec22ab701D5A
- Doge: D6zggTnSXcp6iByip71XC9qT1DdH8fdftB
- (peek slap your donation adresses here)
