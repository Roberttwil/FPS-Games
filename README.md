# 🎯 FPS Bottle Shooter - Unity 3D

## 📝 Project Description
This project is a 3D First-Person Shooter (FPS) game prototype built using the **Unity Engine**. The main focus of this project is to implement robust shooting mechanics and a physics system for a destructible environment. Players can use a weapon (M4A1) to shoot glass bottle targets that react realistically to bullet impacts.

## ✨ Key Features
* **Core Shooting Mechanics:** Implementation of accurate projectile physics/raycasting for the shooting system.
* **Destructible Objects:** Glass bottle targets that dynamically shatter into pieces upon bullet impact, utilizing Unity's physics engine.
* **Visual & Audio FX:** Includes realistic muzzle flash effects on the weapon barrel when shooting, particle systems for scattered glass shards, and synchronized shooting sound effects (SFX).
* **First-Person Controller:** Smooth and responsive camera and player movement tailored for FPS simulation.

## 🛠️ Tech Stack
* **Game Engine:** Unity (v6000.3.10f1 LTS)
* **Programming Language:** C#

## 🚀 How to Run the Project (Installation)

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/Roberttwil/FPS-Games.git](https://github.com/Roberttwil/FPS-Games.git)

```
2. This project utilizes Git Large File Storage (LFS) for 3D assets and textures. Ensure [Git LFS](https://git-lfs.com/) is installed, then run the following command inside the project directory to pull all the heavy assets:
```bash
git lfs pull

```
3. Open **Unity Hub**, click **Import project** (or Add -> Add project from disk), and select the cloned `FPS-Games` folder.
4. If prompted, allow Unity Hub to install the required Editor version (**6000.3.10f1 LTS**).
5. Once the project is successfully loaded, navigate to the *Project* window, open the `Assets/Scenes` folder, and double-click the main scene file (e.g., `SampleScene`).
6. Press the **Play** (▶) button at the top center of the Unity Editor to test the game.

