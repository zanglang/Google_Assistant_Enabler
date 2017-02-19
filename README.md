# Google Assistant Enabler
This Magisk module enables Google Assistant on phones running Nougat. [More details in support thread](http://forum.xda-developers.com/apps/magisk/module-google-assistant-enabler-magisk-t3518883).

## How to install/use
For smooth experience transitioning to Google Assistant from Google Now follow these steps:

1. Enable OK Google Detection from any screen and train the voice model **before** installing the module.

2. Install the module in Magisk Manager, but do not reboot.

3. Manually reboot to recovery and wipe Cache **and** Dalvik/ART Cache and then start the phone.

## Requirements
1. Android Nougat 7.0+
2. Google app version 6.10.31.21 or higher (if your current version of Google app is lower, you can opt in for beta-test of Google app [here](https://play.google.com/apps/testing/com.google.android.googlequicksearchbox))
3. Magisk 10 or higher
4. Magisk Manager 3.0 or higher


## Important Notice
From version 10.0.2 this module no longer changes the phone model/manufacturer. This is due to the fact that as of Google app version 6.10.31.21 the Google Assistant no longer requires the phone to be either Pixel or Pixel XL.

The legacy version which still changes the phone model can be downloaded [here](https://github.com/stangri/MagiskFiles/raw/master/GoogleAssistantEnabler-10.0.1.zip). It is kept for people who have apps which trigger security protection when the phone model change is detected. This is also the latest version compatible with Magisk 9.

## Change Log
10.0.2
    - No longer change phone model/manufacturer

10.0.0
    - Magisk v10-compatible

2.0.0
    - Magisk v9-compatible
