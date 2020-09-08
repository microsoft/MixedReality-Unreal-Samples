# HoloLens 2 Example App

Spawn Paragon minions on the surface of your world and store their locations with persistent anchors. This is a simple HoloLens 2 app built with Unreal Engine 4.24 that demonstrates:
* Basic articulated hand tracking-based interactions in the form of fingertip cursor and pushable buttons
* Spatial mapping and collision understanding
* Launching, saving and loading persistent anchors in the world

Supported Unreal versions | Supported device
:-----------------: | :----------------:
Unreal Engine 4.24+ | HoloLens 2

## How to build and deploy the app

Make sure you have Unreal Engine 4.24 or later installed on your computer. 
* If you do not have a HoloLens 2 device, first follow the [App Packaging Instructions](https://docs.unrealengine.com/en-US/Platforms/AR/HoloLens2/HowTo/PackageApp/index.html) and then follow the [Emulator Quickstart Instructions](https://docs.unrealengine.com/en-US/Platforms/AR/HoloLens2/QuickStartEmulator/index.html) to deploy the app to the [HoloLens 2 Emulator](https://docs.microsoft.com/en-us/windows/mixed-reality/using-the-hololens-emulator)
* If you have a HoloLens 2 device and want to run the app on device, first follow the [App Packaging Instructions](https://docs.unrealengine.com/en-US/Platforms/AR/HoloLens2/HowTo/PackageApp/index.html) and then follow the [Device Quickstart Instructions](https://docs.unrealengine.com/en-US/Platforms/AR/HoloLens2/QuickStartDevice/index.html) to deploy the app to your HoloLens 2
* If you have a HoloLens 2 device and want to stream the app to device, follow the [Streaming Quickstart Instructions](https://docs.unrealengine.com/en-US/Platforms/AR/HoloLens2/QuickStartStreaming/index.html) to stream the app from the Unreal editor to your HoloLens 2

## How to use the app

Press the "Spawn" button to bring up the launch pin. The launch pin is steered by head gaze, aiming at a horizontal planar surface will allow you to [airtap](https://docs.microsoft.com/en-us/windows/mixed-reality/gestures#air-tap) to place a character anchor.
Pressing  "Save Pins" will store the anchors to the device.
Pressing "Clear Pins" will delete the anchor information stored on device (but will not remove current live anchors).
If the app is closed and/or reset, pressing "Load Pins" will restore the saved characters and anchors. 

On the Emulator, you can also use key presses to trigger the buttons. Make sure you uncheck "Use keyboard for simulation" in the [simulation control panel](https://docs.microsoft.com/en-us/windows/mixed-reality/using-the-hololens-emulator#simulation-control-panel) first. Press 1 for "Spawn", 2 for "Save Pins", 3 for "Clear Pins", and 4 for "Load Pins". 