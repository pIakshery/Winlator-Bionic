

> ⚠️ **License notice:** This repository is distributed under a **custom restricted license** — personal, non-commercial use only. Redistribution, publication, or public forking without prior written permission is prohibited. See [LICENSE](LICENSE) for full terms.
>
> 🚫 **Monetization clause:** Sharing this app or content related to it (including APKs, gameplay footage, or benchmark/test videos) in monetized channels or communities — Telegram, Discord, or similar — that profit from ads, paid subscriptions, or donations is strictly prohibited.

<p align="center">
  <img src="logo.png" alt="Winlator Bionic" width="600">
</p>

# Winlator Bionic

Winlator is an Android application that lets you run Windows (x86\_64) applications with Wine — bringing full-fledged PC gaming and software to your phone or tablet. It supports standard `x86_64` containers powered by Box86/Box64, as well as `Arm64EC` containers running on FEXCore (64/32-bit) or an optional WowBox64 (32-bit).

This build is a fork of **Winlator Bionic** by [Pipetto-crypto](https://github.com/Pipetto-crypto/winlator), fine-tuned for smoother performance, better compatibility, and a cleaner experience out of the box — with an integrated MangoHud overlay for real-time performance monitoring.

# Useful Tips

  - Use Proton (arm64ec) together with FEX for the best performance.
  - Use the **Performance** preset for both **Box64 Preset** and **FEXCore Preset** in Settings for the best experience.
  - If you're using an `Arm64EC` (FEX) container and games like *Control* or *Resident Evil 2 Remake* freeze or hang, go to Settings → **FEXCore Preset** and set it to **Performance**. If it's already set to Performance, create a new custom preset instead, enable the first option (**FEX TSO**), and save — this should stop the freezing.
  - The built-in **MangoHud overlay** shows real-time FPS/CPU/GPU stats and is enabled by default as the main performance overlay.
  - The Adrenotools GPU Drivers section defaults to [The412Banner's Banners-Turnip](https://github.com/The412Banner/Banners-Turnip) repository — all the latest drivers are available right from the app.
  - For .NET Framework apps, install Wine Mono from Start Menu → System Tools.

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








