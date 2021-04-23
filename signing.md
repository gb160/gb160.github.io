---
youtubeId: Z0mQE90xPa4
---

# Signing Information

**If your iDevice is not jailbroken the IPA must be signed before you can run it, a red flag for an incorrectly signed IPA is the app will crash immediately after launching it.**

If your device is jailbroken you do not need to sign the IPA.

## Standard Apple ID
* IPAs can be signed with a standard Apple ID, this will need repeating every 7 days, this is free. On Mac OS use ios app signer or sideloadly, on Windows use sideloadly or 3utools.


## Apple Developer
* IPAs can be signed with an Apple developer certificate.
* This will need repeating every 12 months, and is not free. 
* If you have your .mobileprovision and .p12 files, and your .p12 password you can follow the FlySign guide at the bottom of this page. 

## Third Party App signing 
* There are third party app signing services who will provide you with the necessary files to sign the IPA for 12 months. This effectively gives you the benefits of using an Apple developer certificate at a smaller cost.
* One such service that many people use is [UDID Registrations](https://www.udidregistrations.com/buy)
* The silver package is the cheapest package that offers the necessary files to sign and install Mod DJI Fly, however I recommend at least the gold package as it offers protection if your device gets revoked...the platinum package also offers online IPA signing and installation, however I've never used this function so I cannout vouch for it.
* When you have your .mobileprovision .p12 files, and your .p12 password you can follow the FlySign guide below. 
* **I must point out that I'm not affiliated with UDID Registrations in any way, and I'm not responsible for your experiences with them. I've used their service before and had a positive experience.**


## Flysign Guide
* **This guide can only be used when you have the files '.mobileprovision', '.p12', and you have the .p12 password, these will all be provided by UDID Registrations or can be retrieved from your apple developer account**

* This method is the quickest and easiest way to install the app without a jailbreak, as the signing and installation can be done direct from your iDevice without downloading the .ipa file, so a Mac/PC isn't required, just transfer/email your .p12 and .mobileprovision files to your iDevice.


![IMG_0176](https://user-images.githubusercontent.com/2493592/115844922-3a58ca80-a418-11eb-87bb-016da4119137.jpg)


* Go to: [FlySign](https://flysign.ddns.net)
* Click/tap on 'signing'
* Select your '.mobileprovision' and '.p12' files.
* Enter your .p12 password
* Click/tap on the 'sign app' button
* After a few seconds a QR Code will appear on the screen
* * If you are on a PC/Mac, just open the camera on your iDevice and let it focus on the QR Code, then select 'open in iTunes' and agree to the install prompt.
* * If you are using your iDevice tap and hold the QR Code, then select 'open in iTunes' and agree to the install prompt.
* The app will now install to your homescreen, installation can take a few minutes so be patient.
* See below for video of signing/installation using FlySign:



{% include youtubePlayer.html id=page.youtubeId %}



Note: There are many other tools/methods/services available to sign and install apps, use whatever you're comfortable with...I'm just giving a couple of examples of ones I have personally used and tested.



