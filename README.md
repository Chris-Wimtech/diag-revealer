MobileInsight Mobile (Diag_Revealer)
==============

Diag Revealer is the in-device raw cellular message extracter, compiled in native C.

This has been extracted from the Mobile-Insight Mobile App repository for compiling independently.

The structure of this repo is organized as follows:

```
.
├── README.md: this file
├── mtk: Diag_Revealer sources for MTK processors
├── qcom: Diag_Revealer sources for Quelcomm processors
├── diag_revealer:
```


## Quickstart

To build Diag_Revealer you're going to need the following tools:

- Make
- Android Studio + Android NDK

###Setup (Windows)

1. Get Chocoloty
    Setup is going to use Cholocolaty (https://chocolatey.org/), the package manager for windows.
    If you haven't already, please install it and ensure you have an open console with admin privileges.
2. Install make
    Run `choco install make` in a console window
3. Install the Android NDK as described here (https://developer.android.com/ndk/guides)
4. Add NDK tools to the windows PATH.
    Default install location for NDK is at C:\Users\User\AppData\Local\Android\Sdk\ndk-bundle

###Building
Instructions for building are included sub-directories for each version on this repo.
Output will appear in the `libs` folder.
