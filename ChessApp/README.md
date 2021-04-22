---
page_type: sample
languages:
- cpp
products:
- windows
- mixed-reality
- hololens
---

# Chess App

![License](https://img.shields.io/badge/license-MIT-green.svg)

 The final result of the Unreal + UX Tools [tutorial](https://docs.microsoft.com/windows/mixed-reality/unreal-uxt-ch1) located on the Microsoft Mixed Reality docs. Use what you've learned to add the rest of the pieces to the board! 

Supported Unreal versions | Supported device | Built with UXT version
:-----------------: | :----------------: | :----------------------:
Unreal Engine 4.25+ | HoloLens 2 | 0.9

## Contents

| File/folder | Description |
|-------------|-------------|
| `Config` | HoloLens and default configuration files. |
| `Content` | Project files and assets. |
| `Plugins/UXTools` | Mixed Reality Toolkit for Unreal UX Tools plugin components. |
| `.gitignore` | Define what to ignore at commit time. |
| `ChessApp.uproject` | Unreal Engine project file. |
| `ChessAssets.7z` | Zipped asset file with models and materials. |
| `README.md` | This README file. |

## Prerequisites

You can find the samples most up-to-date prerequisites and installation instructions in the [tutorial series](https://docs.microsoft.com/windows/mixed-reality/develop/unreal/tutorials/unreal-uxt-ch1#prerequisites).

## Setup

1. Clone or download this sample repository
2. Open the ChessApp.uproject in Unreal Engine

## Running the sample

* To run the experience in-editor, select "Selected Viewport" as the Active Play Mode and press play. Two blue hands will come up that allow you to simulate hand input in the editor. Learn more about the input simulation controls provided by the UX Tools plugin [here](https://microsoft.github.io/MixedReality-UXTools-Unreal/version/public/0.9.x/Docs/InputSimulation.html). 

* To stream the experience from a PC to a HoloLens 2 headset, follow the instructions for [streaming in Unreal](https://docs.microsoft.com/windows/mixed-reality/unreal-streaming).

* To package and deploy the app to a HoloLens 2 headset, follow the instructions for [deploying to device in Unreal](https://docs.microsoft.com/windows/mixed-reality/unreal-deploying).

## Key concepts

This sample is fully documented in our [Unreal tutorial series](https://docs.microsoft.com/windows/mixed-reality/develop/unreal/tutorials/unreal-uxt-ch1), which covers the following key concepts:
* Starting a new project
* Setting up for mixed reality
* Working with user input
* Adding buttons
* Packaging and deploying on a device or emulator

## Next steps

* [Mixed Reality development with Unreal](https://docs.microsoft.com/windows/mixed-reality/develop/unreal/unreal-development-overview)
* [MRTK for Unreal](https://github.com/microsoft/MixedRealityToolkit-Unreal)
* [UX Tools](https://github.com/microsoft/MixedReality-UXTools-Unreal)
* [Graphics Tools](https://github.com/microsoft/MixedReality-GraphicsTools-Unreal)