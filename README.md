<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107158826-6ef0d600-6941-11eb-83be-3e3f4461a56d.png">
  <br />
  Fedora Guide
</h1>

#### A guide on setting up your Fedora Desktop with all the essential Applications, Tools, and Games to make your experience with Fedora great!

# Table of Contents

1. [Getting Started](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#getting-started)

2. [Getting Software](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#getting-software)

3. [Gaming](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#gaming)

4. [Setting up a macOS workspace](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#setting-up-a-macos-workspace)

5. [Setting up a Windows 10 workspace](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#setting-up-a-windows-10-workspace)

6. [GNOME Extensions](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#gnome-extensions)

7. [Advanced Topics](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#advanced-topics)


# Getting Started

[Fedora](https://getfedora.org/) is a polished, easy to use operating system for laptop & desktop computers, with a complete set of tools for developers and makers of all kinds. The Fedora OS base is used to build/develop new versions of [Red Hat® Enterprise Linux® (RHEL)](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux) the world's leading enterprise Linux platform. The OS serves as the foundation for which you can scale existing apps and roll out emerging technologies across bare-metal, virtual, container, and all types of cloud environments.

[Fedora Silverblue](https://silverblue.fedoraproject.org/) is a variant of the Fedora Workstation that uses rpm-ostree to provide an immutable OS image with reliable updates and easy rollbacks.

[Fedora CoreOS](https://getfedora.org/coreos?stream=stable) is an automatically-updating, minimal operating system for running containerized workloads securely and at scale.

[Fedora Spins](https://spins.fedoraproject.org/) is for those that prefer an alternative desktop environment such as KDE Plasma Desktop, MATE; or Xfce, you can download a spin for your preferred desktop environment and use that to install Fedora, pre-configured for the desktop environment of your choice.

[CentOS Stream](https://www.centos.org/centos-stream/) is a continuously delivered distro(uses the Fedora OS base) that tracks just ahead of Red Hat Enterprise Linux (RHEL) development, positioned as a midstream between Fedora Linux and RHEL.

[Anaconda](http://fedoraproject.org/wiki/Anaconda) is an OS installer used by Fedora, Red Hat Enterprise Linux (RHEL), CentOS Stream and other Linux distributions.

[Fedora Media Writer](https://fedoramagazine.org/make-fedora-usb-stick/) is a tool in Fedora that will set up your flash drive to run a "Live" version of Fedora Workstation, meaning that you can boot it from your flash drive and try it out right away without making any permanent changes to your computer.

[Using Fedora with Microsoft’s WSL2](https://fedoramagazine.org/wsl-fedora-33/)

[Fedora Project Wiki](http://fedoraproject.org/wiki/Fedora_Project_Wiki)

[Fedora Developer Portal](https://developer.fedoraproject.org/start.html)

[Fedora Project Forum](https://discussion.fedoraproject.org/)

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.


 <h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107158827-70220300-6941-11eb-917b-dbdb7142a13b.png">
  <br />
  Fedora Desktop
</h1>
 
 ## Fedora, Red Hat Enterprise Linux (RHEL) and CentOS Stream Development Cycle
 
 <img src="https://user-images.githubusercontent.com/45159366/107158836-7ca65b80-6941-11eb-95dd-5166023597a7.png">


## GNOME Tweaks

Open the terminal and run: 
```sh
sudo dnf install gnome-tweak-tool //let's you customize your desktop layout.
```

## Setting up Pop Shell

[Pop Shell](https://github.com/pop-os/shell) is a keyboard-driven layer for GNOME Shell which allows for quick and sensible navigation and management of windows. The core feature of Pop Shell is the addition of advanced tiling window management similar to i3wm.

```sh
sudo dnf install gnome-shell-extension-pop-shell
```

## Enable Firewall

[Using firewalld](https://docs.fedoraproject.org/en-US/quick-docs/firewalld/)

Open the terminal and run: 
```sh
//Checks firewall status
sudo firewall-cmd --state
sudo systemctl status firewalld
```
# Getting Software

[Back to the Top](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#table-of-contents)

## GNOME Software Center

<img src="https://user-images.githubusercontent.com/45159366/107158830-71ebc680-6941-11eb-893f-be3ad3e1c830.png">

**Note 1: All this software is also available in other popular Linux distributions such as [Debian](https://www.debian.org/), [Linux Mint](https://linuxmint.com/), [elementary OS](https://elementary.io/), [Fedora](https://getfedora.org), [Manjaro Linux](https://manjaro.org/), [EndeavourOS](https://endeavouros.com/) and [Arch Linux](https://archlinux.org/).**

**Note 2: For new users not comfortable with using the command-line or need software not available in the Software Center checkout the Essential Apps section to get started. Also, if you scroll down further you'll see other easy ways to get software applications through Flathub, Snap Store, and AppImages.**

## Essential Apps(depending on your workflow)

[Google Chrome browser](https://www.google.com/chrome/)

[Microsoft Edge browser](https://www.microsoftedgeinsider.com/en-us/download/?platform=linux)

[Visual Studio Code](https://code.visualstudio.com/Download)

[Microsoft Teams](https://www.microsoft.com/en-us/microsoft-teams/download-app)

[Microsoft 365 with Office apps(formerly Office Online)](https://www.microsoft.com/en-us/microsoft-365/free-office-online-for-the-web)

[Google Workspace (formerly G Suite)](https://workspace.google.com/)

[Zoom](https://zoom.us/download?os=linux)

[Jitsi Meet](https://jitsi.org/jitsi-meet/) is a fully encrypted, 100% open source video conferencing solution.

[Cisco Webex Web App](https://help.webex.com/en-us/n1pxgbz/Cisco-Webex-Web-App) is the web based version of Cisco Webex video conferencing solution. 

[Slack](https://slack.com/downloads/linux)

[Trello](https://trello.com/platforms)

[Skype](https://www.skype.com/en/get-skype/)

[Discord](https://discord.com/download)

[TeamViewer](https://www.teamviewer.com/en/download/linux/)

[Spotify](https://www.spotify.com/us/download/linux/)

[Apple Music(Web)](https://music.apple.com/) is the web app version of Apple Music that runs in Safari, Google Chrome and Mozilla Firefox.

[Adobe Lighroom Online photo editor](https://lightroom.adobe.com) is an online web version of Adobe Photoshop Lightroom. Adobe account required to sign-in to app.

[Adobe Spark(Web)](https://spark.adobe.com) is an application that let's you make cool Social Graphics, Short Videos, and Web Pages. Adobe account required to sign-in to app.

[Photopea](https://www.photopea.com/) is an advanced online image editor supporting PSD, XCF, Sketch, XD and CDR formats. (Adobe Photoshop, GIMP, Sketch App, Adobe XD, CorelDRAW).

[Master PDF Editor](https://code-industry.net/masterpdfeditor/) is straightforward, easy to use application for working with PDF documents equipped with powerful multi-purpose functionality. With Master PDF Editor you can easily view, create and modify PDF documents. 

[VMware Workstation Player](https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html) is an ideal utility for running a single virtual machine on a Windows or Linux PC. Organizations use Workstation Player to deliver managed corporate desktops, while students and educators use it for learning and training.

[VMware Workstation Pro](https://www.vmware.com/products/workstation-pro.html) is the industry standard for running multiple operating systems as virtual machines (VMs) on a single Linux or Windows PC. IT professionals, developers and businesses who build, test or demo software for any device, platform or cloud rely on Workstation Pro.

[CrossOver Linux®](https://www.codeweavers.com/crossover) is a Microsoft Windows compatibility layer(based on [WINE(Wine Is Not an Emulator)](https://www.winehq.org)). The CrossOver compatibility layer enables thousands of Windows-based applications to run on Linux, macOS, or Chrome OS.

[WinApps for Linux](https://github.com/Fmstrat/winapps) is a program that runs Windows apps such as Microsoft Office & Adobe in Linux (Ubuntu/Fedora) and GNOME/KDE as if they were a part of the native OS, including Nautilus integration for right clicking on files of specific mime types to open them.

[DaVinci Resolve video editor](https://www.blackmagicdesign.com/products/davinciresolve/) is complete video editing solution that combines professional 8K editing, color correction, visual effects and audio post production all in one software tool.

[Reaper Audio editor](https://www.reaper.fm/download.php) is a complete digital audio production application for computers, offering a full multitrack audio and MIDI recording, editing, processing, mixing and mastering toolset.

[Flameshot](https://flameshot.org/) is a powerful yet simple to use screenshot software.

[Timeshift](https://github.com/linuxmint/timeshift) for Linux is an application that provides functionality similar to the System Restore feature in Windows and the Time Machine tool in Mac OS. Timeshift protects your system by taking incremental snapshots of the file system at regular intervals. These snapshots can be restored at a later date to undo all changes to the system.

[Stacer](https://github.com/oguzhaninan/Stacer) is an open source system optimizer and application monitor that helps users to manage their entire system. Also available as an AppImage.

[Nativefier](https://github.com/nativefier/nativefier) is a command-line tool to easily create a desktop app for any web site with minimal configuration. Apps are wrapped by [Electron](https://www.electronjs.org/) (which uses Chromium under the hood) in an OS executable (.app, .exe, etc) for use on Windows, macOS and Linux.


## App Outlet

[App Outlet](https://app-outlet.github.io/) is a Universal application store(Flatpaks, Snaps, and AppImages) inspired by the Linux App Store online service.

 <img src="https://user-images.githubusercontent.com/45159366/106686354-0095c780-657f-11eb-892b-659d3252d6e7.png">
 
 ## Flatpaks

[FlatHub](https://flathub.org/) is a build and distribution service for Flatpak applications.

[FlatHub Forum](https://discourse.flathub.org/)

 <img src="https://user-images.githubusercontent.com/45159366/106686365-055a7b80-657f-11eb-9b58-1de28abe2e5b.png">
 
 ## Snaps

[Installing snap on Fedora](https://snapcraft.io/docs/installing-snap-on-fedora)

[Snap Store](https://snapcraft.io/store) is a build and distribution service for Snap applications.

[Snapcraft Forum](https://forum.snapcraft.io/)

 <img src="https://user-images.githubusercontent.com/45159366/106686375-08ee0280-657f-11eb-9918-5385d8c09148.png">
 <img src="https://user-images.githubusercontent.com/45159366/106686378-0a1f2f80-657f-11eb-83aa-37ac96c7b032.png">

 
## AppImages

[AppImageHub](https://www.appimagehub.com) is a build and distribution service for AppImage applications.

[AppImage Manager](https://github.com/AppImageCrafters/appimage-manager) is a package manager for AppImages.

[AppImage Forum](https://discourse.appimage.org/)

 <img src="https://user-images.githubusercontent.com/45159366/106686382-0b505c80-657f-11eb-9d74-9a94ec0d0693.png">

# Gaming

[Back to the Top](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#table-of-contents)

## Game Streaming

[Geforce NOW](https://www.nvidia.com/en-us/geforce-now/download/) use the **Chromebook version** to play all your games in Google Chrome or any Chromium-based web browser such as Brave, Vivaldi, and Microsoft Edge. Also, available as a Electron Desktop App in the [Snap store Geforce NOW](https://snapcraft.io/geforcenow).
 <img src="https://user-images.githubusercontent.com/45159366/106686391-0f7c7a00-657f-11eb-9d0b-1ebb4d385883.jpeg">

[Moonlight Game Streaming](https://moonlight-stream.org/) is a program that let you stream from your PC games over the Internet with no configuration required. Stream from almost any device, whether you're in another room or miles away from your gaming rig. 
<img src="https://user-images.githubusercontent.com/45159366/106686398-11463d80-657f-11eb-841a-d534829ccc3d.png">

[Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki) is a Free and Open Source Software Client for PlayStation 4 and PlayStation 5 Remote Play for Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch and potentially even more platforms.

 
## Graphics Performance
 
[GreenWithEnvy (GWE)](https://gitlab.com/leinardi/gwe) is a GTK system utility designed by Roberto Leinardi to provide information, control the fans and overclock your NVIDIA video card for better performance. Available in the Pop Shop as a Flatpak.
 <img src="https://user-images.githubusercontent.com/45159366/107091994-89974380-67b7-11eb-85ed-eedec7e3dfbf.png">
 
 [CoreCtrl](https://gitlab.com/corectrl/corectrl) is a free and open source Linux application that allows you to control your computer hardware with ease using application profiles for native and Windows applications, has basic CPU controls and full AMD GPUs controls (for both old and new models). 
 
 ```sh
sudo dnf install corectrl
```
<img src="https://user-images.githubusercontent.com/45159366/107092000-8b610700-67b7-11eb-86f7-6fcb3d017cd0.png">


## Performance Benchmarks

[Geekbench 5](https://www.geekbench.com/download/) is a cross-platform benchmark that measures your system's performance with the press of a button.

[UNIGINE Superposition](https://benchmark.unigine.com/superposition) is an extreme performance and stability test for PC hardware: video card, power supply, cooling system.

<img src="https://user-images.githubusercontent.com/45159366/107092007-8f8d2480-67b7-11eb-9c3f-a0cb02e6dfcd.png">


## Steam

[Get Steam](https://store.steampowered.com/about/)

**OR**

 ```sh
sudo dnf install steam
```

[Proton](https://github.com/ValveSoftware/Proton/) is a tool for use with the Steam client which allows games which are exclusive to Windows to run on the Linux operating system. It uses Wine to facilitate this.

## Enable Proton in Steam

 - Click on “Steam” then “Settings” to open the Settings window at the far-left corner.
 - On the “Settings” window, click on “Steam Play.” Ensure you check the “Enable Steam Play for supported files” and “Enable Steam Play for   all other titles” checkboxes. Lastly, select the Proton version you wish to use from the drop-down menu.

 <img src="https://user-images.githubusercontent.com/45159366/106686402-13100100-657f-11eb-9012-6bdac264a808.png">

## Lutris

[Lutris](https://lutris.net)is a gaming client for Linux. It gives you access to all your video games with the exception of the current console generation. Also, integrates nicely with other stores like GOG, Steam, Battle.net, Origin, Uplay and many other sources that allow you to import your existing game library and community maintained install scripts give you a completely automated setup.

[Add Epic Games Store](https://lutris.net/games/epic-games-store/)

 <img src="https://user-images.githubusercontent.com/45159366/106686406-14412e00-657f-11eb-97c4-c80c6e25a374.png">
 
 ## GameHub

[GameHub](https://github.com/tkashkin/GameHub) is a unified library for all your games. It allows you to store your games from different platforms into one program to make it easier for you to manage your games.

<img src="https://user-images.githubusercontent.com/45159366/107862734-96451880-6e03-11eb-9b92-9d355b890083.png">

**GameHub supports:**

 - native games for Linux
 - **multiple compatibility layers:**
   - Wine
   - Proton
   - [DOSBox](https://www.dosbox.com/)
   - [RetroArch](https://store.steampowered.com/app/1118310/RetroArch/)
   - [ScummVM](https://www.scummvm.org/)
   - [WineWrap](https://www.gog.com/forum/general/adamhms_linux_wine_wrappers_news_faq_discussion/post1) — a set of preconfigured wrappers for [supported games](https://www.gog.com/forum/general/adamhms_linux_wine_wrappers_news_faq_discussion/post3);
   - custom emulators

 - **multiple game platforms:**
   - [Steam](https://store.steampowered.com/)
   - [GOG](https://www.gog.com/)
   - [Humble Bundle (including Humble Trove)](https://www.humblebundle.com/)
   - [itch.io](https://itch.io/)
 
## Wine

[WINE(Wine Is Not an Emulator)](https://www.winehq.org) is a compatibility layer capable of running Windows applications on several POSIX-compliant operating systems, such as Linux, macOS, & BSD. Instead of simulating internal Windows logic like a virtual machine or emulator, Wine translates Windows API calls into POSIX calls on-the-fly, eliminating the performance and memory penalties of other methods and allowing you to cleanly integrate Windows applications into your desktop.

## Winetricks

[Winetricks](https://github.com/Winetricks/winetricks) is an easy way to work around problems in Wine.

this is needed to avoid adobeair error
```sh
sudo sed -i 's|echo "\${arg%%=\*}"=\\""${arg### \*=}"\\"|echo \${arg%%=\*}=\\"\${arg### \*=}\\"|g' /usr/local/bin/winetricks
sudo dnf install cabextract libncurses5:armhf
```
# Setting up a MacOS workspace

[Back to the Top](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#table-of-contents)

**REQUIREMENTS**

   - A modern Linux distribution
   - QEMU > 2.11.1
   - A CPU with Intel VT-x / AMD SVM support is required
   - A CPU with SSE4.1 support is required for >= macOS Sierra
   - A CPU with AVX2 support is required for >= macOS Mojave
   - Internet access for the installation process

Open the terminal and run:
```sh 
sudo dnf install qemu uml-utilities virt-manager dmg2img git wget libguestfs-tools p7zip
```

[Sosumi](https://snapcraft.io/install/sosumi/fedora) is a app that let's you download and install macOS in a VM. App is based on [macOS-Simple-KVM](https://github.com/foxlet/macOS-Simple-KVM).
 <img src="https://user-images.githubusercontent.com/45159366/107092234-0fb38a00-67b8-11eb-9f30-f4d16545624b.png">

[OpenCore for macOS](https://dortania.github.io/OpenCore-Install-Guide/)

 <img src="https://user-images.githubusercontent.com/45159366/107092246-15a96b00-67b8-11eb-91fb-27494c7f1d4f.jpg">
 
# Setting up a Windows 10 workspace

 [Back to the Top](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#table-of-contents)
 
**REQUIREMENTS**

   - A modern Linux distribution
   - QEMU > 2.11.1
   - A CPU with Intel VT-x / AMD SVM support is required
   - [WindowsGuestDrivers/Download Drivers - KVM](https://www.linux-kvm.org/page/WindowsGuestDrivers/Download_Drivers)
   - Internet access for the installation process

Open the terminal and run:
```sh 
sudo dnf install qemu uml-utilities virt-manager gnome-boxes
```

[GNOME Boxes](https://wiki.gnome.org/Apps/Boxes) is an application that gives you access to virtual machines, running locally or remotely. It also allows you to connect to the display of a remote computer.

 <img src="https://user-images.githubusercontent.com/45159366/107092256-1cd07900-67b8-11eb-9ae9-f389045dad26.png">
 <img src="https://user-images.githubusercontent.com/45159366/107093639-72a62080-67ba-11eb-8d88-477929a5516b.png">
 
 [OpenCore for Windows 10](https://dortania.github.io/OpenCore-Install-Guide/)
 
 <img src="https://user-images.githubusercontent.com/45159366/107092270-222dc380-67b8-11eb-82cc-d41e9e8a39e0.png">

# GNOME Extensions

[Back to the Top](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#table-of-contents)

**Note: GNOME Extenions allow you customize your Desktop layout anyway you want.**

**Easily turn GNOME Extensions On/Off using the [GNOME Shell integration](https://addons.mozilla.org/en-US/firefox/addon/gnome-shell-integration/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) add-on in the Firefox web browser.**

[Caffeine](https://extensions.gnome.org/extension/517/caffeine/) is a GNOME Shell extension that disables the screensaver and auto suspend

[Arc Menu](https://extensions.gnome.org/extension/3628/arcmenu/) is a GNOME Shell extension that adds an Application Menu for GNOME.

[Material Shell](https://extensions.gnome.org/extension/3357/material-shell/) is a GNOME Shell extension that adds a modern desktop interface for Linux - packaged as an extension for GNOME Shell. Improve your user experience and get rid of the anarchy of traditional desktop workflows. Designed to simplify navigation and reduce the need to manipulate windows in order to improve productivity. It's meant to be 100% predictable and bring the benefits of tools coveted by professionals to everyone.

[Clipboard Indicator](https://extensions.gnome.org/extension/779/clipboard-indicator/) is a GNOME Shell extension that adds a clipboard indicator to the top panel, and caches clipboard history.

[Blur My Shell](https://extensions.gnome.org/extension/3193/blur-my-shell/) is a GNOME Shell extension that adds a blur look to different parts of the GNOME Shell, including the top panel, dash and overview.

[GSConnect](https://extensions.gnome.org/extension/1319/gsconnect/) is a GNOME Shell extension that adds a complete implementation of KDE Connect especially for GNOME Shell with Nautilus, Chrome and Firefox integration. It does not rely on the KDE Connect desktop application and will not work with it installed.

[Compiz alike windows effect](https://extensions.gnome.org/extension/2950/compiz-alike-windows-effect/) is a GNOME Shell extension that adds wobbly windows effect inspired by the Compiz one

[CPU Power Manager](https://extensions.gnome.org/extension/945/cpu-power-manager/) is a GNOME Shell extension that enables you to manage Intel_pstate CPU Frequency scaling driver.

[CPU Power Governor](https://extensions.gnome.org/extension/3727/cpu-power-governor/) is a GNOME Shell extension that enables the ability to swap between kernel governors for the CPU useful for laptops.

[CPUFreq](https://extensions.gnome.org/extension/1082/cpufreq/) is a GNOME Shell extension for System Monitor and Power Manager.

[Dash to Panel](https://extensions.gnome.org/extension/1160/dash-to-panel/) is a GNOME Shell extension that shows an icon taskbar for the Gnome Shell. This extension moves the dash into the gnome main panel so that the application launchers and system tray are combined into a single panel, similar to that found in KDE Plasma and Windows 7+. A separate dock is no longer needed for easy access to running and favorited applications.

[Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock/) is a GNOME Shell extension that shows a dock for the Gnome Shell. This extension moves the dash out of the overview transforming it in a dock for an easier launching of applications and a faster switching between windows and desktops. Side and bottom placement options are available.

[Removable Drive Menu](https://extensions.gnome.org/extension/7/removable-drive-menu/) is a GNOME Shell extension that shows a status menu for accessing and unmounting removable devices.

[Snap Manager](https://extensions.gnome.org/extension/3715/snap-manager/) is a GNOME Shell extension that shows a popup menu in the top bar to easily manage snap tasks (list, changes, refresh, remove, install...). Update notification at session startup.

[Sound Input & Output Device Chooser](https://extensions.gnome.org/extension/906/sound-output-device-chooser/) is a GNOME Shell extension that shows a list of sound output and input devices (similar to gnome sound settings) in the status menu below the volume slider. Various active ports like HDMI , Speakers etc. of the same device are also displayed for selection. V20+ needs python as dependency. If you want to continue with the old method without Python, use options to switch off New Port identification. But it works with only English

[User Themes](https://extensions.gnome.org/extension/19/user-themes/) is a GNOME Shell extension that lets you load shell themes from user directory.

[WinTile: Windows 10 window tiling for GNOME](https://extensions.gnome.org/extension/1723/wintile-windows-10-window-tiling-for-gnome/)  is a hotkey driven window tiling system for GNOME that imitates the standard Win-Arrow keys of Windows 10, allowing you to maximize, maximize to sides, or 1/4 sized to corner across a single or multiple monitors using just Super+Arrow.

[Gnome Extensions Sync](https://extensions.gnome.org/extension/1486/extensions-sync/) is a GNOME Shell extension that syncs gnome shell keybindings, tweaks settings and extensions with their configuration across all gnome installations.

[Tray Icons: Reloaded](https://extensions.gnome.org/extension/2890/tray-icons-reloaded/) is a GNOME Shell extension which bring back Tray Icons to top panel, with additional features.

[GitLab extension](https://extensions.gnome.org/extension/3535/gitlab-extension/) is a GNOME Shell extension that lets you utilizes the official GitLab API to provide a comfortable overview about your projects, commits & pipelines.

## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Fedora-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Fedora-Guide/blob/main/README.md#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
