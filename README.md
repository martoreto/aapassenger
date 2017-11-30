# AA Passenger – Android Auto control for passengers

This app allows a passenger to control an Android Auto device connected to the car.

Features:
 - sending navigation destinations
 
 - pushing pictures and screenshots for display
 
 - streaming audio via car speakers (requires root)
 
 ## Requirements
 
 The connection is established using Wi-fi Direct (P2P).
 Therefore both devices must not only support it, but do it robustly.
 Unfortunately this is not always the case and your mileage may vary.
 Please test and report the results.
 
 Note that this is now alpha quality, so expect some glitches and report them here:
 
 TODO
 
 ## Installation
 
 For installation, two devices are needed: one would be connected to the car ("driver's device") and has Android Auto installed.
 The other ("passenger's device") is able to control it.
 
 For initial setup no car is required. :)
 
 ### Driver's device
 
 1. [Download](https://github.com/martoreto/aapassenger/releases) AA Remote APK and install it on the driver's device.
 
 1. Open Android Auto app and enable "Unknown sources", per
 [official documentation](https://developer.android.com/training/auto/testing/index.html#phone)
 or [this video](https://youtu.be/MjHpOaeOmOo).
 
 ### Passenger's device
 
 1. [Download](https://github.com/martoreto/aapassenger/releases) AA Passenger APK, install it on the passenger's device and run.
 A nice wizard will appear, guiding you through the next steps.
 
 1. To enable audio streaming, another application called [Audio Capture Service](https://github.com/martoreto/audiocapture)
 must me installed on the passenger's device. This requires root (or a custom recovery).
 