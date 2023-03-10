# This is no longer being updated! Visit the rewritten version here: [https://github.com/Ravbug/TanksUnreal](https://github.com/Ravbug/TanksUnreal)

![Screenshot of the game](https://i.imgur.com/ozpnjEZ.png)

## About
This repository contains my remake of the [Unity Tanks! Tutorial game](https://unity3d.com/learn/tutorials/s/tanks-tutorial) in [Unreal Engine 4](https://www.unrealengine.com/), the engine behind the popular game [Fortnite](http://fortnite.com/). 
I am writing the game predominantly in C++, using blueprint subclassing where it's easier. My goal is to learn Unreal Engine C++ and provide a sample game for people looking to compare Unreal and Unity.

## Requirements:
Software
1. Engine: [Unreal Engine 4.22](https://www.unrealengine.com/en-US/eulacheck?state=https%3A%2F%2Fwww.unrealengine.com%2Fen-US%2Ffeed&studio=false) or newer
2. IDE: [Microsoft Visual Studio Community 2017](https://visualstudio.microsoft.com/) or [Xcode](https://developer.apple.com/xcode/) 

Hardware
1. A decent discrete GPU and quad core CPU
2. At least 15GB of disk space (for engine and IDE)
3. At least 4GB of RAM

## Compiling it yourself
1. Ensure you have the software listed above installed on your computer.
2. Download this repository as a zip (faster than cloning)
3. Unzip the archive
### Editor only
4. Open the `.uproject` and compile now if it asks
5. Play! 
### From IDE
4. Right-click the `.uproject` file in the Finder/File Explorer and press `Generate Xcode/Visual Studio Project`
   - If this option is not visible, open the `.uproject` and go to `File->Generate Xcode/Visual Studio Project`
5. Press the Compile and Run button in your IDE (CMD+R in Xcode, green Run button in VS)
6. Play!

## Issues
If you find an issue, use the [Issues](https://github.com/Ravbug/TanksUE4/issues) section of this repository to report it. Be sure to include specifically what the issue is, as well as what you've done to try to fix it. The more information you include, the better. However, I may not be able to fix it quickly.

## To Do
My list of tasks for this project, semi sorted by importance:
Goal is to reach parity with the Unity game, and perhaps extend on it.
- [x] Add unified tank controller class
- [x] Tank recoloring and spawnpoint customization
- [x] Tank knockback when hit
- [x] Variable damage based on distance to bullet
- [x] Detect end of game and which tanks to track
- [x] Spawn tanks on level load
- [x] Track wins (configurable rounds needed to win game)
- [x] Text to display round number and scoreboard
- [x] Display tank health in-game (Billboard?)
- [x] Smooth tank acceleration and deceleration when controlled
- [x] Smooth camera acceleration and deceleration 
- [x] Camera rotation (feature removed, caused too many problems)
- [x] Dynamic camera zooming
- [x] fix zooming and rotating to avoid cutting off tanks
- [x] Multiple round support (reset tanks after a delay)
- [x] Convert the multiple arrays used for setup into a single array (like the Unity game) for easier and more idiot-proof config
- [x] Bullet particles and lighting
- [x] Explosions effect
- [x] Sounds (use Unity assets)
- [x] music (use Unity assets)
- [x] Build the arena
- [x] Tank engine idle and driving sounds
- [x] Make game framerate independent
- [x] Tank AI: Pathfinding
- [x] Tank AI: Shooting (and not shooting when behind a wall - use a trigger collider for this)
- [x] Tank AI: Choosing targets (and aiming turret)
- [x] Fix derpy spinning AI
- [ ] ~~Game controller support~~
- [ ] ~~Mobile touch support~~
- [ ] ~~Experiment with deployment~~
- [ ] ~~Maybe: Land mines~~
- [ ] ~~Maybe: Time of day~~
