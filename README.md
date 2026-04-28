# 🏰 Bastion's Last Stand
### A Browser-Based Tower Defense Game

<img width="1889" height="886" alt="Screenshot 2026-04-29 073448" src="https://github.com/user-attachments/assets/aad0fc52-8651-4f32-a82c-a656808fca40" />
<img width="1888" height="887" alt="Screenshot 2026-04-29 073544" src="https://github.com/user-attachments/assets/d5e7865a-7c0b-44e6-aff7-46b6fb28b532" />
<img width="1881" height="900" alt="Screenshot 2026-04-29 073634" src="https://github.com/user-attachments/assets/595057bc-535a-483b-a6d3-6b66f5368237" />

> A fast-paced tower defense game built with vanilla HTML5 Canvas, CSS3, and JavaScript — no frameworks, no libraries, no installs. Just open and play.

---

## 🎮 Live Demo

🔗 **[Play the Game](https://christianpaeanylaibisquera.github.io/My_Team_Repo_Bisquera_Hau/)**  
🌐 **[Visit the Website](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**

> ⚠️ Replace `YOUR-USERNAME` and `YOUR-REPO-NAME` with your actual GitHub username and repository name after deploying to GitHub Pages.

---

## 📸 Screenshots

> _Add screenshots here after taking them. You can drag and drop images directly into the GitHub README editor._

| Start Menu | Gameplay | Game Over |
|------------|----------|-----------|
| _(screenshot)_ | _(screenshot)_ | _(screenshot)_ |

---

## 📖 About the Project

**Bastion's Last Stand** is a 1-level tower defense game developed as a 14-day sprint project for a 2nd Year IT Game Development course. Two students collaborated using GitHub, splitting the work into clearly defined roles:

- **Christian** handled all game logic — enemy AI, wave system, towers, projectiles, and the core game loop.
- **Marc** handled all UI/UX — HTML structure, CSS styling, the start menu, HUD, game over screen, and the website portal.

The game runs entirely in the browser using the HTML5 Canvas API with no external dependencies.

---

## ✨ Features

- 🗺️ **Custom Map** — Hand-crafted winding path with directional arrows
- 🌊 **15 Escalating Waves** — Difficulty scales with each wave
- 🗼 **5 Tower Types** — Basic, Cannon (AoE), Sniper, Freeze, Laser
- 👾 **6 Enemy Types** — Basic, Fast, Tank, Armored, Swarm, Boss
- ⬆️ **Upgrade System** — Upgrade towers up to Level 3
- 💸 **Sell System** — Sell towers for 60% of their total cost
- 💰 **Economy** — Gold rewards, wave-clear bonuses
- ⭐ **Scoring System** — Score tracked per kill and wave
- ⚡ **Speed Control** — 1×, 2×, 3× game speed
- 💥 **Particle Effects** — Death explosions and floating damage numbers
- 🎯 **Tower Info Panel** — Live stats display for selected towers
- 🏆 **Victory & Game Over Screens** — Full end-game stats summary

---

## 🗼 Tower Reference

| Tower | Cost | Damage | Range | Special |
|-------|------|--------|-------|---------|
| 🗼 Basic | 💰 50 | 15 | 120 | Reliable all-rounder |
| 💣 Cannon | 💰 100 | 40 | 100 | Area-of-effect splash |
| 🎯 Sniper | 💰 120 | 80 | 200 | Long range, high damage |
| ❄️ Freeze | 💰 90 | 5 | 110 | Slows enemies by 55% |
| ⚡ Laser | 💰 130 | 8 | 130 | Rapid fire |

---

## 👾 Enemy Reference

| Enemy | HP | Speed | Reward | Notes |
|-------|----|-------|--------|-------|
| Basic | 80 | 1.0 | 💰 10 | Standard enemy |
| Fast | 50 | 2.2 | 💰 12 | Quick but fragile |
| Tank | 400 | 0.5 | 💰 30 | Slow and tough |
| Armored | 200 | 0.8 | 💰 20 | Balanced threat |
| Swarm | 40 | 1.5 | 💰 8 | Comes in large groups |
| Boss | 1500 | 0.6 | 💰 100 | Appears in late waves |

---

## 🕹️ Controls

| Action | How |
|--------|-----|
| Select a tower | Click a tower card in the right panel |
| Place a tower | Click any grey tile on the map |
| Deselect tower type | Right-click anywhere on the map |
| Select a placed tower | Click it on the map |
| Upgrade tower | Click the **Upgrade** button in the info panel |
| Sell tower | Click the **Sell** button in the info panel |
| Start next wave | Click **▶ Send Wave** in the top bar |
| Change game speed | Click **1×**, **2×**, or **3×** in the side panel |

---

## 📁 Project Structure

```
bastion-last-stand/
│
├── index.html                  # Game landing page (website portal)
├── team.html                   # Team page with student profiles
├── tower-defense-FULL.html     # ✅ The complete playable game
│
├── tower-defense-part1.html    # Marc's work — HTML structure & CSS
├── tower-defense-part2.html    # Christian's work — JavaScript game logic
│
└── README.md                   # This file
```

> `tower-defense-FULL.html` is the combined final product. The `part1` and `part2` files are kept in the repo to demonstrate individual contributions.

---

## 🚀 How to Run

### Option 1 — Play Online (GitHub Pages)
Click the **[Live Demo](#-live-demo)** link at the top of this README.

### Option 2 — Run Locally
1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   ```
2. Open `tower-defense-FULL.html` in any modern browser.
3. No server, no install, no dependencies needed.

---

## 🌐 Deploying to GitHub Pages

1. Push all files to your `main` branch
2. Go to your repo on GitHub → **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Select **`main`** branch and **`/ (root)`** folder
5. Click **Save** — your site will be live in a few minutes at:
   ```
   https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
   ```

---

## 👥 Team

| | Name | Role | GitHub |
|-|------|------|--------|
| 👾 | **Christian Paean Ylai F. Bisquera** | Game Logic & Systems | [@ChristianPaeanYlaiBisquera](https://github.com/ChristianPaeanYlaiBisquera) |
| 🎮 | **Marc Hau** | UI Design & Web Portal | [@hawitz](https://github.com/hawitz) |

### Responsibilities Breakdown

**Christian — Game Logic (`tower-defense-part2.html`)**
- Core game loop and HTML5 Canvas rendering engine
- Enemy AI, pathfinding, and wave spawn system
- Tower targeting, projectile, and AoE mechanics
- Upgrade/sell economy and scoring system
- Particle effects and floating damage numbers

**Marc — UI & Frontend (`tower-defense-part1.html`, `index.html`, `team.html`)**
- Full HTML structure and CSS design system
- Animated start menu, HUD, and game over screen
- Side panel — tower shop, tower info, wave status
- Game landing page and team page (website portal)
- Responsive layout and visual polish

---

## 🛠️ Built With

- **HTML5 Canvas API** — Game rendering
- **Vanilla JavaScript** — All game logic, no frameworks
- **CSS3** — Animations, transitions, and layout
- **Google Fonts** — Orbitron, Share Tech Mono
- **GitHub Pages** — Hosting and deployment

---

## 📋 Project Requirements Checklist

### Website ✅
- [x] Game Landing Page with title, instructions, and play/download links
- [x] Team Page with individual roles and GitHub profile links
- [x] Deployed on GitHub Pages

### Game ✅
- [x] Start / Menu Screen
- [x] Core Playable Mechanic (tower defense loop)
- [x] Score / Game Over Screen

### GitHub Collaboration ✅
- [x] Shared repository with both contributors
- [x] 5+ meaningful commits per student
- [x] Professional README with description, controls, and screenshots

---

## 📄 License

This project was created for educational purposes as part of a 2nd Year IT Game Development course.

© 2025 Christian Paean Ylai F. Bisquera & Marc Hau
