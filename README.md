# Semi Autonomus Drone Navigation

Introduction
=============

The simulation process involves creating a virtual environment using Unreal Engine 4.27 and the AirSim plugin, which provides a high-fidelity simulation of drone flight and sensor data collection. The environment includes various types of crops, terrain, and obstacles that the drone must navigate around. The simulation allows for the testing and validation of different drone sensors, including RGB and thermal cameras, LIDAR, and ultrasound sensors.

The simulation allows for testing and validation of drone-related algorithms and techniques, such as object detection, path planning, and data collection. It also enables the development of new features and applications that can be integrated into the drone's hardware and software. Additionally, the use of AI and machine learning algorithms in the simulation can improve the accuracy and efficiency of data collection and analysis.

<figure>
  <img src="https://user-images.githubusercontent.com/80394968/224868977-cf1cd102-3fbf-4de7-96cc-528c55794761.png" alt="Image 1">
</figure>
<p align="center">
  Drone farming environment
</p>

Requirments
===========

<img src="https://user-images.githubusercontent.com/80394968/224969515-c77bdfe8-f115-4f14-bb31-0ca5ce6cbf19.png" width="30" /> System 
-------

* Win OS 10 or 11 
* DirectX 11 compatible graphics card with 16 GB video RAM
* CPU with at least 4 cores
* SSD hard drive with at least 20 GB free space 

<img src="https://user-images.githubusercontent.com/80394968/224971035-f404cb16-4c9c-437e-b70d-61cad87f9847.png" width="25" /> Tools
-----
* Unreal Engine 4.27
* AirSim (new version)
* Open CV for Python
* Microsoft visual studio 22 
* Desktop Development with C++ & Developer Command Prompt for VS 2022
* NET Framework SDK (Windows 10 SDK 10.0.19041)

Installation
=============
* Install Epic game launcher & [Unreal Engine 4.27](https://docs.unrealengine.com/4.27/en-US/Basics/InstallingUnrealEngine/)
* Download [AirSim](https://microsoft.github.io/AirSim/) package 
* To download the project files, go to [Google Drive](https://drive.google.com/drive/folders/1HEl6NDDz8kOuERAFpLMrJWBNcjAKZSu_?usp=share_link) and look for a file called "Assignment VR". Inside, you'll find two zip folders and a script called "setting.json".

* The "Drone_VR" folder contains the Unreal Engine environment. Extract it into the ``Documents\Unreal Projects`` directory.

* The "Drone_shell" folder contains the main.cpp and Python scripts. Extract it into the AirSim folder you downloaded. Note that there's already a file named "Drone_shell" inside the AirSim package, so you'll need to replace it with the one from the project files. The program is written in C++, so you'll need to compile it before running it.
 
* After adding the Drone_shell file and extracting it, you can use the ``Developer Command Prompt VS22`` to navigate to the repository where you put the AirSim package. Then, you can call ``build.cmd`` to compile the program and generate the "Plugin" folder for Unreal Engine.
* Copy the "Drone_shell" file from the AirSim package and paste it into the ``Document\Unreal Project\Drone_VR`` folder.
* Copy the "Plugin" file from the "AirSim\Unreal" package and paste it into the ``Document\Unreal Project\Drone_VR`` folder. There may already be a "Plugins" folder inside the "Drone_VR" directory. Simply replace it with the new one from the AirSim package.
* Right-click on the ``Dorne_VR.uproject`` file in the Drone_VR folder and select `Generate Visual Studio project files` to perform the final compilation of the project with the newly added files.
* open the "Drone VR.sln" file and ensure that the configuration solution is set to "Debug Game Editor" and the solution platform is set to "Win64" and start the project. The initial compilation may take some time. If the Unreal environment does not open, try restarting the project.



Usage
=============

Video
=============

Members
=============
| Github-page | Email |
|------------------|------------------|
| [Mohammad Reza Haji Hosseini](https://github.com/mrhosseini75) | mrhhosseini75@gamil.com |
| Bouazza El Moutaouakli  | Row 2, Column 2 |
| Danial Sabzevari  | electrical.eng.ds@gmail.com |
| [Parinaz Ramezanpour](https://github.com/ParinazRmp)  | parinaz.ramezanpoor0@gmail.com |

