# 🕹️ Console Games Collection

A curated collection of standalone HTML5, Canvas, and Web Audio games designed for arcade controllers, gamepads, keyboards, and mobile touchscreens. Every game is self-contained in a single executable file with zero installation required.

---

## 🎮 Playable Games

### 1. 🎈 [Baby JoyPop — Sensory Playground](./joypop/README.md)
A gentle, calming audiovisual sensory experience tailored for babies, toddlers, and relaxation. Features gamepad/joystick controls, multi-touch popping, procedural pentatonic lullabies, and adaptive sensory soothing.

- 🔗 **Instant Play**: [Launch JoyPop via raw.githack](https://raw.githack.com/Ajeet-Ganga/console-games/main/joypop/baby_joypop_sensory_playground.html)
- 📖 **Documentation**: [JoyPop README](./joypop/README.md)

```text
https://raw.githack.com/Ajeet-Ganga/console-games/main/joypop/baby_joypop_sensory_playground.html
```

---

### 2. 🪂 Paratrooper (PTP) Tactical Defense
A tactical retro arcade defense game inspired by classic artillery defense combat. Defend your base against enemy aircraft, paratroopers, and bombers with high-powered cannons, custom upgrades, and CRT aesthetic shaders.

- 🔗 **Instant Play**: [Launch Paratrooper via raw.githack](https://raw.githack.com/Ajeet-Ganga/console-games/main/paratrooper_tactical_defense.html)
- 🖼️ **Screenshot**:
  
  ![Paratrooper Tactical Defense Screenshot](./ptp%20screenshot.jpg)

```text
https://raw.githack.com/Ajeet-Ganga/console-games/main/paratrooper_tactical_defense.html
```

---

## ⚡ How raw.githack Works for Instant Gameplay

GitHub's default raw file server (`raw.githubusercontent.com`) serves HTML files with a `Content-Type: text/plain` header for security. Consequently, browsers show the plain source code instead of running the game.

**[raw.githack.com](https://raw.githack.com)** solves this by acting as a lightweight CDN gateway:
- It pulls the latest version directly from GitHub's `main` branch.
- It detects `.html` files and automatically delivers them with the proper `Content-Type: text/html` header and caching rules.
- Anyone can click the link and immediately play the game in full screen on any device without installing software or running a local server.

---

## 💻 Running Offline / Locally

All games are fully self-contained single-page applications.

1. Clone this repository:
   ```bash
   git clone https://github.com/Ajeet-Ganga/console-games.git
   cd console-games
   ```

2. Open either game in your web browser:
   ```bash
   # Open JoyPop
   open joypop/baby_joypop_sensory_playground.html

   # Open Paratrooper Defense
   open paratrooper_tactical_defense.html
   ```

3. (Optional) Run via a local HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
