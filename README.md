# Table of Contents
- [Questions](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#questions)
    - [What is Waydroid?](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#what-is--waydroid) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
    - [How does Waydroid differ from Android emulators?](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#how-does--waydroid-differ-from--android-emulators) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> 
    - [Can I play all Android games through Waydroid?](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#can-i-play-all--android-games-through--waydroid) <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" />  <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
- [Before Starting](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#before-starting)
- [Get Started](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#get-started)
- [Waydroid Tweaks](https://github.com/cagla-su/Waydroid-Guide/tree/main?tab=readme-ov-file#-waydroid-tweaks)
    - [Run Waydroid on X11](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#run--waydroid-on--x11) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" />
    - [Hybrid Graphics Setup](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#hybrid-graphics-setup)
    - [Internet Connection Issue](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#internet-connection-issue)
- [Notes](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#notes)
- [Conclusion](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#conclusion)
## Türkçe Çeviri 🇹🇷
Rehberin [Türkçe çevirisi buradadır](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md). Birebir çeviri değildir ama içerik aynıdır.
# Waydroid Guide
Hello. In this guide, you will be informed about **what is <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid and how to install/configure it**. If you are ready, let's begin!
## Questions
### What is <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid?
<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> [Waydroid](https://waydro.id/) is a **container-based compatibility layer** that **allows <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android to run on Linux**.
### How does <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid differ from <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android emulators?
Mobile <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android devices use processors with **ARM-based** architectures while most of the computers use processors with **x86_64** architectures.
- So, <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android emulators **emulate (imitate)**:
    - **CPU architecture:** They emulate **ARM** CPU architecture **instead of natively using** your CPU architecture.
    - **<img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android system services and kernel**
    - **Device hardware and sensors**
- However, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid **does not emulate anything** mentioned above. It **directly uses your own computer hardware and Linux kernel** to run <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android on Linux. That's why there is **almost no performance loss**.
### Can I play all <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android games through <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid?
- **No**. Most of the <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android games **do not support x86_64** architecture.
- It is possible to install an **ARM translation layer** to make **some incompatible games compatible**.
    - However, this **does not mean** that all games **will start working** after installing an ARM translation layer.
- You can make some games that **partially** support PC controls support them **completely** using [scrcpy](https://github.com/Genymobile/scrcpy). It is easy to use scrcpy, simply [install the package following the instructions](https://github.com/Genymobile/scrcpy/blob/master/doc/linux.md) and execute `scrcpy` command in your terminal after launching <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid.
  - **Some** popular <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android games that **natively support keyboard and/or mouse configurations** are:
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/26dec68d-79c7-4f82-875a-ab1a21bb11f5" /> **Roblox** - *keyboard + mouse*
    - <img width="16" height="25" alt="mc" src="https://github.com/user-attachments/assets/b48ac714-01b3-4aaf-bb00-348e811eb0d5" /> **Minecraft: Pocket Edition** - *keyboard + mouse*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/32a419a2-833c-4831-b274-483ccea67497" /> **PUBG Mobile** - *keyboard + mouse* (it is hard to aim and shoot at the same time because it does not work like <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android emulators)
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/a8b6315f-3ed8-4463-98f6-42ccb8c2ed96" /> **Mobile Legends: Bang Bang** - *keyboard + limited mouse support, can be fixed using "scrcpy"*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/c3e34de1-8499-4136-8a18-e2b1e14c70fc" /> **Honkai Impact** - *keyboard + mouse* (it is hard to change camera and attack at the same time)
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/f56ff322-e58f-4cbe-97d2-52e20371f169" /> **Asphalt Legends** - *mouse*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/b2d2b81e-7dbd-4966-9597-49007c5ede65" /> **Shadow Fight 3** - *keyboard + mouse* (2 and 4 work with mouse but it is hard to move and attack at the same time)
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/9f6735c8-b0bc-45c9-83b0-5a0eb70af3fd" /> **Subway Surfers** - *keyboard*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/7e2863a6-6dca-467b-9570-d10424917b79" /> **Geometry Dash** Series - *mouse*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/b1dd7b37-fe47-4ddc-850a-0d024b7837fd" /> **Angry Birds** Series - *mouse*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/98707f14-2a4e-43b4-be96-51e42f5a687a" /> **Candy Crush** Series (and other King games) - *mouse*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/56449c8c-1ca6-467a-9a8a-06ede7106448" /> **Clash Royale** (and other Supercell games) - *mouse*
## Before Starting
Before starting, you should be aware of the fact that <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid **only runs on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/a00199c8-1319-4180-bbae-9e77988a03d3" /> Wayland!** So if you are using <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11, you should **apply some extra steps**.
## Get Started
- First of all, **install** <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid [following the steps according to your Linux distribution](https://docs.waydro.id/usage/install-on-desktops).
- Next, **execute** `sudo waydroid init` command in your terminal to install <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid.
- Next, **install** [this Waydroid script](https://github.com/casualsnek/waydroid_script) to configure <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid with an easier way.
- After successfully running the script, follow these steps:
  - `Android 13` **-** `Install` **-** `Select "gapps" and "libhoudini (or libndk if you use an AMD CPU)" using Space button` **-** `Enter`
  - `Run the script again` **-** `Android 13` **-** `Get Google Device ID to Get Certified` **-** `Open the link that the script shows you and enter the ID (numbers) you see on your terminal`
- You are now **officially ready to use <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid**.
## <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Tweaks
### Run <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11
- Simply **apply the** [previous steps](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#get-started) to install <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid properly.
- After applying the previous steps, **install** `weston` package using your package manager.
- Next, **create a file** and **name it** as you wish. **Change the file's extension** as `.sh` and **edit the file** using a text editor.
  - Your bash script's content **should look like this**:
```
#!/bin/bash

WAYLAND_DISPLAY=waydroid-1 weston --socket=waydroid-1 --backend=x11-backend.so --width=1280 --height=720 &
sleep 3
waydroid session start
WAYLAND_DISPLAY=waydroid-1 waydroid show-full-ui
```
If you want, you can change the `--width` and `--height` values according to your liking.
- After **saving** the changes, **move the file** to a location that you will be able to **remember the path**.
- Next, **open terminal** in that location and **give your file the necessary permissions** by **executing** the command below:
```
sudo chmod +x yourfile.sh
```
- Now you have the script that **automatically launches <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid** on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11 without issues.
- However, running `./yourfile.sh` command every time you want to use <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid **can be annoying**. That's why, let's **make it look like an application!**
- **Create a file** with `.desktop` file extension and **edit it** using a text editor.
  - Your file's content **should look like this**:
```
[Desktop Entry]
Name=Waydroid-X11
Comment=Launch Waydroid inside Weston
Exec=sh -c '~/location/of/yourfile.sh'
Icon=waydroid
Terminal=false
Type=Application
Categories=System;
```
After **saving** the changes, **move the file** to the **specific location** to **make your system detect it as an application executing the command** below:
```
sudo mv yourfile.desktop ~/.local/share/applications/
```
- Finally, you should **see an app** called <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid-X11** in your **applications list**. You can **start launching <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid** using that **shortcut** on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11!
### Hybrid Graphics Setup
- <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid is **unable to run on hybrid graphics** (computers with two GPUs) **setup**. That's why you should **make Waydroid use** the **integrated GPU**.
```
sudo nano /var/lib/waydroid/waydroid_base.prop
```
```
ro.hardware.gralloc=default
ro.hardware.egl=mesa
```
```
waydroid session stop
```
### Internet Connection Issue
This issue generally occurs from the **firewall** your system is using.
- This step is explained in <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/17e40f3d-086e-4979-bd7a-786ce5864c66" /> [Arch Wiki](https://wiki.archlinux.org/title/Waydroid#Network)
## Notes
- When you **exit <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid**, it **keeps running in the background**. If you would like to **stop it** from **running in the background**, you should **execute the command below**:
```
waydroid session stop
```
- On your Linux system, you might see the <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> **Android apps in your applications list**. If you would like to **hide them**:
  - Go to `~/.local/share/applications/` and **edit all `.desktop` files** that belong to <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid **one by one**.
    - While editing the files, **add** `NoDisplay=true` at the end of the `[Desktop Entry]` section of **each `.desktop` file** that belongs to <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid.
  - After **saving** the changes, the **icons should be hidden** from your applications list **in a few minutes**.
    - **Removing** the .desktop files instead **would not work** because they would **be added again after running <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid**.
- Lastly, if you want to **change the default screen resolution permanently**, you should **execute the command** below in terminal while <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid is **still running**:
```
waydroid prop set persist.waydroid.width [value]
waydroid prop set persist.waydroid.height [value]
```
- Now you are **ready to use <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid!**
# Conclusion
This guide was about Waydroid installation and configuration. I hope the guide has been useful. Thank you for reading, have a nice day! <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/60e83c84-d8f8-4035-8052-08aabe1d83a1" />
