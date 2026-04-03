# PhoenixEngine 🔥

🚧 **This project is currently in active development. Features are incomplete and subject to change.** 🚧  

**Mobile-first game engine for iOS, built with C++ (Core), Swift (Platform Layer), and Lua (Scripting).**  

---

## 📌 Overview

PhoenixEngine is a **high-performance, modular game engine** designed for mobile devices.  
It supports **2D/3D rendering**, **ECS-based game logic**, **physics simulation**, and **hot-reload Lua scripting**.  

**Key Features:**
- Metal-based rendering (2D & 3D)  
- ECS Framework (Entity-Component-System architecture)  
- Physics engine with rigid bodies and collision detection  
- Lua scripting for gameplay logic  
- Asynchronous asset pipeline for textures, models, and audio  
- Hot-reload for scripts and assets  

**Current Status:** `v0.1.0-alpha`  
- Core systems: ✅  
- ECS framework: ✅  
- Metal Renderer: ✅  
- Physics Engine: 🚧 In Progress  
- Level Editor: 🔜 Planned  
- Public Beta Release: 🔜 Planned  

---

## 🗂 Repository Structure

```text
PhoenixEngine/
│
├─ Core/                  # Engine core systems
│   ├─ ECS/               # Entity Component System
│   ├─ Rendering/         # Metal-based rendering
│   ├─ Physics/           # Physics engine & collision
│   ├─ Audio/             # Audio systems
│   └─ Assets/            # Asset management
│
├─ PlatformLayer/         # iOS-specific bridge (Swift)
│   ├─ Input/             # Touch & sensor handling
│   ├─ Audio/             # Platform audio wrappers
│   └─ FileIO/            # File I/O and storage
│
├─ Scripts/               # Lua scripting for gameplay
├─ Tools/                 # Level editor, debug utilities
├─ Docs/                  # Documentation & diagrams
├─ Examples/              # Sample scenes and projects
└─ README.md              # This file
