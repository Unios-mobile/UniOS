# UniOS
UniOS is a ARM mobile OS designed to allow porting of different executables on one device. 
The possible executables it can run are APK and UNX (uniOS's custom executables).

# Languages
The languages that UniOS is programmed in is C++, Lua, Kotlin with SASS for the some UI support.

# Uses
UniOS is good for those whom like a secure and private running. With a custom app store that draws on different APKs that you can find on GitHub, Google Play Store, and f-droid.

# Developing Apps For UniOS
UniOS apps are written in Kotlin for easy access to your PC via a USB connection. 
The configuration files use Lua.

# Backbone
UniOS uses the /e/OS — a deGoogled version of the Android kernel—  kernel, with custom daemons for the OS to allow `.rpm`, `.deb`, `.exe`, and `.unx` files. 

For what /e/OS is please visit their [website](https://e.foundation/e-os/). To see some phones that use it, you can go to visit [murena.com > Shop](https://murena.com/) for the information. 

# Stack
The stack used is:
- ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white)
- ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
- ![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white)

## Explaining the Languages
For the system files that *aren't* configuration files, Rust is used. For the configuration files, Lua is used. For the UI and apps, Kotlin is used.

There is other allowed languages such as React but all standard UniOS apps are made with Kotlin, Lua, and Rust

# Custom File Formats
- **UNX**: UNX files are the executables/package files that are used to run UniOS
- **UNI**: UNI files are the configuration files for the system. It accepts Lua, KDL, and ~~C++~~ Rust.
# Pre-Installed Software 
## Tag Definitions
- `[Optional]`: An app with the [Optional] tag means that it will be in the downloads page for you to download when you install UniOS
- `[Forked]`: An app with the [Forked] tag means that it is forked from another open-source project. Often it is for it to be UniOS compatible.
- `[Closed-Source]`: An app with the [Closed-Source] tag means that the app's source code is not visible and is ***NOT*** recommended for privacy minded indivisuals.
- `[Open-Source]`: An app with the [Open-Source] tag means that the app's source code is publicly avaliable and recommended for privacy minded indvisuals.
    - These apps will be followed by a link at the end to the source code.
## Apps
UniOS comes with custom forks of some Android software along with its own custom software.
### Android Apps
- [Open-Source] [Aurora Store](https://f-droid.org/en/packages/com.aurora.store/): An APK store that can be downloaded from F-Droid to have Google Play apps without Google Play. [Source-Code](https://gitlab.com/AuroraOSS/AuroraStore) 
- [Optional] [Open-Source] [Element](https://f-droid.org/en/packages/io.element.android.x/): An APK file that allows you to use Matrix. [Source-Code](https://github.com/element-hq/element-android)
- [Open-Source] [F-Droid](https://f-droid.org/): [FOSS](https://en.wikipedia.org/wiki/Free_and_open-source_software) APK App store [Source-Code](https://gitlab.com/fdroid/fdroidclient)
- [Open-Source] [microG](https://github.com/microg/GmsCore/releases/tag/v0.3.11.250932): Allows Google Play Services without Google Play services. [Source-Code](https://github.com/microg/GmsCore/)
### Uni Apps
- UniStore: UniOS app store.
    - **Accessed stores & libraries:**
        - Google Play → Not in the base version, but will be scraped in later versions to allow you to have one unified store.
- UniSys: UniOS System Settings
- UniScreen: UniOS App Launcher. 
    - **Possible Launchers**: 
        - [Forked] from [Open-Source] [KISS Launcher](https://f-droid.org/packages/fr.neamar.kiss) [Source-Code](https://github.com/Neamar/KISS) → forked to be compatible with UniOS.
- UniCam: UniOS Camera app.
- UniDate: UniOS calander app.
- UniMsg: UniOS SMS app. 

# Other Files 
- [CODE_OF_CONDUCT.MD](https://github.com/Unios-mobile/UniOS/blob/main/CODE_OF_CONDUCT.md)
- [FAQ.md](https://github.com/Unios-mobile/UniOS/blob/main/FAQ.md)
- [LICENSE](https//github.com/Unios-mobile/UniOS/blob/main/LICENSE)
- [ROADMAP.md](https://github.com/Unios-mobile/UniOS/blob/main/ROADMAP.md)
- [SECURITY.md](https://github.com/Unios-mobile/UniOS/blob/main/SECURITY.md)

# NOTICE
UniOS scrapes data from certain sources, these sources are to allow you to have access to every app. 
**Scraped Sources:**
- One of these sources is the Google Play Store.
