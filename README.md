# amogOS
Among Us-inspired OS for the Raspberry Pi.

![image](https://user-images.githubusercontent.com/44128563/119536694-98920980-bd46-11eb-950e-425475bb90ac.png)


This was mostly inspired by https://www.reddit.com/r/unixporn/comments/nhomed/cinnamon_amogos_is_complete_icon_art_idea_by_u/ (and also yoinks the icon and wallpaper from it), 

Initially made by Moon1789#6969, RPiNews#0816 and the folks here at Jostro OS

EDIT: AHHH Mutahar covered the OS!!!!! I am beyond words that he made a video on this crappy OS. This OS was inspiried by other similiar mods people have made (credit above). I'm just gonna sneak in my youtube channel here to capitalize on the fame :) I cover Raspberry Pi-related content: https://www.youtube.com/channel/UCmp6JswV90SV5agNFGQuWkw

## Download:

https://github.com/jostroOS/amogOS/releases/latest

### Get support on Discord:
https://discord.gg/k4d24VaAJN

## Features

- Sus
- Custom wallpaper and start menu icon
- Mostly grey colour palette
- Custom neofetch icon
- Wine + box86 preinstalled for x86 windows translation
- piKiss and pi-apps preinstalled so you can install some games and also A M O N G U S
(Among Us will run at ~5 fps on multiplayer play. It's a really crap framerate, but for a game never intended to run on a CPU the size of a thumb with 2 layers of syscall translation (x86 windows -> x86 linux -> arm linux), it's decent. A small resolution is needed for the game to run without insane lag.)

## Notes

- You can use https://github.com/Botspot/vdesktop to test out the OS in a container without any lag on a arm host.
- This is meant for RPI 3 and 4. If you would like to run it on a x86 system, you can do so via qemu. Download https://drive.google.com/file/d/1wgkJYwNV7jqxNFW_uRPPZ3JKvd87mVPE/view?usp=sharing and read the instructions inside the zip to find how to replace the twister os image with amogOS.
- Default username is "pi" and password is "raspberry"
- By default, a 512mb GPU memory is set. This is to make 256mb of memory available to Among Us so it doesn't go bonkers with more lag. Feel free to change it if you are experiencing problems or you don't plan on playing among us.
