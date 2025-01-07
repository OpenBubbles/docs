---
sidebar_position: 3
---
# Phone Number Registration
:::note[disclaimer]
Phone Number Registration may not be as reliable as Mac registration, and different carriers may not play nicely. OpenBubbles operates **BEST** with Mac hardware codes. Phone Number Registration is **NOT** required to use OpenBubbles. 

The following guide contains links to third-party websites that are not affiliated with OpenBubbles and their contents can change at any time. Use at your own risk.
:::
Learn how to get your phone number working on iMessage. The app will default to sending to whatever handle is chosen in settings or setup. 
You can also choose to skip logging in with Apple Account. This may lead to less issues in some cases.

## Pre-Setup | Do this first
Make sure iMessage (Only if you are using [Relay Apps](https://openbubbles.github.io/docs/Setup/pnr#relay-apps)) and Facetime is disabled on your iPhone. You also need to disable Advanced Data Protection and Contact Key Verification.

## Sim / eSim Swaping Methods

Sim swapping is a method which involves using an iPhone to register a number, and then using OpenBubbles normally with Mac hardware data. You can follow the same guides used for BlueBubbles. However, this method can be even more unreliable than OB.
[All These BlueBubbles | Sim Swapping Guide](https://guide.atbluebubbles.com/ )

## Relay Apps
Keep the device on at all times and connected to Wi-Fi in order to keep your number registered. 
While not required, leaving the display on may improve reliability.

### Method 1 - Validation Relay
There are multiple ways to install Validation Relay. 
This is dependent on iOS version and device hardware. 
This guide can be followed regardless of jailbreak status: 
 
Guide 1 - TrollStore

1. Install TrollStore on your device (iOS 14 - iOS 17.0) - [TrollStore Guide](https://ios.cfw.guide/installing-trollstore/)
2. If you have testflight installed, delete it.
3. Sideload JJTech's - [Validation Relay App](https://github.com/JJTech0130/ValidationRelay/releases) TIPA file. Then open trollstore and sideload the file.
4. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from the relay app in OpenBubbles (if you are changing from existing hardware. go to settings, reset, and press "Just change hardware").
5. Enable Keep Awake and Dim Display
6. Ignore if on version V1.8 or higher. ~~Set location services to always for the relay app. (Go to Settings, Privacy & Security, Location Services and Relay)~~
7.  Optional Steps  - If you are Jailbroken (tweaks may not be compatible with your iOS version) you can install the following apps, [AdvancedBrightnessSlider](https://havoc.app/package/advancedbright) to lower the risk of screen burn in, install [ChargeLimiter](https://github.com/lich4/ChargeLimiter?tab=readme-ov-file#Introduction) to limit charge of the battery and [Immortalizer](https://havoc.app/package/immortalizer) to keep the relay app in the active while the screen is off.

Guide 2 -  Sideloading Beepserv - Installs a out of date Validation Relay and is no longer recommended 

~~1. Use [Sideloadly](https://sideloadly.io/) or [AltStore](https://altstore.io/) ([SideStore](https://sidestore.io/) and [Feather](https://github.com/khcrysalis/Feather) are other options, Feather requires a Apple certificate to work),
 to sideload the [provided beepserv installer IPA](https://joshuafhiggins.github.io/beepserv_installer_v0.1.ipa) onto your iPhone (Apple Account required for sideloading).
2. Open the Beepserv Installer app to install and enable beepserv.
3. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from beepserv in OpenBubbles (if you are changing from existing hardware. go to settings, reset, and press "Just change hardware").
4. Set location services to always for the relay app. (Go to Settings, Privacy & Security, Location Services and Relay)~~

### Method 2

If you are on older iOS versions(10 - 14) and jailbroken follow these steps: 

Note: Currently Copperboy's relay server arm64 file on the github linked is not working

Download the working arm64 file [here](/files/dev.copper.relayserver_0.0.1-8+debug_iphoneos-arm64.deb) - This file works with rootless jailbreaks on iOS (15-16.5)
1. Download Copperboy100's - [RelayServer](https://github.com/OpenBubbles/relayserver/releases)
2. Install RelayServer 
3. Edit the config file in /var/mobile
4. Retrieve the relay code in /var/mobile
5. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from the relay app in OpenBubbles (if you are changing from existing hardware. go to settings, reset, and press "Just change hardware").

There are other ways to sideload on iOS on newer versions, follow these third-party guides to sideload a relay app and trollstore.

https://np.reddit.com/r/sideloaded/comments/1debdgh/guide_how_to_sideload_on_ios_without_expiry/

https://docs.google.com/document/d/1QseJR-ZTGJO0q99l9eh1-wsR-tldtbsM6rbsti08EDQ

## DO NOT USE
~~https://github.com/thatmarcel/beepserv-rewrite~~

It is known to be **extremely unreliable** and usually only works once.

###
**Credits** : [pypush, jjtech, Alfie,](https://discord.com/channels/1130633272595066880/1135636248019615874/1231003645529817139) [BlueBubbles Team](https://github.com/orgs/BlueBubblesApp/people), [danip](https://discord.com/channels/1130633272595066880/1135636248019615874/1231003645529817139), [cjocollin](https://www.reddit.com/r/BlueBubbles/comments/1938ock/stop_using_old_methods_heres_a_new_one/) and [Copperboy100](https://github.com/TaeHagen)
###
