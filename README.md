# Citra - Unofficial [Windows branch]

This is being maintained from a fork of the Citra Bleeding Edge build 0.1.86.  
As and when I update the build, I'll modify the build number.

Checkout the @master-windows and the @master-linux branch to see the actual files for either of the two OS.  
This just has a readme and is mainly to ease my life with the limited git knowledge I have.  

This also needs a 'user' folder in the top level directory.

# lemonbot merge log

Scroll down for the original README.md!

======

|   PR | Ref                  | Commit                                     | Author      | Status   |
|-----:|:---------------------|:-------------------------------------------|:------------|:---------|
|   19 | pipe3                | `8f51d9522c670158b9517df3af236f24b8c6c31f` | MerryMage   | Merged   |
|   17 | bleeding-edge-base   | `0e2339c482b197b9a049a99c8a4304b11e1430c0` | jroweboy    | Merged   |
|   10 | gs-new-refactor      | `f89d6d920795f3bd9d15cea039ec5263223d8960` | JayFoxRox   | Merged   |
|    5 | jfr-fix-batch-errors | `4f4326d0cf0f7a5e23057df89acf8f0aafa19f41` | jroweboy    | Merged   |
| 2260 | scheduling           | `406907d57055965780e04769482556995de8c50a` | Subv        | Merged   |
| 2240 | auto-region          | `84e78790ab3f3e8883493b18946e97328d921774` | wwylele     | Merged   |
| 2063 | CheatsModule         | `080e24c598e4eda2eec5fdcaf3903c31fef757b0` | makotech222 | Merged   |
| 1995 | inputcore            | `7d5a26d8f4c9e2880fe2166a1b19e1d7eebed9b1` | makotech222 | Failed   |
| 1951 | motion-sensor        | `d43a1e3815c3e572c617aede133c0aafd1cc8dc0` | wwylele     | Merged   |

End of merge log. You can find the original README.md below the break.

======

**BEFORE FILING AN ISSUE, READ THE RELEVANT SECTION IN THE [CONTRIBUTING](https://github.com/citra-emu/citra/blob/master/CONTRIBUTING.md#reporting-issues) FILE!!!**

Citra Emulator
==============
[![Travis CI Build Status](https://travis-ci.org/citra-emu/citra.svg?branch=master)](https://travis-ci.org/citra-emu/citra)
[![AppVeyor CI Build Status](https://ci.appveyor.com/api/projects/status/sdf1o4kh3g1e68m9?svg=true)](https://ci.appveyor.com/project/bunnei/citra)

Citra is an experimental open-source Nintendo 3DS emulator/debugger written in C++. It is written with portability in mind, with builds actively maintained for Windows, Linux and macOS. Citra only emulates a subset of 3DS hardware, and therefore is generally only useful for running/debugging homebrew applications. At this time, Citra is even able to boot several commercial games! Most of these do not run to a playable state, but we are working every day to advance the project forward.

Citra is licensed under the GPLv2 (or any later version). Refer to the license.txt file included. Please read the [FAQ](https://github.com/citra-emu/citra/wiki/FAQ) before getting started with the project.

Check out our [website](https://citra-emu.org/)!

For development discussion, please join us @ #citra on freenode.

### Development

Most of the development happens on GitHub. It's also where [our central repository](https://github.com/citra-emu/citra) is hosted.

If you want to contribute please take a look at the [Contributor's Guide](CONTRIBUTING.md), [TODO list](https://docs.google.com/document/d/1SWIop0uBI9IW8VGg97TAtoT_CHNoP42FzYmvG1F4QDA) and [Developer Information](https://github.com/citra-emu/citra/wiki/Developer-Information). You should as well contact any of the developers in the forum in order to know about the current state of the emulator.

### Building

* __Windows__: [Windows Build](https://github.com/citra-emu/citra/wiki/Building-For-Windows)
* __Linux__: [Linux Build](https://github.com/citra-emu/citra/wiki/Building-For-Linux)
* __macOS__: [macOS Build](https://github.com/citra-emu/citra/wiki/Building-for-macOS)


### Support
We happily accept monetary donations, or donated games and hardware. Please see our [donations page](https://citra-emu.org/page/donate) for more information on how you can contribute to Citra. Any donations received will go towards things like:
* 3DS consoles for developers to explore the hardware
* 3DS games for testing
* Any equipment required for homebrew
* Infrastructure setup
* Eventually 3D displays to get proper 3D output working

We also more than gladly accept used 3DS consoles, preferably ones with firmware 4.5 or lower! If you would like to give yours away, don't hesitate to join our IRC channel #citra on [Freenode](http://webchat.freenode.net/?channels=citra) and talk to neobrain or bunnei. Mind you, IRC is slow-paced, so it might be a while until people reply. If you're in a hurry you can just leave contact details in the channel or via private message and we'll get back to you.