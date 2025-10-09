# 🎮 EduRPG: The Ultimate Learning Adventure

> **A Notion-based RPG that turns studying into a game.**  
> Track XP by completing quests, take damage from failed challenges, and unlock new chapters as you master topics.

![EduRPG demo](docs/screenshots/demo.gif)

---

## 🌟 Overview

EduRPG transforms your study routine into a role-playing adventure.  
Built entirely inside **Notion**, this system gamifies learning — perfect for anyone pursuing certifications like CompTIA Network+, AWS, or Cybersecurity.

### 🧠 Key Features
- **Character Sheet** – HP hearts, XP bar, equipped items, level system.  
- **Story Chapters** – Unlock new story arcs as you complete objectives.  
- **Dice Mechanics** – Roll d20 to determine success or failure in scenes.  
- **Inventory System** – Equip items that boost stats or give new abilities.  
- **Quest Log** – Earn XP from studying, labs, or course progress.  
- **Battle Log** – Automatic HP updates from damage, rest, or healing.  
- **Expandable World** – Build your own subjects (Cloud+, Security+, etc.).  

---

## 🧩 How It Works

Everything runs inside interconnected Notion databases:
| Database | Purpose |
|-----------|----------|
| **Character** | Tracks HP, XP, gold, equipped items |
| **Scenes** | Contains narrative text, DC, and hidden outcomes |
| **Chapters** | Groups scenes, manages unlock logic |
| **Inventory** | Manages items and equipment bonuses |
| **Quest Log** | Awards XP when real-life tasks are completed |
| **Battle Log** | Records damage/healing events |

---

## 🚀 Quick Start

1. **Duplicate the Template**  
   → [Notion Template Link](#) *(add your public Notion share link here)*

2. **Open the Dashboard**  
   - View your Character Card  
   - Roll dice for your current Scene  
   - Use buttons: *Take Damage*, *Use Potion*, *Claim XP*

3. **Import Sample Data (Optional)**  
   CSVs located in `/templates/csv/`  
   - `Scenes.csv`  
   - `Inventory.csv`  
   - `Chapters.csv`

4. **Play Through Chapter 1: The Networking Realm**  
   Study each topic, roll for success, and watch your XP rise!

---

## 🧙‍♀️ Behind the Scenes

This system was designed by **Tiana Coats** as part of her cloud and network engineering studies —  
built originally for **CompTIA Network+ (N10-009)**, later expanded into a general gamified study platform.

> *“I wanted to make studying feel like leveling up in an RPG —  
every exam objective became a story quest.”*

---

## 🛠️ Tech Stack
- 🗂️ **Notion** (databases, rollups, formulas)
- 🧮 **Notion formulas** (for HP, XP, DC, and progress)
- 🎲 **Manual or digital dice** for encounters
- 🧰 **GitHub Pages** (documentation hosting)
- 💡 **Markdown + Screenshots + GIFs**

---

## 🎥 Demo

Add your GIF in `/docs/screenshots/demo.gif` and reference it here:

![EduRPG demo](docs/screenshots/demo.gif)

> The clip shows rolling a d20, the Visible Text revealing success/failure, and HP updating automatically.

---

## 🏆 Roadmap
See [ROADMAP.md](ROADMAP.md) for planned features like:
- Achievements and Titles
- Random Encounters
- Status Effects (Burned, Inspired)
- Item Crafting System

---

## 🙌 Credits
Created by [**Tiana Coats**](https://www.linkedin.com/in/tianacoats/)  
Built with Notion and inspired by tabletop RPG mechanics.  
Not affiliated with CompTIA or Blizzard.

---

## 📜 License
MIT License — see [LICENSE](LICENSE)
