# FPS Game in Unreal Engine 5

## Overview

This repository contains a first-person shooter (FPS) game developed in Unreal Engine 5. The project demonstrates core FPS mechanics, user experience (UX) improvements, and modular blueprint design. It is intended for both learning and demonstration purposes.

---

## How to Get Started

1. **Clone or Download the Repository**
   - Click the green `Code` button and select `Download ZIP`, or use:
     ```
     git clone https://github.com/Abhijeet-Singh-MUN/FPS-Game-in-Unreal-Engine-5.git
     ```

2. **Open the Project in Unreal Engine 5**
   - Launch Unreal Engine 5.
   - Open the `FPS Game.uproject` file located in the root directory.

3. **Play the Game**
   - Press the Play button in the Unreal Editor to start the game.
   - Explore the mechanics, shoot targets, and test the scoring and game flow.

---

## FPS Game in Unreal Engine 5

Built a modular and immersive **first-person shooter (FPS)** in Unreal Engine 5, focused on realistic physics, clean Blueprint architecture, and responsive user experience. The project features a custom weapon system, destructible environments, and an interactive UI/UX layer, all optimized for gameplay clarity and maintainability.

---

### Core Gameplay Systems

- **Custom Weapon System:**  
  Engineered a sniper rifle (`BP_Rifle`) with an ArrowComponent for precise projectile trajectory control.

- **Projectile Mechanics:**  
  Created `BP_Bullet` with adjusted mesh, velocity, and tracer glow using emissive materials for visual feedback.

- **Combat Feedback:**  
  Added recoil via asset montages, muzzle smoke, and impact sparks to heighten immersion.

---

### Environmental Interactions

- **Destructible Targets:**  
  Used Geometry Collection and Chaos Physics to build targets that fracture on valid projectile hits.

- **Impact Logic:**  
  Applied collision boxes and conditions to ensure accurate, physics-driven destruction.

---

### UI and Game Flow

- **UI Design:**  
  Built `WBP_UI` and `WBP_EndScreen` for score tracking, game states, and restarts with visual clarity (including background blur).

- **Crosshair Integration:**  
  Added a custom crosshair through `BP_FirstPersonHUD` to enhance aiming precision.

- **Modular GameMode:**  
  Structured logic into reusable functions like `ShowEndScreen` for scalable game flow.

- **Game Loop Control:**  
  Managed game-over states using timers and restart logic tied to UI buttons.

---

### Testing and Debugging

- **UX Optimization:**  
  Resolved issues like overlapping game states and missing HUD elements through targeted debugging and user playtesting.

---

### Tools & Technologies

Unreal Engine 5 · Blueprint Scripting · Chaos Physics · Geometry Collection · UMG · Material & Particle Systems

---

## Project Details

- **Gameplay Video:**  
  To watch a demonstration of the game, download the raw video file (`Gameplay video 1.mp4`) directly from the repository's file list.  
 
##  [Watch the gameplay video by downloading the raw video file "Gameplay video 1.mp4" by clicking on it, then download/view raw ]


- **UX and Design Documentation:**  
  For a comprehensive explanation of the game's features, UX improvements, design decisions, and blueprint structure, download and read the [`Game details.docx`](Game details.docx) file from the repository.

---

## Key Features

- Immediate weapon access and improved gun mechanics
- Enhanced projectile visuals and effects (tracer, sparks, smoke)
- Responsive recoil and shooting feedback
- Breakable targets with physics-based fracture
- Score tracking and end-game conditions (win/loss, restart)
- Custom crosshair and bullet drop mechanics
- Modular blueprints for maintainability
- Detailed UX justifications and playtesting feedback

---

## Requirements

- **Unreal Engine 5** (latest version recommended)
- Windows 10/11 (or compatible OS for UE5)

---

## Credits

- Assets and some bug fixes inspired by Unreal Sensei (YouTube)
- Additional troubleshooting and learning with ChatGPT and UE5 documentation

---

## License

This project is provided for educational and demonstration purposes. 

