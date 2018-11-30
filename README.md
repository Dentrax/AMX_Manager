<h1 align="center">AMX_Manager for GNU/Linux Public Source Repository</h1>

**Improve your GNU/Linux productivity with life-saver Shell scripts**

[What It Is](#what-it-is)

[How To Use](#how-to-use)

[Modules](#modules)

[Requirements](#requirements)

[Dependencies](#dependencies)

[About](#about)  

[Collaborators](#collaborators)  

[Branches](#branches) 

[Copyright & Licensing](#copyright--licensing)  

[Contributing](#contributing)  

[Contact](#contact)

## What It Is

**AMX_Manager for GNU/Linux**

AMX manager is an easy and advanced way to utilizing your Linux usability.

## Modules

* **AMX_BOOT:** Boost the RAM & Temp & Cache 

* **AMX_ECHO:** Simple echo commands

* **AMX_PACMAN:** Add and Update commands for Pacman 

* **AMX_POWER:** Simple Power commands (Shutdown, Reboot, Suspend, Standby)

* **AMX_SCREENSHOT:** Taking screenshots

* **AMX_MUSIC:** Music utilities (Play, Pause, Stop)

* **AMX_VOLUME:** Volume utilities (Up, Down, Mute, Toggle)

* **AMX_LIGHT:** Backlight utilities  (Up, Down)

* **AMX_RESOLUTION:** Screen resolution settings

* **AMX_TOUCHPAD:** Laptop Touchpad settings (Enable, Disable, Toggle, Auto)

* **AMX_START:** To start a spesific program

* **AMX_WIFI:** WiFi utilities (Enable, Disable, Connect, Disconnect)

* **AMX_WMCTRL:** Window Manager Controller (Clone, Minify, Maximize)

* **AMX_ANIMATE:** Animate the something

## How To Use

... WILL UPDATE SOON...

## Requirements

* You should be familiar with Shell environment
* You will need a Terminal to run commands
* You will need a least Bash nor ZSH Command Line Shell
* You will need a computer that running Linux

## Dependencies

**WARNING:** `Each AMX module may needed a different dependency. Module will show a error log if there is no required dependency installed in the system.`

* AMX_RAM

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| sync            | -               |

* AMX_PACMAN

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| pacman          | -               |
| reflector       | -               |

* AMX_POWER

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| betterlockscreen| -               |

* AMX_SCREENSHOT

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| xclip           | -               |
| feh             | -               |
| scrot           | -               |

* AMX_MUSIC

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| dbus            | -               |

* AMX_VOLUME

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| amixer          | -               |

* AMX_LIGHT

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| light           | -               |

* AMX_RESOLUTION

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| xrandr          | -               |

* AMX_TOUCHPAD

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| xinput          | -               |
| synclient       | -               |

* AMX_WIFI

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| nmcli           | -               |
| nmtui           | -               |

* AMX_WMCTRL

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| wmctrl          | -               |

* AMX_ANIMATE

| **Dependency**  | **Description** |
| --------------- | --------------- |
| notify-send     | -               |
| xwinwrap        | -               |

## About

AMX_Manager was created to serve three purposes:

**AMX_Manager is a basically Live-Saver GNU/Linux productivity tools repository coded in Shell**

1. To act as a guide to learn basic Shell programming with rich and simple examples

2. To provide a simplest and easiest way to control your Linux environment insted of remembering different commands

3. There is a source for you to develop own AMX module in Shell and inreace your Shell programming level

## Collaborators

**Project Manager** - Furkan Türkal (GitHub: **[Dentrax](https://github.com/dentrax)**)

## Branches

We publish source for the **[AMX_Manager]** in single rolling branch:

The **[master branch](https://github.com/dentrax/AMX_Manager/tree/master)** is extensively tested and makes a great starting point for using the AMX_Manager. Also tracks [live changes](https://github.com/dentrax/AMX_Manager/commits/master) by commits.

## Copyright & Licensing

The base project code is copyrighted by Furkan 'Dentrax' Türkal and is covered by single licence.

All program code (i.e. .sh) is licensed under [MIT License](https://opensource.org/licenses/MIT) unless otherwise specified. Please see the **[LICENSE.md](https://github.com/Dentrax/AMX_Manager/blob/master/LICENSE)** file for more information.

**References**

While this repository is being prepared, it may have been quoted from some sources. 

- https://github.com/metinUr/dotfiles/tree/master/opt/bin

If there is an unspecified source or if you think that I made a copyright infringement, please contact with me.

## Contributing

Please check the [CONTRIBUTING.md](CONTRIBUTING.md) file for contribution instructions and naming guidelines.

## Contact

AMX_Manager was created by Furkan 'Dentrax' Türkal

 * <https://www.furkanturkal.com>
 
You can contact by URL:
    **[CONTACT](https://github.com/dentrax)**

<kbd>Best Regards</kbd>