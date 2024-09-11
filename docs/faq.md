---
sidebar_position: 3
---



# FAQ

## What is "Hardware Info"?&#x20;

During iMessage activation, your machine's hardware identifiers (serial number, board ID, model, etc.) are sent to Apple for validation. 
OpenBubbles requires valid machine identifiers to send to Apple during activation. OpenBubbles refers to this data as "hardware info".

## How can I obtain hardware info?

If you have access to a Mac, download the [hardware info app](https://github.com/OpenBubbles/Mac-Hardware-Info/releases). 

Once installed, you will receive a code you can paste into OpenBubbles and a code you can scan with the app for ease of use.

## Can OpenBubbles import existing messages? 
* If you have a previous OpenBubbles message backup, yes. To create or restore one, go to Settings -> Backup & Restore -> Messages Backups.
* If you do not have an OpenBubbles message backup, not at this time. OpenBubbles cannot backfill messages from iCloud.

## What if I do not have access to a Mac?

* If you don't have access to a Mac, ask a friend to share their code with you. They can share it from the hardware info app on the Mac, or from settings inside OpenBubbles. One Mac can be used by up to 20 users (unlimited logins).

## Does the Mac need to stay online?&#x20;

* No! Once you have setup OpenBubbles, feel free to turn off, discard, or do anything you wish with your Mac. Keep in mind the physical Mac may still be useful for troubleshooting.

## What does "prevent sharing" do?

* Enabling "prevent sharing" applies a few restrictions to generated codes:
* Can only be used once (text codes only)
* Expire after 48 hours (text codes only)
* Cannot be shared to other users after completing setup.

## Is OpenBubbles safe to use?&#x20;

* Everything happens locally, on your phone. Anything that happens is strictly between you and Apple. An immense effort has been made to ensure a reliable and safe experience. That being said, iMessage is a complex and changing system, and every situation cannot be predicted. Most issues will only affect OpenBubbles, and will not affect other devices or your account. In extremely rare cases, your account may be temporarily (day or two) or permanently blocked. In permanent cases, a call with Apple support will usually lift the block.
:::note
You are responsible for who you share your hardware identifiers with. If someone uses your hardware identifiers to send mass spam, your device _**will**_ be blocked, and you will only have yourself to blame. If you share one device with over 20 users, you may experience issues.
:::
## I am having issues logging into my Apple ID
* To potentially resolve this issue, go to https://appleid.apple.com/, and delete any duplicate devices and try again.


## Can I register my phone number with OpenBubbles?

* &#x20;If you have an iPhone running the relay app, yes. The phone must stay online at all times. Enter the relay code on the hardware identifier screen, and you will be prompted to register your number. Please refer to the [Phone Number Registration](Setup/pnr) page for more information.

## Does OpenBubbles work with FindMy?

* No, OpenBubbles does not have FindMy integration.

## Does OpenBubbles work with FaceTime?

* No, OpenBubbles does not work with FaceTime.

## Why are contacts I know are using iMessage showing up green?

This means you are throttled by Apple. Wait a few hours/days and try again.
* If you recently registered, this can be normal.
* If you have texted many people (group chat or otherwise) you may have to wait a few days or weeks for Apple to raise your limit.

## Why can't I send or receive messages?

* Running clear identity cache (Go to settings, troubleshooting) - This may help with sending messages.
* Make sure iMessage and Facetime is disabled and you are logged out of iCloud if you are using an iPhone.
* You are deregistered - Check your registration status and renewal time in your profile settings and check your registration method and try again.
* Advanced Data Protection is enabled - Disable this option
* Contact Key Verification is enabled - Disable this option
* Your Apple ID/Hardware has been throttled/banned/blocked by Apple - Visit this [site](https://rentry.org/applebans) to learn more. You may need to create a new account.

Contact us in the [discord](https://discord.gg/98fWS4AQqN) if issues persist.

## Why can't I see my messages sent on OpenBubbles on other Apple devices, even though my Apple ID is linked?

* This is a known issue and fixes itself after 24 hours.