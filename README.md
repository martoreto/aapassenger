# AA Passenger – Android Auto control for passengers

This app allows a passenger to control an Android Auto device connected to the car.

Features:
 - sending navigation destinations
 
 - pushing pictures and screenshots for display
 
 - streaming audio via car speakers ~~(requires root on passenger's phone)~~
 
## Requirements
 
Two devices are needed: one would be connected to the car ("driver's device") and have Android Auto app installed.
The other ("passenger's device") will be able to control it.

The connection is established using either Wi-fi Direct (P2P) or Android Hotspot
(in this case Hotspot must be manually activated before starting Android Auto).

Note that Wi-fi Direct is not always robust and your mileage may vary.
Please test and report the results.

Note that this is now alpha quality, so expect some glitches and report them here:

https://forum.xda-developers.com/android-auto/android-auto-general/app-aa-passenger-remotely-control-t3713198

Minimum supported Android version is 5.0 (Kitkat).

Not supported for non-projected (on the phone screen) Android Auto, although audio streaming seems to work.

## Installation

For initial setup and connection test no car is required. :)

### Driver's device
 
1. [Download](https://github.com/martoreto/aapassenger/releases) AA 2nd Seat APK and install it on the driver's device.
 
1. Open Android Auto app and enable "Unknown sources", per
[official documentation](https://developer.android.com/training/auto/testing/index.html#phone)
or [this video](https://youtu.be/MjHpOaeOmOo).
 
### Passenger's device
 
1. Download [from here](https://github.com/martoreto/aapassenger/releases)
or [from Play Store](https://play.google.com/apps/testing/com.github.martoreto.aapassenger)
the AA Passenger APK, install it on the passenger's device and run.
A nice wizard will appear, guiding you through the next steps.

1. Enjoy.
 
## Is it free?

AA Passenger App is ad-supported.

Pre-release AA 2nd Seat App versions will be free. What about releases? I haven't decided yet.

I'm also open-sourcing useful reusable components of the app. For now we have:
 - the media audio redirection service (https://github.com/martoreto/audiocapture)
 - nicely packaged Opus audio codec (https://github.com/martoreto/opuscodec)
 - the unofficial Android Auto SDK build scripts (https://github.com/martoreto/aauto-sdk)

## Screenshots

![Screenshot 1](media/nav1.png)

![Screenshot 2](media/audio2.png)

![Screenshot 3](media/sshot3.png)
