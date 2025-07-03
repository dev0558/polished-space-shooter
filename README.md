# 🎮 Polished Space Shooter  
**A retro-inspired space shooter built with Python & Pygame** featuring a parallax starfield, power-ups, enemy wave patterns, and persistent high-scores.

---

## 🚀 Live Demo  
*Coming soon!*  
*(You can embed a GIF or video here once ready.)*

---

## 🎯 Features
- **Parallax starfield** background for depth and atmosphere  
- **Menu navigation** with hoverable buttons (Start / Restart)  
- **Enemy waves** that spawn in increasing difficulty  
- **Power-ups**:  
  - 🛡️ Shield boost (restores player health)  
  - 🔫 Multi-shot (fires more bullets per shot)  
- **HUD elements**: Score, High Score, Shield Bar  
- **Persistent high-score** saved via `scores.json`  
- Clean **object‑oriented design**, using `pygame.sprite.Group`

---

## 💾 Installation

**Prerequisites:**
- Python 3.10+  
- Pygame  

```bash
pip install pygame

git clone https://github.com/yourusername/polished-space-shooter.git
cd polished-space-shooter
python main.py

##Project Structure
polished-space-shooter/
├── main.py           # Main script with all game logic
├── scores.json       # High-score storage (auto-generated)
├── assets/           # *(Optional)* for future images/sounds
│   ├── player.png
│   ├── enemy.png
│   └── ...
└── README.md

