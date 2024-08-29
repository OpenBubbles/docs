---
sidebar_position: 3
---
# Phone Number Registration
**DISCLAIMER**: **Phone Number Registration is not perfect and it has various issues and may not be as reliable,different carriers may also not play nicely with the Sim swap methods, OpenBubbles operates BEST with Mac hardware codes.**

Learn how to get your phone number working on iMessage. The app will default to sending to whatever handle is chosen in settings/setup.

Make sure iMessage is disabled on your iPhone, you also need to disable Advanced Data Protection and Contact Key Verification. You may need a new AppleID for this process.

These are the methods to get your phone number registered on iMessage.

## Sim / eSim Swaping Methods
The guide linked below is made by a BlueBubbles community member found on the BlueBubbles docs website. 

Note: This guide was also created before OpenBubbles existed but is a good resource for learning about sim swapping.

[All These BlueBubbles | Sim Swapping Guide](https://guide.atbluebubbles.com/ )

## Relay Apps
This is dependant on jailbreak status. It is also advised to keep the device on at all times and connected to wifi in order to keep phone number registration. While not required, leaving the display on may improve reliability.
If your device is not jailbroken. Then follow the following steps.

1. Use [Sideloadly](https://sideloadly.io/) or [AltStore](https://altstore.io/) to sideload the [provided beepserv installer IPA](https://cdn.discordapp.com/attachments/1130641573244317736/1230994423958077450/beepserv_installer_v0.1.ipa?ex=66d0e8e5&is=66cf9765&hm=04366038bd916e9b5e04e217a2023df6a39ee3877e7b1eba827b95a36940ca29&) onto your iPhone (Apple ID required for sideloading).
2. Open the Beepserv Installer app to install and enable beepserv.
3. Turn off iMessage.
4. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from beepserv in OpenBubbles(if you are changing from existing hardware. go to settings,reset,and press "Just change hardware").

If you are jailbroken follow these steps:

1. Install TrollStore on your device (iOS 14 - iOS 17.0) - [TrollStore Guide](https://ios.cfw.guide/installing-trollstore/)
2. Turn off iMessage, if you have testflight installed, delete it.
3. Sideload JJTech's - [Validation Relay App](https://github.com/JJTech0130/ValidationRelay/releases) TIPA file, download the testflight one it typically works better. Then open trollstore and sideload the file.
4. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from the relay app in OpenBubbles(if you are changing from existing hardware. go to settings,reset,and press "Just change hardware").

If you are on older iOS versions 10 - 14  and jailbroken follow these steps : 

1. Download Copperboy100's - [RelayServer](https://github.com/TaeHagen/relayserver/releases)
2. Install RelayServer 
3. Edit the config file in /var/mobile
4. Retrieve the relay code in /var/mobile
5. Install OpenBubbles if you haven't already and follow the setup steps, and input the code from the relay app in OpenBubbles(if you are changing from existing hardware. go to settings,reset,and press "Just change hardware").

## More Methods
Note: These methods/guides were made before OpenBubbles existed.
https://docs.bluebubbles.app/server/advanced/registering-a-phone-number-with-your-imessage-account (OpenBubbles is not affiliated with BlueBubbles)
##  DO NOT USE
~~https://github.com/thatmarcel/beepserv-rewrite~~

It is known to be **extremely unreliable** and usually only works once.

---
**Credits** : pypush,jjtech,Alfie,BlueBubbles Team,danip and Copperboy100
---