# 🌌 RealmExplorer

**RealmExplorer** is a 2D adventure and exploration game built with **Python** and **Pygame**.
The player can explore different environments, interact with NPCs, and fight enemies in real-time battles.
The project is in **early development**, aiming to become a full RPG experience over time.

---

## 🧭 Game Overview

* 🗣️ **NPC Interaction** — Talk to characters and uncover the world’s lore.
* ⚔️ **Battle System** — Engage in combat (currently in progress).
* 🌄 **Exploration** — Move freely through handcrafted or generated maps.
* 🧱 **Future Systems** — Quests, items, inventory, and progression.
* 🎨 **Style** — Simple 2D pixel-art inspired design.

---

## 🧩 Technologies Used

* **Language:** Python 3
* **Library:** Pygame
* **IDE Recommended:** VS Code or PyCharm
* **Version Control:** Git / GitHub

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/RealmExplorer.git
cd RealmExplorer
```

### 2️⃣ Install Dependencies

```bash
pip install pygame
```

### 3️⃣ Run the Game

```bash
python main.py
```

---

## 🧱 Development Setup

Your project structure should look like this:

```
RealmExplorer/
│
├── assets/
│   ├── images/        # Player, enemies, NPC sprites
│   ├── tiles/         # Environment tiles and maps
│   ├── sounds/        # Sound effects and music
│   └── fonts/         # Game fonts
│
├── scripts/
│   ├── player.py      # Player movement and actions
│   ├── npc.py         # NPC interaction and dialogue
│   ├── combat.py      # Battle logic
│   ├── world.py       # Map handling and transitions
│   └── ui.py          # Menu and HUD elements
│
├── main.py            # Game entry point
├── requirements.txt   # Python dependencies
└── README.md          # Project documentation
```

> 💡 You can adjust folder names or add modules as your project grows (for example, add a `save_load.py` or `inventory.py`).

---

## 🎮 Controls (Planned)

| Key               | Action          |
| ----------------- | --------------- |
| **W / A / S / D** | Move character  |
| **E**             | Interact / Talk |
| **SPACE**         | Attack          |
| **ESC**           | Pause / Menu    |

---

## 🧠 Roadmap

* [x] Create main game window and loop
* [ ] Add player movement and camera system
* [ ] Implement NPC dialogue
* [ ] Add combat mechanics
* [ ] Add map transitions and world zones
* [ ] Create save/load functionality

---

## 🤝 Contributing

Contributions are welcome!
To contribute:

1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🌟 Acknowledgments

* Inspired by classic RPGs and exploration games
* Built using the **Pygame** framework
* Created by **Richard Kóša**
