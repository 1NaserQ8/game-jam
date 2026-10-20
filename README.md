# 🎮 Game Jam – Kuwait University

A 3D third-person collectible game I made during the **Game Jam at Kuwait University**.

Built with **Unity 6** (`6000.5.2f1`), starting from Unity's *Get Started* 3D template.

## ✨ Features
- Third-person character controller (run, jump, camera follow)
- Floating, rotating collectible pickups with particle effects
- Collectible counter UI
- Player respawn system
- Motion-based audio

## 📂 Main Scripts
| Script | What it does |
|--------|--------------|
| [`ThirdPersonController.cs`](Assets/SourceFiles/Scripts/ThirdPersonController.cs) | Player movement and camera |
| [`Pickup.cs`](Assets/SourceFiles/Scripts/Pickup.cs) | Collectible rotation, bobbing and pickup effect |
| [`UpdateCollectibleCount.cs`](Assets/SourceFiles/Scripts/UpdateCollectibleCount.cs) | Updates the collectible counter |
| [`RespawnPlayer.cs`](Assets/SourceFiles/Scripts/RespawnPlayer.cs) | Respawns the player after falling |
| [`MotionAudioController.cs`](Assets/SourceFiles/Scripts/MotionAudioController.cs) | Plays audio based on movement |

## ▶️ How to Open
1. Install **Unity Hub** and Unity **6000.5.2f1**
2. Clone this repo (Git LFS is required: `git lfs install` first)
3. Open the folder in Unity Hub
4. Open `Assets/Scenes/GetStarted_Scene.unity` and press **Play**
