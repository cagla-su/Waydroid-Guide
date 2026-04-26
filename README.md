# Table of Contents
- [Questions](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#questions)
    - [What is Waydroid?](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#what-is-waydroid)
    - [How does Waydroid differ from Android emulators?](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#how-does-waydroid-differ-from-android-emulators)
    - [Can I play all Android games through Waydroid?](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#can-i-play-all-android-games-through-waydroid)
- [Before Starting](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#before-starting)
- [Get Started](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#get-started)
- [Waydroid Tweaks](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#waydroid-tweaks)
    - [Run Waydroid on X11](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#run-waydroid-on-x11)
    - [Internet Connection Issue](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#internet-connection-issue)
    - [Hiding Waydroid Application Shortcuts](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#hiding-waydroid-application-shortcuts)
- [Conclusion](https://github.com/cagla-su/Waydroid-Guide/blob/main/README.md#conclusion)
## Türkçe Çeviri 🇹🇷
> [!NOTE]
> Rehberin [Türkçe çevirisi buradadır](https://github.com/cagla-su/Waydroid-Guide/blob/main/Waydroid-Rehberi.md). Birebir çeviri değildir ama içerik aynıdır.
# Waydroid Guide
Hello. In this guide, you will be informed about **what is Waydroid and how to install/configure it**. If you are ready, let's begin!
## Questions
### What is Waydroid?
[Waydroid](https://waydro.id/) is a **container-based compatibility layer** that **allows Android to run on Linux**.
### How does Waydroid differ from Android emulators?
Mobile Android devices use processors with **ARM-based** architectures while most of the computers use processors with **x86_64** architectures.
- So, Android emulators **emulate (imitate)**:
    - **CPU architecture:** They emulate **ARM** CPU architecture **instead of natively using** your CPU architecture.
    - **Android system services and kernel**
    - **Device hardware and sensors**
- However, Waydroid **does not emulate anything** mentioned above. It **directly uses your own computer hardware and Linux kernel** to run Android on Linux. That's why there is **almost no performance loss**.
### Can I play all Android games through Waydroid?
- **No**. Most of the Android games **do not support x86_64** architecture.
- It is possible to install an **ARM translation layer** to make **some incompatible games compatible**.
    - However, this **does not mean** that all games **will start working** after installing an ARM translation layer.
- **Some** popular Android games that **natively support keyboard and/or mouse configurations** are:
    - **Roblox** - *keyboard + mouse*
    - **Minecraft: Pocket Edition** - *keyboard + mouse*
    - **PUBG Mobile** - *keyboard + mouse* (it is hard to aim and shoot at the same time because it does not work like Android emulators)
    - **Honkai Impact** - *keyboard + mouse* (it is hard to change camera and attack at the same time)
    - **Asphalt Legends** - *mouse*
    - **Shadow Fight 3** - *keyboard + mouse* (2 and 4 work with mouse but it is hard to move and attack at the same time)
    - **Subway Surfers** - *keyboard*
    - **Geometry Dash** Series - *mouse*
    - **Angry Birds** Series - *mouse*
    - **Candy Crush** Series (and other King games) - *mouse*
    - **Clash Royale** (and other Supercell games) - *mouse*
## Before Starting
> [!IMPORTANT]
> Before starting, you should be aware of the fact that Waydroid **only runs on Wayland!** So if you are using X11, you should **apply some extra steps**.
## Get Started
- First of all, **install** Waydroid [following the steps according to your Linux distribution](https://docs.waydro.id/usage/install-on-desktops).
> [!IMPORTANT]
> Please make sure to install **vanilla** version, which is **the opposite of gapps**.
> Also **launch** Waydroid **once** before continuing.
- Next, **install** [Waydroid Helper](https://github.com/waydroid-helper/waydroid-helper) according to your distribution.
- After successfully installing and running the application, click this button to configure Waydroid:
<img width="630" height="180" alt="image" src="https://github.com/user-attachments/assets/4e1724b4-8a62-4253-bf2f-5f8466fa94ce" />

- Next, go to `Extensions` and install `LiteGapps-Lite`
- Then, scroll down and install `houdini` (for Intel CPUs) or `ndk_translation` (for AMD CPUs)
- Click this button to go back and run Waydroid.
<img width="630" height="180" alt="image" src="https://github.com/user-attachments/assets/9a82542b-6835-4bf8-9b48-290749de63d5" />
<img width="630" height="318" alt="image" src="https://github.com/user-attachments/assets/4db2f99f-cd0b-43ce-9004-561fe6533c64" />

- Once you see the app saying that **Waydroid session is running**, go to the configuration page and click `Settings`.
- If you have a **hybrid graphics setup** *(1 integrated + 1 dedicated GPU)*, scroll down and find `gpu`.
    - From `gpu`, select your **integrated GPU** because Waydroid **does not support hybrid graphics**.
- If you additionally would like to **change Waydroid's screen resolution permanently**, scroll up and find `persist.waydroid.width` and `persist.waydroid.height` and change the values to your liking.
<img width="548" height="125" alt="image" src="https://github.com/user-attachments/assets/1b427367-a0c1-41db-b963-12fa4e1b9796" />

- Lastly, go to `Details` and click `Retrieve GSF ID`.
    - **Copy** the numbers you see and click `Open registration page`. **Paste** the numbers to the website that opened and click `Register`.
    - Make sure to **restart Waydroid** after completing the steps.
## Waydroid Tweaks
### Run Waydroid on X11
- Install `weston` package using your package manager.
- Inside Waydroid Helper, go to `Scripts` and click `Launch Waydroid with Weston`.
- This is how you can run Waydroid on X11!
> [!NOTE]
> If this method does not work, try **launching weston manually** and execute `waydroid show-full-ui` command **inside weston**.
### Internet Connection Issue
This issue generally occurs from the **firewall** your system is using.
- This step is explained in [Arch Wiki](https://wiki.archlinux.org/title/Waydroid#Network)
### Hiding Waydroid Application Shortcuts
- You might have noticed that Waydroid application shortcuts are **seen on your Linux applications list**. In order to hide them:
    - Inside Waydroid Helper, go to `Scripts` and click `Toggle Waydroid App Icons`, make sure to **restart your Linux system** for applying changes.
- Now you are **ready to use Waydroid!**
# Conclusion
This guide was about Waydroid installation and configuration. I hope the guide has been useful. Thank you for reading, have a nice day!
