# Signing Information

**If your iDevice is not jailbroken the app must be signed before you can run it, a red flag for an incorrectly signed app is the app will crash immediately after launching it.**

**If you are new to this, the current recommended signing and installation method is to use UDID Registrations to register your device, and then Flysign to sign and install the app to your device.  It's simple, quick, gets you up and running with the least hassle, and the app stays signed for 12 months**

If your device is jailbroken you do not need to sign the IPA.

## UDID Registrations and Flysign
* UDID Registrations can provide you with the necessary files to sign the app for 12 months. This effectively gives you the benefits of using an Apple developer certificate at a much smaller cost.
* The silver package is the cheapest package that offers the necessary files to sign and install Mod DJI Fly, however I recommend the gold package as it offers protection if your device gets revoked.
* You can register your device with UDID Registrations [HERE](https://www.udidregistrations.com/buy)
* When you receive the email from UDID Registrations after registering your iDevice, select 'view your order', and then select 'Certificate and Provisioning Files'...download these 2 files somewhere easy to find. This can be done either from your Mac/PC, or direct from your iDevice. At this point you can use Flysign which is a quick simple online solution that will sign and install Mod DJI Fly direct to your iDevice. 
* **I must point out that I'm not affiliated with UDID Registrations in any way and I'm not responsible for your experiences with them, however I currently use their service and have experienced zero problems.**

{%include button_guide_flysign.html %}{: .btn_indent}

## Apple Developer
* IPAs can be signed with an Apple developer certificate.
* This will need repeating every 12 months, and is not free. 
* If you have your .mobileprovision and .p12 files, and your .p12 password you can follow the FlySign guide at the bottom of this page. 

## Standard Apple ID
* IPAs can be signed with a standard Apple ID, this is free, but needs repeating every 7 days.
* On Mac OS use ios app signer or sideloadly, on Windows use sideloadly or 3utools.



Note: There are many other tools/methods/services available to sign and install apps, use whatever you're comfortable with...I'm just giving a couple of examples of ones I have personally used and tested.



