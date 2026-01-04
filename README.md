# 🏎️ Neon Runner - High Performance WebGL Game

![Three.js](https://img.shields.io/badge/Three.js-Black?style=for-the-badge&logo=three.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**Neon Runner** is a browser-based 3D infinite runner game built using **Three.js** and **WebGL**. It features a procedural environment, dynamic difficulty progression, and a resource management system (Nitro & Ammo).

The game is optimized for performance using **Object Pooling** and **Math Vector recycling** to ensure smooth 60 FPS gameplay on various devices.

## 🎮 Gameplay Features

* **Infinite Procedural World:** The track generates endlessly with increasing speed.
* **Dynamic Leveling System:** Difficulty scales automatically (Easy -> Medium -> Hard) as you survive.
* **Combat System:** Collect **Ammo Crates (Purple)** to shoot down obstacles using a raycasting system.
* **Nitro Boost Mechanics:** Collect **Nitro Tanks (Blue)** to activate a warp-speed boost with visual distortion effects.
* **High Score System:** Saves your best runs using LocalStorage.
* **Responsive UI:** Full HUD with ammo counters, nitro bars, and level notifications.

## 🕹️ Controls

| Key | Action |
| :--- | :--- |
| **⬅️ Left Arrow** | Move Left |
| **➡️ Right Arrow** | Move Right |
| **SPACE** | Fire Weapon (Costs 1 Ammo) |
| **SHIFT (Hold)** | Activate Nitro Boost |

## 🚀 How to Run (Local Installation)

Because this project uses **JavaScript ES6 Modules** to import Three.js, **you cannot simply double-click the `index.html` file**. Modern browsers block local file imports for security reasons (CORS policy).

You must use a **Local Server**. Choose one of the methods below:

### Method 1: VS Code (Recommended)
1.  Open the project folder in **Visual Studio Code**.
2.  Install the extension **"Live Server"** by Ritwick Dey.
3.  Right-click `index.html` and select **"Open with Live Server"**.

### Method 2: Python
If you have Python installed, run this command in your terminal inside the project folder:
```bash
# Python 3.x
python -m http.server
