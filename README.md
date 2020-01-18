# AdColony Android SDK
* Modified: January 17th, 2020
* SDK Version: 4.1.3

## Overview
AdColony delivers zero-buffering, [full-screen, Instant-Play™ HD video](https://www.adcolony.com/technology/instant-play/), [interactive Aurora™ Video](https://www.adcolony.com/technology/auroravideo/), and Aurora™ Playable ads that can be displayed anywhere within your application. Our advertising SDK is trusted by the world’s top gaming and non-gaming publishers, delivering them the highest monetization opportunities from brand and performance advertisers. AdColony’s SDK can monetize a wide range of ad formats including in-stream/pre-roll, out-stream/interstitial and V4VC™, a secure system for rewarding users of your app with virtual currency upon the completion of video and playable ads.


## Release Notes

#### 4.1.3

* Updated OM SDK to v1.3.0

Here is the link to the [release notes](https://github.com/AdColony/AdColony-Android-SDK/blob/master/CHANGELOG.md) for all the previous SDK versions.

## Getting Started 
To get started, here is the link to [Android SDK integration documentation](https://github.com/AdColony/AdColony-Android-SDK/wiki).

### Supporting 64-bit on Android
Version 3.3.7 and above no longer uses the .so libraries and these can be removed from your project. SDK 3.3.7 and above supports 64-bit without the .so libraries.

If you are using using earlier 3.x SDK versions you need to add the proper libadcolony.so and libjs.so architectures to your project to support 64-bit.

## Upgrade 
#### SDK 2.x:

Please note that updating from our 2.x SDK is not a drag and drop update, but rather includes breaking API and process changes. In order to take advantage of the 3.x SDK, a complete re-integration is necessary. Please review our [documentation](https://github.com/AdColony/AdColony-Android-SDK/wiki) to get a better idea on what changes will be necessary in your app.

#### SDK 3.x:
Update the AdColony library referenced by your project following the steps below:

**Manual**

* Drag and drop the adcolony.jar into your project.

**Via Gradle**

Assuming our maven repo is added to your project (see our [project setup guide](https://github.com/AdColony/AdColony-Android-SDK/wiki/Project-Setup)), update your 'dependencies' configuration within your module's build.gradle to point to the latest version:

```
dependencies {
  /** 
   * Any other dependencies your module has are placed in this dependency configuration
   */
  implementation 'com.adcolony:sdk:4.1.3'
}
```

## Legal Requirements
By downloading the AdColony SDK, you are granted a limited, non-commercial license to use and review the SDK solely for evaluation purposes.  If you wish to integrate the SDK into any commercial applications, you must register an account with AdColony and accept the terms and conditions on the AdColony website.

Note that U.S. based companies will need to complete the W-9 form and send it to us before publisher payments can be issued.

## Contact Us
For more information, please visit AdColony.com. For questions or assistance, please email us at support@adcolony.com.
