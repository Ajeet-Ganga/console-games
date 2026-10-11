# 🎈 Baby JoyPop — Sensory Playground

A gentle, soothing, interactive audiovisual playground designed for babies, toddlers, and relaxing sensory stimulation. Built entirely in modern HTML5, Canvas, and Web Audio API with zero external runtime dependencies.

---

## 🚀 Instant Gameplay via raw.githack (No Installation Required)

You can launch and play **Baby JoyPop** instantly on any browser, phone, tablet, or smart display using the direct **raw.githack** link:

👉 **[Play Baby JoyPop Live](https://raw.githack.com/Ajeet-Ganga/console-games/main/joypop/baby_joypop_sensory_playground.html)**

```text
https://raw.githack.com/Ajeet-Ganga/console-games/main/joypop/baby_joypop_sensory_playground.html
```

### 💡 How raw.githack Works
When you access raw files directly from GitHub (`raw.githubusercontent.com`), GitHub enforces a `Content-Type: text/plain` header for security, preventing the browser from executing HTML, JavaScript, and Canvas rendering.

**[raw.githack.com](https://raw.githack.com)** solves this by acting as a high-performance CDN gateway that:
1. Fetches the latest source file directly from the GitHub repository `main` branch.
2. Inspects the file type and delivers it with the proper `Content-Type: text/html` MIME type and CORS headers.
3. Allows the game to execute directly inside any browser sandbox with no web hosting, server setup, or build tools needed.

---

## ✨ Features

- **🎮 Universal Controls & Input Options**:
  - **Gamepad / Joystick**: Full plug-and-play support for standard USB and Bluetooth game controllers (Xbox, PlayStation, 8BitDo, generic arcade sticks). Move sticks or press buttons to pop bubbles and float emojis.
  - **Touch & Multi-Touch**: Designed for little hands—tapping or swiping anywhere on the screen creates bubbles, bursts of light, and musical notes.
  - **Mouse & Keyboard**: Click, drag, or press keyboard keys to interact. Press `Esc` to toggle Pause.
  - **Gyroscope & Device Tilt**: Tilt the tablet or mobile device to gently float sensory elements across the screen.

- **🎵 Soothing Procedural Soundscapes**:
  - Powered by the browser's native **Web Audio API** (no bulky audio downloads).
  - Four customizable melodic background themes:
    - *Dreamy Pentatonic (Warm Bells)*
    - *Twinkle Star (Celesta)*
    - *Cradle Song (Soft Chime)*
    - *Ocean Breeze & Chimes*
  - Interactive SFX tones: Harmonic Wooden Marimba, Gentle Music Box Bells, or Soft Popping Bubbles.

- **🌿 Toddler Sensory Soother (Auto-Desensitization)**:
  - Built-in adaptive calming algorithm that prevents sensory overload.
  - Gently moderates burst rates and flash intensity during rapid or continuous tapping sessions.

- **🎨 Themes & Visual Customization**:
  - Six preset palettes: *Pastel Sky*, *Cozy Stars*, *Sun Meadow*, *Gentle Sea*, *Sweet Pink*, and *Lavender*.
  - Upload custom family photos or baby pictures directly into the canvas background via the parent panel.
  - Selectable emoji sets: Cute Animals (🐶, 🐱, 🐼, 🐰), Toys & Sweets (🧸, 🎈, 🍭, 🚗), Celestial Sky (🌟, 🌙, ☀️, 🌈), or Rainbow Mix.

- **🧸 Parent Safety & Settings**:
  - Discreet parent settings modal (⚙️ icon) to adjust music volume (defaults to a safe 20%), tempo, particle rate limiters, visual density, and motion drift.
  - Auto-pause enabled when switching tabs or losing screen focus to prevent unexpected noises.

---

## 🕹️ Running Locally

If you prefer to run the game offline or develop locally:

1. Clone or download the repository:
   ```bash
   git clone https://github.com/Ajeet-Ganga/console-games.git
   cd console-games/joypop
   ```
2. Open `baby_joypop_sensory_playground.html` directly in your browser:
   ```bash
   # macOS
   open baby_joypop_sensory_playground.html

   # Linux
   xdg-open baby_joypop_sensory_playground.html

   # Or run a local Python HTTP server
   python3 -m http.server 8000
   ```
3. Tap anywhere or press a button on your connected controller to begin!
