# College-Archives
A collection of source code and scripts from my college game development coursework (Unity, C#, &amp; Unreal).

*Note: As these are legacy projects, some files are preserved as standalone scripts rather than full project directories.*

## 📂 Repository Contents

### 1. 2D Roguelike Platformer (Unity)
**Context:** First Year Final Major Project.
A procedural platformer where the player navigates through randomly selected rooms, collecting power-ups and fighting enemies.

**Key Systems Implemented:**
* **Procedural Flow:** Implemented a system (`Door.cs`) to randomly load different room scenes to create a unique run every time.
* **Power-Up System:** Created a modular upgrade system (`StatUp.cs`) handling stats like Speed, Double Jump, Health, and "Bat Repellent".
* **Enemy AI:**
    * **Bats:** Proximity-based flying AI that chases the player (`BatMovement.cs`).
    * **Snakes:** Patrolling ground enemies (`SnakeMovement.cs`).
    * **Traps:** Raycast-based dart traps that fire when players cross their line of sight (`DartTrapRight.cs`, `DartTrapLeft.cs`).
* **State Management:** Utilised `PlayerPrefs` to persist high scores and room counts across scene loads (`RoomCounterUI.cs`).

### 2. Global Game Jam 2023 "Roots" (Unity)
**Context:** First Year Game Jam Entry.
A prototype featuring a snake-like following mechanic.

* **Snake AI:** A bespoke script (`Follow Player`) using `Vector3.Lerp` and Rigidbody constraints to create a smooth chase movement behavior for AI enemies.

---

### 🛠 Tech Stack
* **Languages:** C# (Unity API)
* **Engines:** Unity 2021/2022
