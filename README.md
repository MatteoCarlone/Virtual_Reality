# Virtual_Reality
Unreal Engine simulator for Drones autonomous landing on mobile platforms

### Link for oneDrive:
click here:

<a href="https://unigeit-my.sharepoint.com/:f:/r/personal/s5322242_studenti_unige_it/Documents/VR_project/TestDroneProject?csf=1&web=1&e=EcNYz3" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Microsoft_Office_OneDrive_%282019%E2%80%93present%29.svg" alt="c" width="40" height="40"/> </a>


### Link for Overleaf:
click here:

<a href="https://it.overleaf.com/read/gdyzfzgpxdkw" target="_blank"> <img src="https://images.ctfassets.net/nrgyaltdicpt/h9dpHuVys19B1sOAWvbP6/5f8d4c6d051f63e4ba450befd56f9189/ologo_square_colour_light_bg.svg" alt="c" width="40" height="40"/> </a>

## Installation and Running

To start the drone simulation, run the executable file `TestDroneProject` located in the `PrusaApp` folder.
A remote control (RC) controller is required to operate the drone within the simulation. 
To use default settings, place the `AirSim` folder into your `Documents` folder.

## Installation of Unreal Engine and Requirements
The Unreal Engine can be installed by following these steps:
1. Download the Epic Games Launcher from the official website and register.
2. Open the Unreal Engine tab in the Epic Games Launcher.
3. Click on the Install button and select Unreal Engine >= 4.27.
4. Choose the location for the installation.
5. If multiple versions of Unreal Engine are installed, make sure the desired version is set as the current version.

Before installing Unreal Engine, make sure to meet the following requirements:
- Visual Studio 2022
- Windows 10 SDK 10.0.19041 (selected by default during Visual Studio installation)
- Latest .NET Framework SDK (selected under the "Individual Components" tab during Visual Studio installation)

## Installation of AirSim Colosseum and Components
To install AirSim Colosseum, follow these steps:
1. Start the Developer Command Prompt for Visual Studio 2022.
2. Clone the repository: "git clone https://github.com/CodexLabsLLC/Colosseum.git".
3. Change to the AirSim directory by running "cd Colosseum".
4. Run "build.cmd" from the command line to build AirSim Colosseum.

Note: Installing AirSim Colosseum in the C drive is not recommended, as it may cause scripts to fail and requires running Visual Studio in Admin mode. It is recommended to clone the repository in a different drive, such as D or E.

## Python Interface
The project includes a Python interface that allows the user to interact with the simulation. The interface enables the user to:
- Enable and disable the RC (Joystick)
- Set wind disturbance
- Perform automatic takeoff
- Perform automatic landing

Additionally, the simulation displays real-time plots of the drone's altitude and orientation (in terms of roll, pitch, and yaw) in the world.

## Running the Python Script

To run the python User Interface, go into the folder `PrusaProject/TestDroneProject/PythonScripts` and run `python MultiRotorUI.py`.
