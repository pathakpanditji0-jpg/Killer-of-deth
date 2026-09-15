# ☠️ KILLER OF DETH

### 🍎 Fruit Location Finder

**KILLER OF DETH** is a clean Roblox Studio-compatible Fruit Location Finder UI designed to help detect and locate fruits in your game.

> ⚠️ **Note:** The displayed fruit timer is an **estimated countdown**, not an exact server-side spawn timer.

---

## ✨ Features

* 🍎 **Fruit Detection**

  * Detects supported fruits in `Workspace`
  * Shows the nearest detected fruit
  * Displays total fruits currently detected

* 📍 **Fruit Teleport**

  * Teleports the player's character to the nearest detected fruit

* 👁️ **Fruit ESP**

  * Displays fruit names above spawned fruits
  * Rare fruits are highlighted separately

* ⭐ **Rare Fruit Detection**

  * Highlights valuable/rare fruits such as:

    * Kitsune
    * Dragon West
    * Dragon East
    * Yeti
    * Gas
    * T-Rex
    * Leopard
    * Dough

* ⏱️ **Estimated Next Fruit**

  * Displays an estimated countdown
  * Timer resets when a new fruit is detected
  * Clearly marked as an estimate

* 🔎 **Manual Scan**

  * Quickly scans the current server for fruits

* 🔄 **Timer Reset**

  * Manually resets the estimated countdown

* 📦 **AutoStore Toggle**

  * UI toggle included for AutoStore functionality

* 🎨 **Premium UI**

  * Dark gaming-style interface
  * Red/black theme
  * `KILLER OF DETH` branding
  * Rounded panels
  * Hover effects
  * Draggable window

* ➖ **Minimize Button**

  * Collapse the main interface when you need more screen space

---

## 📋 Supported Fruits

The finder currently recognizes fruits including:

`Rocket` • `Spin` • `Ghost` • `Spring` • `Bomb` • `Spike` • `Smoke` • `Blade`

`Sand` • `Ice` • `Dark` • `Diamond` • `Light` • `Rubber` • `Barrier` • `Magma`

`Phoenix` • `Love` • `Spider` • `Sound` • `Buddha` • `Quake` • `Gravity` • `Control`

`T-Rex` • `Mammoth` • `Spirit` • `Venom` • `Shadow` • `Rumble` • `Portal` • `Blizzard`

`Dragon` • `Leopard` • `Dough` • `Dragon West` • `Dragon East` • `Kitsune`

`Gas` • `Flame` • `Yeti` • `Creation` • `Eagle`

---

# 🛠️ Installation

## Method 1 — Roblox Studio

1. Install and open **Roblox Studio**.
2. Open your Roblox experience/project.
3. Create a **LocalScript**.
4. Paste the contents of:

```text
FruitLocationFinder.lua
```

5. Place the LocalScript in an appropriate client-side location, such as:

```text
StarterPlayer
└── StarterPlayerScripts
    └── FruitLocationFinder
```

6. Press **Play**.
7. The **KILLER OF DETH** interface should appear on screen.

---

## 🎮 Controls

| Button         | Function                    |
| -------------- | --------------------------- |
| 📍 TELEPORT    | Move to the nearest fruit   |
| 👁 ESP         | Toggle fruit ESP            |
| 📦 STORE       | Toggle AutoStore setting    |
| 🔎 SCAN FRUITS | Scan the current server     |
| 🔄 RESET TIMER | Reset estimated fruit timer |
| `—`            | Minimize the interface      |

---

## ⏱️ About the Fruit Timer

The timer shown in the interface is:

```text
Estimated Next Fruit: 59:59
```

It is **not an exact server timer**.

The script resets the estimate when a new fruit is detected. Actual fruit spawning can differ depending on the game/server.

---

## 📁 Project Structure

```text
KILLER-OF-DETH/
│
├── README.md
├── FruitLocationFinder.lua
└── LICENSE
```

---

## 🔒 Privacy

This project does **not intentionally send player information or fruit information to an external webhook**.

No external Discord webhook is required for the core UI and detection features.

---

## ⚠️ Disclaimer

This project is provided for **educational and Roblox Studio development purposes**.

Use it only in experiences/projects where you have permission to run or modify the code.

The author is not responsible for misuse of the project.

---

## ☠️ KILLER OF DETH

**Detect. Locate. Hunt.**

> 🍎 Find the fruit before someone else does.
