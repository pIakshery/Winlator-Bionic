

<p align="center">
  <img src="logo.png" alt="Winlator Bionic" width="600">
</p>

# Winlator Bionic

> ⚠️ **License notice:** This repository is distributed under a **custom restricted license** — personal, non-commercial use only. Redistribution, publication, or public forking without prior written permission is prohibited. See [LICENSE](LICENSE) for full terms.

Winlator is an Android application that lets you run Windows (x86\_64) applications with Wine — bringing full-fledged PC gaming and software to your phone or tablet. It supports standard `x86_64` containers powered by Box86/Box64, as well as `Arm64EC` containers running on FEXCore (64/32-bit) or an optional WowBox64 (32-bit).

This build is a fork of **Winlator Bionic** by [Pipetto-crypto](https://github.com/Pipetto-crypto/winlator), fine-tuned for smoother performance, better compatibility, and a cleaner experience out of the box — with an integrated MangoHud overlay for real-time performance monitoring.

# Useful Tips

  - Here is a tutorial from ZeroKimchi channel on how to use Winlator Bionic:
    https://youtu.be/EJDWZUGF9sk?si=e3Z-DdmMJSYKduWz
  - If you are using an `x86_64` container and experiencing performance issues, try changing the Box86/Box64 preset to **Performance** in Container Settings -\> Advanced Tab.
  - If you are using an `Arm64EC` container, try using FEXCore version **2609** (the latest) in the container settings for better compatibility or performance.
  - For applications that use .NET Framework, try installing Wine Mono found in Start Menu -\> System Tools.
  - If some older games don't open, try adding the environment variable MESA\_EXTENSION\_MAX\_YEAR=2003 in Container Settings -\> Environment Variables.
  - Try running the games using the shortcut on the Winlator home screen, there you can define individual settings for each game.
  - To speed up the installers, try changing the Box86/Box64 preset to Intermediate in Container Settings -\> Advanced Tab.
  - A built-in **MangoHud overlay** is included for on-screen FPS/CPU/GPU/battery monitoring — enable it in Container Settings to see real-time performance stats while playing.

# Additional Components & Updates

You can find updated components (known as `wcps`) to improve compatibility and performance, as well as new drivers, at the links below:

  - **Winlator Components (FEXCore, Box64/Box86, DXVK, etc.):**
      - [The412Banner's Nightlies Repository](https://github.com/The412Banner/Nightlies/releases)
  - **Adreno GPU Drivers (Turnip):**
      - [The412Banner's Banners-Turnip Repository](https://github.com/The412Banner/Banners-Turnip)

# Credits and Third-party apps

  - **Original Winlator** by [brunodev85](https://github.com/brunodev85/winlator)
  - **Original Winlator Bionic** by [Pipetto-crypto](https://github.com/Pipetto-crypto/winlator)
  - **Winlator (coffincolors fork)** by [coffincolors](https://github.com/coffincolors/winlator)
  - Ubuntu RootFs (Bionic Beaver): [releases.ubuntu.com/bionic](https://www.google.com/search?q=https://releases.ubuntu.com/bionic)
  - Wine: [winehq.org](https://www.winehq.org/)
  - Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
  - FEX-Emu by [FEX-Emu](https://github.com/FEX-Emu/FEX)
  - PRoot: [proot-me.github.io](https://proot-me.github.io)
  - Mesa (Turnip/Zink/VirGL): [mesa3d.org](https://www.mesa3d.org)
  - DXVK: [github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk)
  - VKD3D: [gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d)
  - D8VK: [github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk)
  - CNC DDraw: [github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw)
[ptitseb](https://github.com/ptitSeb) (Box86/Box64), [Danylo](https://blogs.igalia.com/dpiliaiev/tags/mesa/) (Turnip), [alexvorxx](https://github.com/alexvorxx) (Mods/Tips) and others.








