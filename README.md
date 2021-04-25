# Customization Tools For  m$wm



[TOC]

## General Tools

* *Winget** - **Must Have** if you like APT or convenience.

  * Do not install from the App Store. It will not work properly for some reason and you'll be very confused. 
  * [Releases · microsoft/winget-cli (github.com)](https://github.com/microsoft/winget-cli/releases) <---- Use this link instead.
  * Can activate update searching
  * Can activate store integration (idk why you'd want that since there is so much awful there)

* [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab)  - **Must Have** if you use the CLI.

  * Quite customizable
  * Works amazingly with wsl
  * Tabbing
  * Has transparency with an ultra-secret keybind
  * Alt-Shift-D to split
  * Can change background to Anime Waifu (But only in the workplace, remember that.)

  * Quite customizable
  * Works amazingly with wsl
  * Tabbing
  * Has transparency with an ultra-secret keybind
  * Alt-Shift-D to split
  * Can change background to Anime Waifu (But only in the workplace, remember that.)

* **WinaeroTweaker** - Windows Customization Tool
  * Borders for each window
  * Title-bar Reduction
  * Global font settings (breakage)
  * Disabling Annoyances (Cortana, search, Ads, etc)
  * Disabling Aero Shake
  * Enable old Windows Sound Mixer and Photo Viewer
  * Most anything else that Explorer is capable of. (With a slight amount of breakage)
* **Powertoys** - Many Various Useful Tools
  * Hotkeys
  * Runner (very featureful, but kinda eh)
  * Other quasi-useful utilities

* [Files‎ ](https://www.microsoft.com/en-us/p/files/9nghp3dx8hdx?activetab=pivot:overviewtab)Terribly named but fantastic File Manager (Although in their defense 'Dolphin' and 'Thunar' suffer the same fate... And p much all Linux file managers now that I think about it. Nautilus? PCMANFM-QT? Really?)
  * You must enable split layout
  * No dark mode? My eyes tho. OwO
  * Can be laggy, but has toggle features for performance.

* **AltDrag** - Linux-like dragging and Transparency in Windows
  * Amazing lil widget.
  * Allows you to drag windows with Alt or Meta
  * Allows you to modify any window's transparency with mousewheel

## Tiling Options

#### **Powertoys**

**Pros:**

* Easy to setup initially
* Easy to configure

**Cons:**

​	Made by Microsoft

​	Fancy-Zones is the worst name ever. This isn't Mary Poppins ffs.

#### **Workspacer**

* Works extraordinarily well once configured.
* Hard to use, lacking features. (cannot change mod key zzzzzz)
* **Need** to understand basic C# to customize.
* Has to compile each time, so can be annoying to troubleshoot.
* Made for power-users
* No useless gaps (Should have them soon tho!)
* Will die if you don't set exceptions for resolution changes. or certain applications (Mr. Virtualbox)

**Note: **

​			**Any other TILING alternative is either buried in the deepweb, or a meme.**

#### **DPI Scaling**

If you're needing to use **scaling**, Both Powertoys and Workspacer do not play well with it. (With multi-monitors or different resolution monitors.) I recommend using font-scaling, as I'm using in my video. It works well enough, and does tend to be less-glitchy than dpi scaling imo. It's a hidden option under 'Ease of Access'. 

## Other Comfy Software

#### **Text**

- Typora - Markdown Editor
- Zim - Desktop Wiki
- Vscode - Best text editor available. Sorry.
- Draw.io - Web based graphic software. 10/10 Useful

#### **Tools**

* Process Explorer - Task-manager made by Microsoft that sends process IDs/Hashes to Virustotal. Far more useful than the stock one.
* Autologin - Microsoft Tool to automatically log you in. Actually safer in many cases than having a login. Esp with that stupid Windows Hello 4 digit pin.
* Windirstat - The infamous filesystem visualizer. Very useful when you're battling Windows Directories
* GWSL - Xserver on Windows but actually easy. 
* Victor Mono - **Based** Font

## Quick Winget Installs

``` powershell
// This is what I run everytime that I format.

winget install powertoys
winget install Microsoft.VisualStudioCode.User-x64
winget install terminal
winget install git
winget install zim
winget install typora
winget install python
winget install wsl2
winget install virtualbox
winget install debian
winget install docker
winget install gwsl
// winget install discord
// winget install musescore
// winget install obs
// winget install neovim (Does this work without modification?)
```



## Future Additions

- [ ]  Add all relevant links and label MStore or Github
- [ ] Add warning about WinAeroTweaker and... what else was it?
- [ ] Consider doing a long video showing setup. 
- [ ] Remove jokes from markdown.
- [ ] Add all the Winget commands you have
- [ ] Add an easy script to install Doom Emacs in WSL.
  - [ ] wget from main src, compile, set up dir, weren't there path issues?
- [ ] Figure out formatting issues
