# Signing Information

**If your iDevice is not jailbroken the IPA must be signed before you can run it, a red flag for an incorrectly signed IPA is the app will crash immediately after launching it.**

If your device is jailbroken you do not need to sign the IPA.

**If you are new to this the current recommended signing and installation method is to use UDID Registrations to register your device, and then Flysign to sign and install the app to your device. It's simple, quick, and gets you up and running with the least hassle.**


## UDID Registrations and Third Party App signing 
* There are third party app signing services who will provide you with the necessary files to sign the IPA for 12 months. This effectively gives you the benefits of using an Apple developer certificate at a smaller cost.
* One such service that many people use is [UDID Registrations](https://www.udidregistrations.com/buy)
* The silver package is the cheapest package that offers the necessary files to sign and install Mod DJI Fly, however I recommend at least the gold package as it offers protection if your device gets revoked.
* **I must point out that I'm not affiliated with UDID Registrations in any way, and I'm not responsible for your experiences with them. I've used their service before and had a positive experience.**

## Flysign is a quick, simple online solution for signing and installing Mod DJI Fly
* When you have your .mobileprovision, .p12 files and your .p12 password you can follow the FlySign guide:

* {%include button_guide_flysign.html %}

## Apple Developer
* IPAs can be signed with an Apple developer certificate.
* This will need repeating every 12 months, and is not free. 
* If you have your .mobileprovision and .p12 files, and your .p12 password you can follow the FlySign guide at the bottom of this page. 

## Standard Apple ID
* IPAs can be signed with a standard Apple ID, this is free, but needs repeating every 7 days.
* On Mac OS use ios app signer or sideloadly, on Windows use sideloadly or 3utools.



Note: There are many other tools/methods/services available to sign and install apps, use whatever you're comfortable with...I'm just giving a couple of examples of ones I have personally used and tested.



