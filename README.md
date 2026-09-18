

> ⚠️ **License notice:** This repository is distributed under a **custom restricted license** — personal, non-commercial use only. Redistribution, publication, or public forking without prior written permission is prohibited. See [LICENSE](LICENSE) for full terms.
>
> 🚫 **Monetization clause:** Sharing this app or content related to it (including APKs, gameplay footage, or benchmark/test videos) in monetized channels or communities — Telegram, Discord, or similar — that profit from ads, paid subscriptions, or donations tied to access to this Software is strictly prohibited.

<p align="center">
  <img src="logo.png" alt="Winlator Bionic" width="600">
</p>

# Winlator Bionic

Winlator is an Android application that lets you run Windows (x86\_64) applications with Wine — bringing full-fledged PC gaming and software to your phone or tablet. It supports standard `x86_64` containers powered by Box86/Box64, as well as `Arm64EC` containers running on FEXCore (64/32-bit) or an optional WowBox64 (32-bit).

This build is a fork of **Winlator Bionic** by [Pipetto-crypto](https://github.com/Pipetto-crypto/winlator), fine-tuned for smoother performance, better compatibility, and a cleaner experience out of the box — with an integrated MangoHud overlay for real-time performance monitoring.

<p align="center">
  <img src="collage.png" alt="Winlator Bionic Screenshots" width="800">
</p>

Development on this fork is ongoing and driven by real gameplay testing rather than just code changes — every tweak to FEX, Box64, or the graphics stack is validated against actual titles before it ships. The goal isn't just to add features, but to keep the app stable, fast, and predictable release after release.

# Useful Tips

  - If you're using an `x86_64` container and running into performance issues, try switching the Box86/Box64 preset to **Performance** in Container Settings → Advanced.
  - If you're using an `Arm64EC` container, try the latest FEXCore version in the container settings for better compatibility or performance.
  - For .NET Framework apps, install Wine Mono from Start Menu → System Tools.
  - The built-in **MangoHud overlay** shows real-time FPS/CPU/GPU/battery stats — enable it in Container Settings.

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








