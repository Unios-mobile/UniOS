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
- ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
- ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white)
- ![Lua](https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white)

## Explaining the Languages
For the system files that *aren't* configuration files, C++ is used. For the configuration files, Lua is used. For the UI and apps, Kotlin is used.

# Custom File Formats
- **UNX**: UNX files are the executables/package files that are used to run UniOS
- **UNI**: UNI files are the configuration files for the system. It accepts Lua, KDL, and C++
