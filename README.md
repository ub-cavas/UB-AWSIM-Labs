# AWSIM Labs

<img src="docs/assets/images/E2ESim.png" height="300">

<img src="docs/assets/images/autoware-foundation.png" height="90"> <img src="docs/assets/images/awsim-labs-logo.png" height="90">

Main purpose of this fork is to develop the existing AWSIM-Labs environment to integrate new research from University at Buffalo on Gaussian Splatting, traffic simulation and collaborative sensing while also ensuring a high-performance simulation environment for the [Autoware](https://github.com/autowarefoundation/autoware).

This is a fork of [AWSIM Labs](https://github.com/autowarefoundation/AWSIM-Labs).

## Features

- Simulator components included (Vehicle, Sensor, Environment, ROS2, etc.)
- Support for Ubuntu 22.04 and windows 10/11
- ROS2 native communication
- Open source software
- Made with Unity Game Engine
- Multiple scene and vehicle setup
- Interactable simulation and UI

## Tutorial

First, try the packaged version!  
[AWSIM Labs Documentation - Quick Start Demo](https://autowarefoundation.github.io/AWSIM-Labs/main/GettingStarted/QuickStartDemo/)

Next, try running the project from source!
1. Clone this repo
2. Follow the config instructions in the Quick Start Demo
3. Install the [Unity HUB](https://unity.com/download) 
4. Install the following editor version [Unity 6000.0.36f1](https://unity.com/releases/editor/archive)
5. Open the project (it will ask to open in safe mode) **NOTE:** The Unity HUB must be launched via terminal (not GUI) to run the project without errors
6. Import the [Vehicle Physics Pro](https://autowarefoundation.github.io/AWSIM-Labs/main/DeveloperGuide/EditorSetup/VPPCommunityEdition/) and [Graphy](https://autowarefoundation.github.io/AWSIM-Labs/main/DeveloperGuide/EditorSetup/Graphy/) assets using the package manager
3. Unzip and import the Service Center Loop assets into Assets/AWSIM/Externals/ [Link to assets](https://buffalo.app.box.com/file/1786212759904)
4. Open the Service Center Loop Scene (Assets/AWSIM/Scenes/ServiceCenterLoop.unity)
5. Press Play to run the scene
    - NOTE: The Unity HUB must be launched via terminal (not GUI) to run the project without errors
6. Start autoware with the correct map: !!! TO DO - Add link to autoware map !!!

## Documentation

https://autowarefoundation.github.io/AWSIM-Labs/main/



## License

AWSIM License
Applies to `tier4/AWSIM` repositories and all content contained in the [Releases](https://github.com/autowarefoundation/AWSIM-Labs/releases).

- code : Apache 2.0
- assets : CC BY-NC

See also [LICENSE](./LICENSE)
