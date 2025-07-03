# Table of Contents

- [Important Info](#important-info)
	- [Disclaimer](#disclaimer)
	- [Download Instructions](#download-instructions)
	- [Requirements](#requirements)
	- [Other](#other)

- [Voly](#voly)
	- [Terminology](#terminology)
	- [Features](#features)

- [Potential Additions](#potential-additions)

- [Special Thanks](#special-thanks)

- [Credits](#credits)
	- [Used Packages](#used-packages)
	

<br/>


# Important Info

## Disclaimer

Voly does **not** currently have a **Code Signing Certificate** yet! If you do not trust Voly, please feel free to reach out at [volyapp1@gmail.com](mailto:volyapp1@gmail.com).

## Download Instructions

- **Portable**: Download the "**VolyApp-win-Portable.zip**" file and extract it anywhere
- **Installer**: Download and run the "**VolyApp-win-Setup.exe**" file, this will place Voly into the "..\AppData\Local\" folder

[Go to the latest release!](https://github.com/BattleFrog99/Voly-Releases/releases)

## Requirements

Windows, version 10.0.17763.0 or higher

## Other

Please utilize the [Issues](https://github.com/BattleFrog99/Voly-Releases/issues) tab for bug reports, or email [volyapp1@gmail.com](mailto:volyapp1@gmail.com) for help and support.

This application is proprietary software. Redistribution is permitted without prior permission, provided that proper attribution is given to the original author. See [LICENSE](LICENSE.txt) for full terms.

I'm currently looking for a new job, so if this application peaks your interest, please view my [Portfolio](https://evan-goddard.github.io/eg-portfolio/) and get in contact with me for any opportunities, thanks!

_Buy me a coffee and help support future development of Voly here: [https://paypal.me/EvanGoddardVoly](https://paypal.me/EvanGoddardVoly)_

<br/>


# Voly

Voly allows the user to easily control the Windows Volume Mixer and gives seamless control to the volume of any application, output device, and input device. Voly is a Windows desktop application created using Windows Presentation Foundation (WPF) and [Prism](https://github.com/PrismLibrary/Prism).

![Initial_Gif](https://github.com/BattleFrog99/Voly-Releases/blob/main/Readme%20Resources/initial.gif)

## Terminology
- **Volume Manager**: The container for Volume Editors

- **Volume Editor**: The control used for changing volumes

- **Audio Objects**: Anything that can be dragged onto a Volume Editor and be edited by Voly
	- _Examples: Applications, Output Devices, Input Devices, Custom Voly Audio Objects_

- **Active Border**: Surrounds the 'active' Volume Editors, these active Volume Editors determine which Audio Object will be edited by hotkeys
	- _When applicable, hotkeys have a field to denote which of the Volume Editors in the active border will be edited by the hotkey_

## Features

- **Audio Control**
	- Seamlessly change the volume levels of any application, output device, and input device
	- Custom Voly Audio Objects
		- **Audio Groups**: link together volumes of audio objects
		- **Fullscreen Application(s)**: control the volume of any fullscreen application

- **Hotkeys**
	- Customizable system-wide hotkeys, this means that hotkeys can be used even when the application is minimized

- **Auto Updating**
	- New versions of Voly can be automatically downloaded and installed

- **User Color Schemes**
	- The colors within Voly are fully customizable and can be edited without having to close and reopen the application

<br/>


# Potential Additions

Suggest new ideas on the [Discussion](https://github.com/BattleFrog99/Voly-Releases/discussions) tab of this repo!

- Allowing user to replace audio object icons with custom images
- Create animations on button icons when hovering

<br/>


# Special Thanks

- [MajorGeeks.com](https://www.majorgeeks.com/): Thank you so much for creating a [page for Voly](https://www.majorgeeks.com/files/details/voly.html)! They did an amazing job describing the app, go check them out!


# Credits

**Author**: Evan Goddard

## Used Packages
- [NAudio](https://github.com/naudio/NAudio): Handles audio functionality in Windows
- [Velopack](https://velopack.io/): Handles auto updating of application
- [PixiEditor.ColorPicker](https://github.com/PixiEditor/ColorPicker): Used in App Colors settings
- [Prism](https://github.com/PrismLibrary/Prism): Framework for WPF