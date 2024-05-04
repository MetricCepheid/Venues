<p align="center">
    <i>YARG (a.k.a. Yet Another Rhythm Game)</i>
</p>

<p align="center">
  <a href="https://twitter.com/YARGGame">
    <img src="./Images/Socials/Twitter.png" width="38px" height="38px" alt="Twitter">
  </a>
  <a href="https://discord.gg/sqpu4R552r">
    <img src="./Images/Socials/Discord.png" height="38px" width="38px" alt="Discord">
  </a>
  <a href="https://reddit.com/r/yarg">
    <img src="./Images/Socials/Reddit.png" height="38px" width="38px" alt="Discord">
  </a>
</p>

---

YARG (a.k.a. Yet Another Rhythm Game) is a free, open-source, plastic guitar game that is still in development. It supports guitar (five fret), drums (plastic or e-kit), vocals, pro-guitar, and more! YARG is still in active development, so there may be bugs and missing features.

## 👉 Disclaimer

> [!IMPORTANT]
> **YARG stands firmly against all forms of piracy.** We neither support nor endorse piracy, as it is a violation of copyright law with serious legal consequences. Our platform's importable content—designed for creators to share their work and for educational purposes—does not justify or excuse piracy.
>
> YARG itself **does not** use any ripped/pirated assets or music and never will. By using YARG, users agree not to promote or endorse piracy in any way through our platform. Upholding these principles ensures a community that respects copyright, creativity, and legal standards.
>
> YARG stands for "Yet Another Rhythm Game" and NOT for pirates.

## 📃 Table of Contents

- [📃 Table of Contents](#-table-of-contents)
- [✍️ Contributing](#️-contributing)
- [🛡️ License](#️-license)
- [🧰 External Licenses](#-external-licenses)
- [📦 External Assets and Libraries](#-external-assets-and-libraries)

## ✍️ Contributing

1. Instead of cloning this repository, pull YARG's repository
   - [Link Here](https://github.com/YARC-Official/YARG)
2. After pulling YARG's repository, you want to open the **".gitmodules"** file that's in the root folder.
3. If you pulled YARG's repository correctly, in the **".gitmodules"** file you should see the following
```
[submodule "Assets/Plugins/YARG.Core"]
	path = YARG.Core
	url = https://github.com/YARC-Official/YARG.Core
```
4. You will want to add the following directly under, as such
```
[submodule "Assets/Authoring/Venue"]
	path = Venue
	url = https://github.com/Roystermeat/Venues
```
5. Then, in a terminal run **git submodule update**
6. The venues folder should now be updated with the files from this repository.

## 🛡️ License

YARG is licensed under the [GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html) (or later) - see the [`LICENSE`](LICENSE) file for details.

## 🧰 External Licenses

Some libraries/assets are **packaged** with the source code have licenses that must be included.

Please note that other libraries are **not** directly packaged within the source code, and are to be installed by NuGet, Unity's packaged manager, or via a Git submodule.

## 📦 External Assets and Libraries

These are assets that are installed by NuGet, Unity's packaged manager, or via a Git submodule. These have varying licenses, but can all be downloaded/accessed by the links given.

| Link | Type | Use |
| --- | --- | --- |
| [YARG.Core](https://github.com/YARC-Official/YARG.Core) | Library | Provides most of YARG's backend (engine, replays, etc.)
| [PlasticBand](https://github.com/TheNathannator/PlasticBand) | Reference | Controller Support Info
| [GuitarGame_ChartFormats](https://github.com/TheNathannator/GuitarGame_ChartFormats) | Reference | File Format Documentation
| [PlasticBand-Unity](https://github.com/TheNathannator/PlasticBand-Unity) | Library | GH/RB Controller Support
| [HIDrogen](https://github.com/TheNathannator/HIDrogen) | Library | Linux HID Controller Support
| [EasySharpIni](https://www.nuget.org/packages/EasySharpIni/) | Library | Parsing `song.ini` Files
| [DryWetMidi](https://www.nuget.org/packages/Melanchall.DryWetMidi) | Library | Parsing `.mid` Files
| [Minis](https://github.com/keijiro/Minis/tree/master) | Library | MIDI Input for Unity
| [DOTween](https://github.com/Demigiant/dotween) | Library | Animation Utility
| [UniTask](https://github.com/Cysharp/UniTask) | Library | Async Library
| [unity-toolbar-extender](https://github.com/marijnz/unity-toolbar-extender/) | Library | Unity Editor Utility
| [SoftMaskForUGUI](https://github.com/mob-sakai/SoftMaskForUGUI) | Library | UI Utility
| [Unity-Dependencies-Hunter](https://github.com/AlexeyPerov/Unity-Dependencies-Hunter) | Library | Unity Editor Utility
| [tmpro-dynamic-data-cleaner](https://github.com/STARasGAMES/tmpro-dynamic-data-cleaner) | Library | Prevent Git Change Spam
