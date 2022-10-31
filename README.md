# OpenCore_ASUS-PRIME-H410M-D
<p align="left">
    <a href="https://www.apple.com/macos/monterey/">
        <img src="https://img.shields.io/badge/Monterey-12.1-brown"></a>
    <a href="https://www.apple.com/macos/monterey/">
        <img src="https://img.shields.io/badge/Ventura-13.1-brown"></a>
    <a href="https://github.com/dortania/build-repo/releases">
        <img src="https://img.shields.io/badge/OpenCore-0.8.7-blue"/></a>
</p>

<p align="center">
    <a href="">
        <img src="/PIC/AboutMyMac.png" alt="ASUS Prime H410M-D"> </a>
</p>

#### I am not responsible for any damages you may cause.

#### If my work here helped you. Please consider donating, it would mean a lot to me.

- This EFI is configured with Monterey.
- With every EFI update you retrieve from here please remember to go through the post install guide.

> ### Video and Audio

| Feature                              | Status | Dependency          |
| :----------------------------------- | ------ | ------------------- |
| Full Graphics Accleration (QE/CI)    | ✅   | `WhateverGreen.kext`  |
| Audio Recording                      | ✅   | `AppleALC.kext`   |
| Audio Playback                       | ✅   | `AppleALC.kext`   |

> ### Power, Charge, Sleep and Hibernation

| Feature                              | Status |
| :----------------------------------- | ------ |
| iGPU Power Management                | ✅   |
| Sleep/ Hibernation Mode 3            | ✅   |

> ### Input/ Output

| Feature                              | Status |
| :----------------------------------- | ------ |
| Ethernet                             | ✅   |
| USB 2.0, USB 3.0                     | ✅   |

> ### Display, and Keyboard

| Feature                              | Status |
| :----------------------------------- | ------ |
| HDMI Framebuffer Patch               | ✅  |
| External Keyboard                    | ✅  |

> ### macOS Continuity

| Feature                              | Status |
| :----------------------------------- | ------ |
| iCloud, iMessage, FaceTime           | ✅   |
| AirDrop                              | ✅   |
| Time Machine                         | ✅   |

</details>

<details>
<summary><strong> Reference </strong></summary>
<br>

Read these before you start:

- [dortania's Hackintosh guides](https://github.com/dortania).
- [dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/).
- [dortania's OpenCore Post Install Guide](https://dortania.github.io/OpenCore-Post-Install/).
- [dortania/ Getting Started with ACPI](https://dortania.github.io/Getting-Started-With-ACPI/).
- [dortania/ opencore `multiboot`](https://github.com/dortania/OpenCore-Multiboot).
- [dortania/ `USB map` guide](https://dortania.github.io/OpenCore-Post-Install/usb/).
- [WhateverGreen Intel HD Manual](https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.IntelHD.en.md).
- `Configuration.pdf` and `Differences.pdf` in each `OpenCore` releases.

</details>

<details>
<summary><strong> Requiement </strong></summary>
<br>

- A macOS machine(optional): to create the macOS installer.
- Flash drive, 12GB or more, for the above purpose.  
- [IORegistryExplorer](https://developer.apple.com/downloads), for diagnosis.  
- Patience and time, especially if this is your first time Hackintosh-ing.

</details>

<details>
<summary><strong> Hardware </strong></summary>
<br>

| Category  | Asus Prime H410M-D       |
| --------- | ------------------------ |
| CPU       | Intel Core i3-10400      |
| SSD       | TeamGroup MP33 M.2 256GB |
| Display   | 29' IPS UltraWide        |

</details>

<details>
<summary><strong> Getting Started </strong></summary>
<br>

Before you do anything, please familiarize yourself with basic Hackintosh terminologies and the basic Hackintosh process by throughly reading Dortania guides as linked in `REFERENCES`

- Creating a macOS installer: refer to [Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
- [**Read Hardware**](/Other/README_HARDWARE.md): Requirements before installing.
- [**Read Other**](/Other/README_OTHERS.md): for post installation settings and other remarks.

</details>

# Contact Me

- Email: xyzuannihboss@gmail.com
- Telegram: t.me/xyzuan

# Credits

- [Friction](https://t.me/rexr4ven)
- [Apple](https://www.apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for all the kexts/utilities that they made.
- [Rehabman](https://github.com/RehabMan) and [Daliansky](https://github.com/daliansky) for the patches and guides and kexts.
- [Dortania](https://github.com/dortania) for for the OpenCore Install Guide.
