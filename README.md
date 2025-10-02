# Waydroid Guide
Hello. In this guide, you will be informed about **what is <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid and how to install/configure it**. If you are ready, let's begin!
## Questions
### What is <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid?
<img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> [Waydroid](https://waydro.id/) is a container-based compatibility layer that allows <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android to run in a containerized environment on Linux systems.
### How Does <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Differ from <img width="16" height="25" alt="image-removebg-preview(1)" src="https://github.com/user-attachments/assets/cec27060-1d67-48e1-8f29-a3a5b639fde8" /> Android Emulators?
Mobile phones use processors with **ARM-based** architectures while most of the computers use processors with **x86_64** architectures.
- So, Android emulators **emulate (imitate)** everything about the Android system to make Android applications and games run on computers. This process delivers **naturally poor** performance especially if you do not have a powerful system.
  - To explain further, Android emulators emulate:
    - **CPU Architecture:** They emulate **ARM** CPU architecture instead of using your CPU architecture natively.
      - **Android System Services and Kernel:** They emulate Android's kernel components in a virtual environment.
      - **Device Hardware and Sensors**
        - GPS
        - Compass sensor, gyroscope, magnetometer etc.
        - Camera, microphone and speakers
        - Wi-Fi and telephony functions like phone calls, SMS etc.
        - Storage
        - GPU rendering
        - Keyboard, mouse, controllers etc.
- However, <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid **does not imitate** anything mentioned above. It directly uses **your own computer hardware and Linux kernel** to run Android on Linux. That's why there is **almost no performance loss**.
### Can I play all Android games through <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid?
No. Most of the Android games **do not support** x86_64 architecture. It is possible to install an **ARM translation layer** to make incompatible games compatible, however if that game does not support keyboard + mouse configuration, you will be unable to play it anyway.
- Some Android games that support keyboard + mouse configuration are:
  - Roblox
  - Minecraft: Pocket Edition
  - Subway Surfers
  - aa (and derivatives)
  - Stardew Valley
  - Asphalt 8
  - Geometry Dash
  - Shadow Fight 3
- Other than that, many Android games like **Angry Birds, Stick Hero etc.** that only require a touchscreen can be played through your mouse.
## Before Starting
Before starting, I should say that <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid runs **only on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/a00199c8-1319-4180-bbae-9e77988a03d3" /> Wayland!!!** So if you are using <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/4d1fca1d-3f5b-4de8-af0a-7555255af4f2" /> X11, you should apply some extra steps.
## Get Started - <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/a00199c8-1319-4180-bbae-9e77988a03d3" /> Wayland
- First of all, install <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid [following the steps according to your Linux distribution](https://docs.waydro.id/usage/install-on-desktops).
- Next, execute `sudo waydroid init` command in your terminal to install Android in <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid.
- Next, install [this script](https://github.com/casualsnek/waydroid_script) to configure <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid easier.
  - If you are confused, [install the required dependency package for your Linux distribution](https://github.com/casualsnek/waydroid_script?tab=readme-ov-file#dependencies) first and [execute the specified commands in your terminal](https://github.com/casualsnek/waydroid_script?tab=readme-ov-file#interactive-terminal-interface) to run the script.
- After successfully running the script, follow these steps:
  - `Android 13` **-** `Install` **-** `Choose "microg and libhoudini (or libndk if you use an AMD CPU)" using Space button` **-** `Enter` **-** `Select "Standard" as the MicroG variant`
- After these steps, you are officially ready to use <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid.
## How to Run <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/4d1fca1d-3f5b-4de8-af0a-7555255af4f2" /> X11?
- Simply apply the previous steps to install <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid properly.
- After applying the previous steps, install `weston` package using your package manager.
- Next, create a file and name it whatever you want. Change the file's extension as `.sh` and open the file using a text editor.
  - Your bash script's content should be:
```
#!/bin/bash

WAYLAND_DISPLAY=waydroid-1 weston --socket=waydroid-1 --backend=x11-backend.so --width=1280 --height=720 &
sleep 3
waydroid session start
WAYLAND_DISPLAY=waydroid-1 waydroid show-full-ui
```
If you want, you can change the `--width` and `--height` values according to your liking.
- After saving the changes, move the file to a location that you will be able to remember the path.
- Next, open terminal in that location and give your file the necessary permissions by executing the command below:
```
sudo chmod +x yourfile.sh
```
- Now we have the script that will automatically launch <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/4d1fca1d-3f5b-4de8-af0a-7555255af4f2" /> X11 without issues. However, running `./yourfile.sh` command every time you want to use <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid can be annoying. That's why, let's make it look like an app!
- Create a file with `.desktop` file extension and open it using a text editor.
  - Your file's content should be:
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
After saving the changes, move the file to the necessary location to make your system detect it as an application executing the command below:
```
sudo mv yourfile.desktop ~/.local/share/applications/
```
- After that, you should see an app called <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> **Waydroid-X11** in your applications list. You can comfortably start launching <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid using that shortcut on <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/4d1fca1d-3f5b-4de8-af0a-7555255af4f2" /> X11!
## <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Hybrid Graphics Setup
- <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid does not run on hybrid graphics (computers with two GPUs) setup. So that's why we should make Waydroid use the integrated GPU.
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
## <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid Internet Connection Issue
This issue generally occurs from the firewall your system is using.
- This step is explained in [Arch Wiki](https://wiki.archlinux.org/title/Waydroid#Network)
## Post Installation
- First of all, the store application we will be using is **Aurora Store** and not Play Store. Do not worry, Aurora Store can install everything that Play Store can.
- Next, for MicroG configuration, open **microG Settings** app and:
  - Enable `Google device registration`, `Cloud Messaging` and `Google SafetyNet`.
- After these steps, you can finally start downloading your favourite software!
- When you close <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid, it generally keeps running in the background. If you would like to stop it from running in the background, you should execute the command below:
```
waydroid session stop
```
### Notes
- On your Linux system, you might see the Android apps inside <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid in your applications list and you might find seeing them annoying. To hide them:
  - Go to `~/.local/share/applications/` location and edit all `.desktop` files that belong to <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid one by one.
    - What we are going to do while editing the files using a text editor is adding `NoDisplay=true` at the end of the `[Desktop Entry]` section of each `.desktop` file that belongs to <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid.
  - After saving the changes, the icons should be hidden from your applications list in a few minutes. Removing the .desktop files would not work because they would be added again after running <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid.
- Also, if you are using <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid through <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/a00199c8-1319-4180-bbae-9e77988a03d3" /> Wayland and want to change default screen resolution, you should execute the command below in terminal while <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid is running:
```
waydroid prop set persist.waydroid.width [value]
waydroid prop set persist.waydroid.height [value]
```
- Now you are ready to use <img width="16" height="25" alt="image" src="https://github.com/user-attachments/assets/92f8c7dc-7a41-4a92-bc71-0d69bd2d22b9" /> Waydroid!
# Conclusion
This guide was about Waydroid installation and configuration. I hope the guide has been useful. Thank you for reading, have a nice day! 🐧
