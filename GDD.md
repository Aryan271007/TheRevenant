# The Revenant

---

## 1. Game Overview
* **Genre:** 2D Singleplayer Platformer
* **Platform:** PC
* **Target Audience:** Casual Gamers (Age: 12+)
* **Game Summary:**
    > A challenging 2D platformer where the player must reach the end and defeat the boss in order to win.

---

## 2. Gameplay Mechanics

### Core Gameplay
* Player controls a character inside the game.
* The player must jump and reach the end of the map.
* The game ends when the player defeats the boss.

### Controls
| Action | Key Input |
| :--- | :--- |
| **Move Left / Right** | `A` / `D` |
| **Jump** | `Space` |
| **Attack** | `J` |
| **Pause** | `Esc` |

---

## 3. Combat & Enemy
* **Enemy:** A boss enemy that patrols and attacks the player.
* **Combat:** The player uses a sword to damage the boss.

---

## 4. Visual & Art Style
* **Visual Style:** Pixel aesthetic for a retro feel.
* **Theme:** *"Death is not the end"*

---

## 5. User Interface (UI/UX)
- **Main Menu**
    - Start Game
    - Exit
- **In-Game UI**
    - *Player HP Bar*: top left corner
    - *Boss HP Bar*: top Right Corner(visible when near to boss)
- **Pause Menu**
    - Accessed by esc 
    - Resume
    - Main Menu
    - Quit
- **Death Screen**
    - Respawn
    - Menu
- **Win Screen**
    - Main Menu
    - Quit
  
 ---
 ## 6. Level Design & Progression
 - **Level Structure**
   - *Handcrafted Dungeon*: A single, manually designed level divided into distinct zones.
 - **Difficulty Progression**
   - *First Phase*: jump to different platforms to progress.
   - *Second Phase*: Fight the Boss to win.

---
## 8. Technical Requirements
**Engine**: Unity

**Programming Language**: C#

**Physics System**: Unity 2D Physics 

**Target Platform**: Windows PC 

**Data Handling**: Session-based state management for Checkpoints.

---

## 9. Additional Features & Unique Additions

- **Particle Systems:** 
  - *Visual Feedback*: Custom particle effects play when the player dies, activates a checkpoint, or hits the Boss.

- **Dynamic Animations:**

    - *State Machine*: transitions between Idle, Run, Jump, and Attack animations for the player character.

  - *Enemy Animation:* The Boss has specific animation loops for patrolling and attacking.

- **Checkpoint System:**

    - *Persistence*: The game remembers the last activated checkpoint and respawns the player there, reinforcing the "Death is Not the End" theme.
  
---
## 10. Links & References
- **Repo:** [Aryan271007/TheRevenant](https://github.com/Aryan271007/TheRevenant)
- **Itch\.io:** [aryan27/TheRevenant](https://aryan27.itch.io/therevenant)
- **Drive:** [TheRevenant](https://drive.google.com/drive/folders/16HBOOPldI3ZFZ317G3koXlDlwiPZ81Ks?usp=drive_link)

---