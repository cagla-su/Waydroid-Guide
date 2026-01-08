# Table of Contents
- [Questions](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#questions)
    - [What is Waydroid?](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#what-is--waydroid) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
    - [How does Waydroid differ from Android emulators?](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#how-does--waydroid-differ-from--android-emulators) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> 
    - [Can I play all Android games through Waydroid?](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#can-i-play-all--android-games-through--waydroid) <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" />  <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
- [Before Starting](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#before-starting)
- [Get Started](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#get-started)
- [Waydroid Tweaks](https://github.com/cagla-su/Waydroid-Guide/tree/main?tab=readme-ov-file#-waydroid-tweaks) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
    - [Run Waydroid on X11](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#run--waydroid-on--x11) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" />
    - [Internet Connection Issue](https://github.com/cagla-su/Waydroid-Guide?tab=readme-ov-file#internet-connection-issue)
    - [Hiding Waydroid Application Shortcuts](https://github.com/cagla-su/Waydroid-Guide/tree/main?tab=readme-ov-file#hiding--waydroid-application-shortcuts) <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" />
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
- **Some** popular <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android games that **natively support keyboard and/or mouse configurations** are:
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/26dec68d-79c7-4f82-875a-ab1a21bb11f5" /> **Roblox** - *keyboard + mouse*
    - <img width="16" height="25" alt="mc" src="https://github.com/user-attachments/assets/b48ac714-01b3-4aaf-bb00-348e811eb0d5" /> **Minecraft: Pocket Edition** - *keyboard + mouse*
    - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/32a419a2-833c-4831-b274-483ccea67497" /> **PUBG Mobile** - *keyboard + mouse* (it is hard to aim and shoot at the same time because it does not work like <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android emulators)
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
- First of all, **install** <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid [following the steps according to your Linux distribution](https://docs.waydro.id/usage/install-on-desktops). Please make sure to install **vanilla** version, which is **the opposite of gapps**.
- Next, **install** [Waydroid Helper](https://github.com/waydroid-helper/waydroid-helper) according to your distribution.
- After successfully installing and running the application, click this button to configure <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid:
<img width="630" height="180" alt="image" src="https://github.com/user-attachments/assets/4e1724b4-8a62-4253-bf2f-5f8466fa94ce" />

- Next, go to `Extensions` and install `LiteGapps-Lite`
- Then, scroll down and install `houdini` (for Intel CPUs) or `ndk_translation` (for AMD CPUs)
- Click this button to go back and run <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid.
<img width="630" height="180" alt="image" src="https://github.com/user-attachments/assets/9a82542b-6835-4bf8-9b48-290749de63d5" />
<img width="630" height="318" alt="image" src="https://github.com/user-attachments/assets/4db2f99f-cd0b-43ce-9004-561fe6533c64" />

- Once you see the app saying that <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid session is running**, go to the configuration page and click `Settings`.
- If you have a **hybrid graphics setup** *(1 integrated + 1 dedicated GPU)*, scroll down and find `gpu`.
    - From `gpu`, select your **integrated GPU** because <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid **does not support hybrid graphics**.
- If you additionally would like to **change <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid's screen resolution permanently**, scroll up and find `persist.waydroid.width` and `persist.waydroid.height` and change the values to your liking.
<img width="548" height="125" alt="image" src="https://github.com/user-attachments/assets/1b427367-a0c1-41db-b963-12fa4e1b9796" />

- Lastly, go to `Details` and click `Retrieve GSF ID`.
    - **Copy** the numbers you see and click `Open registration page`. **Paste** the numbers to the website that opened and click `Register`.
    - Make sure to **restart <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid** after completing the steps.
## <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Tweaks
### Run <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/3dd1cec2-812d-4367-856a-0c008cbd7ede" /> X11
- Install `weston` package using your package manager.
- Inside Waydroid Helper, go to `Scripts` and click `Launch Waydroid with Weston`.
- This is how you can run <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid on X11!
### Internet Connection Issue
This issue generally occurs from the **firewall** your system is using.
- This step is explained in <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/17e40f3d-086e-4979-bd7a-786ce5864c66" /> [Arch Wiki](https://wiki.archlinux.org/title/Waydroid#Network)
### Hiding <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Application Shortcuts
- You might have noticed that <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid application shortcuts are **seen on your Linux applications list**. In order to hide them:
    - Inside Waydroid Helper, go to `Scripts` and click `Toggle Waydroid App Icons`, make sure to **restart your Linux system** for applying changes.
- Now you are **ready to use <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid!**
# Conclusion
This guide was about Waydroid installation and configuration. I hope the guide has been useful. Thank you for reading, have a nice day! <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/60e83c84-d8f8-4035-8052-08aabe1d83a1" />
