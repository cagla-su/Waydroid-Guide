# Waydroid Guide
Hello 🤭. In this guide, you will be informed about what is Waydroid, how to install and configure it in a beginner friendly way.
## Questions
**What is Waydroid?**
- [Waydroid](https://waydro.id/) is a container-based compatibility layer that enables Android to run in a containerized environment on Linux systems. You can use your favourite Android applications and play a good amount of Android games through Waydroid.
**How does Waydroid differ from Android emulators?**
- Mobile phones have processors that use **ARM-based** architecture while most of the computers have processors that use **x86_64** architecture.
  - So, Android emulators **emulate (imitate)** everything about the Android system software-side to make Android applications and games run on computers and this process delivers **naturally poor** performance especially if you do not have a powerful system.
    - To explain further, Android emulators emulate:
      - **CPU Architecture** `:` They emulate **ARM** CPU architecture instead of using your CPU architecture natively.
      - **Android System Services and Kernel** `:` They emulate Android's kernel components in a virtual environment.
      - **Device Hardware and Sensors**
        - GPS
        - Compass sensor, gyroscope, magnetometer etc.
        - Camera, microphone and speakers
        - Wi-Fi and telephony functions like phone calls, SMS etc.
        - Storage
        - GPU rendering
        - Keyboard, mouse, controllers etc.
  - However, Waydroid **does not imitate** anything mentioned above but it directly uses **your own computer hardware and Linux kernel** to run Android on Linux. That's why there is **almost no performance loss**.
  - Plus, just like how WINE directs Windows library files into Linux library files to make Windows applications run on Linux, Waydroid performs a similar process for directing Android library files into Linux library files for software compatibility.
**Can I play all Android games through Waydroid?**
- No. Most of the Android games do not support x86_64 architecture. It is possible to install an **ARM translation layer** to make incompatible games compatible, however if that game does not support keyboard + mouse configuration, you will be unable to play the game anyway.
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
