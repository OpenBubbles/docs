---
sidebar_position: 3
---
# Phone Number Registration
**DISCLAIMER**: **Phone Number Registration is not perfect and it has various issues and may not be as reliable, different carriers may also not play nicely with the Sim swap methods, OpenBubbles operates BEST with Mac hardware codes.**

**The following guide contain links to third-party websites that are not affiliated with OpenBubbles and their content can change at any time. Use at your own risk.**

Learn how to get your phone number working on iMessage. The app will default to sending to whatever handle is chosen in settings/setup. 
You can also choose to skip logging in with AppleID. This may lead to less issues with certain users.

## Pre-Setup | Do this first
Make sure iMessage/Facetime is disabled on your iPhone, you also need to disable Advanced Data Protection and Contact Key Verification.
You may need a new AppleID for this process if your existing AppleID is blocked from iMessage.

## Sim / eSim Swaping Methods
The guide linked below is made by a BlueBubbles community member found on the BlueBubbles docs website. 

Note: This guide was also created before OpenBubbles existed but is a good resource for learning about sim swapping.

[All These BlueBubbles | Sim Swapping Guide](https://guide.atbluebubbles.com/ )

## Relay Apps
This is dependent on jailbreak status. It is also advised to keep the device on at all times and connected to Wi-Fi in order to keep phone number registration. While not required, leaving the display on may improve reliability.

### If your device is not jailbroken. Then follow the following steps.
There are multiple ways to install relay apps in you are not jailbroken here are the guides: 

Guide 1:
1. Use [Sideloadly](https://sideloadly.io/) or [AltStore](https://altstore.io/) to sideload the [provided beepserv installer IPA](https://joshuafhiggins.github.io/beepserv_installer_v0.1.ipa) onto your iPhone (Apple ID required for sideloading).
2. Open the Beepserv Installer app to install and enable beepserv.
3. Turn off iMessage.
4. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from beepserv in OpenBubbles (if you are changing from existing hardware. go to settings, reset, and press "Just change hardware").

Guide 2:

1. Install TrollStore on your device (iOS 14 - iOS 17.0) - [TrollStore Guide](https://ios.cfw.guide/installing-trollstore/)
2. Turn off iMessage, if you have testflight installed, delete it.
3. Sideload JJTech's - [Validation Relay App](https://github.com/JJTech0130/ValidationRelay/releases) TIPA file, download the TestFlight one it typically works better. Then open trollstore and sideload the file.
4. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from the relay app in OpenBubbles (if you are changing from existing hardware. go to settings, reset, and press "Just change hardware").

### If you are on older iOS versions 10 - 14 and jailbroken follow these steps: 

Note: Currently Copperboy's relay server arm64 file on the gitbub linked above not working

Download the working arm64 file [here](https://cdn.discordapp.com/attachments/1273349815803314208/1276915932157055087/dev.copper.relayserver_0.0.1-8debug_iphoneos-arm64.deb?ex=66d47ea2&is=66d32d22&hm=ed6660e60c7915f50c2b4e07c1d53572cbf15b0f63964db554accb4923041fe7&) - This file works with rootless jailbreaks on iOS (15-16.5)
1. Download Copperboy100's - [RelayServer](https://github.com/TaeHagen/relayserver/releases)
2. Install RelayServer 
3. Edit the config file in /var/mobile
4. Retrieve the relay code in /var/mobile
5. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from the relay app in OpenBubbles (if you are changing from existing hardware. go to settings, reset, and press "Just change hardware").

There are other ways to sideload on iOS on newer versions here is a third-party guide. Follow them to sideload a relay app.

Use this guide to sideload apps and sideload trollstore.
https://np.reddit.com/r/sideloaded/comments/1debdgh/guide_how_to_sideload_on_ios_without_expiry/

## More Methods
Note: These methods/guides were made before OpenBubbles existed.
https://docs.bluebubbles.app/server/advanced/registering-a-phone-number-with-your-imessage-account (OpenBubbles is not affiliated with BlueBubbles)


## DO NOT USE
~~https://github.com/thatmarcel/beepserv-rewrite~~

It is known to be **extremely unreliable** and usually only works once.

###
**Credits** : [pypush, jjtech, Alfie,](https://discord.com/channels/1130633272595066880/1135636248019615874/1231003645529817139) [BlueBubbles Team](https://github.com/orgs/BlueBubblesApp/people), [danip](https://discord.com/channels/1130633272595066880/1135636248019615874/1231003645529817139), [cjocollin](https://www.reddit.com/r/BlueBubbles/comments/1938ock/stop_using_old_methods_heres_a_new_one/) and [Copperboy100](https://github.com/TaeHagen)
###
