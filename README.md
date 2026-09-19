# 🐍 Classic Nokia Arcade Snake

A retro-inspired, responsive Snake arcade game that faithfully revives the iconic Nokia 3310 experience with modern web standards. Built entirely with pure HTML5 Canvas, modern CSS, and vanilla JavaScript in a single, zero-dependency file.

Playable seamlessly across **Desktop Computers** (keyboard controls) and **Smartphones** (full touch swipe gestures & dedicated tactile on-screen D-Pad).

---

## ✨ Features

- **Cross-Platform Playability:** Fully optimized for both desktop browsers and mobile touchscreens (e.g., iPhone, Samsung Galaxy S25 Ultra, and other Android devices).
- **Responsive Viewport:** Dynamic layout scaling ensures zero awkward horizontal scrolling, unwanted zoom, or screen overflow.
- **Nokia LCD Aesthetic:** Authentic monochrome dot-matrix green display complete with scanlines, pixel borders, and retro arcade typography.
- **Web Audio API Sound Effects:** Realistic 8-bit synthesized square-wave audio for movement, eating pellets, pausing, and collision crashes (no external `.mp3` files needed).
- **Mobile Haptic Feedback:** Vibrates on Android/touch devices upon eating pellets or hitting walls using the native Vibration API.
- **Persistent High Scores:** Tracks your all-time high score across browser sessions using `localStorage`.

---

## 🎮 Game Modes & Difficulties

Configure your playstyle directly from the pre-game setup menu:

- **Difficulty Speeds:**
  - **Easy:** Relaxed movement speed (ideal for casual practice).
  - **Medium:** Standard classic Nokia pacing.
  - **Hard:** Rapid tick speed for reflex testing.
- **Wall Rules:**
  - **Solid Walls (Snake I):** Hitting any border ends the run immediately.
  - **Wrap Around (Snake II):** Exiting through one screen edge wraps you back from the opposite side.

---

## 🕹️ Controls

### 💻 On Computer / Desktop
| Action | Key(s) |
| :--- | :--- |
| **Move / Steer** | Arrow Keys (`↑`, `↓`, `←`, `→`) or `W`, `A`, `S`, `D` |
| **Start / Restart** | `Enter` or `R` |
| **Pause / Resume** | `Space` or `P` |
| **Open Menu** | `Esc` |
| **Toggle Audio** | `M` |

*Includes an input buffer queue to prevent accidental 180° self-collisions during rapid keypresses.*

### 📱 On Smartphones / Touch Devices
- **Swipe Gestures:** Swipe directly anywhere on the green LCD screen (Up, Down, Left, Right) to steer.
- **Virtual D-Pad:** Tap the directional arrows on the on-screen control cluster below the board.
- **Arcade Touch Buttons:** Tap buttons directly to Start, Pause, adjust Difficulty, or toggle sound.

---

## 🚀 Live Demo & Deployment

This game is self-contained in a single `index.html` file and runs instantly via **GitHub Pages**:

1. Fork or push this repository to GitHub.
2. Go to **Settings > Pages**.
3. Under **Branch**, select `main` (or `master`), select root `/`, and click **Save**.
4. Open the generated GitHub Pages URL on your PC or smartphone browser to play immediately!

---

## 🛠️ Built With

- **HTML5 Canvas** – 2D grid rendering engine
- **Modern Vanilla JavaScript** – Game state loop, touch/keyboard input handling, and collision logic
- **Web Audio API** – Native 8-bit sound synthesis
- **Responsive CSS** – Adaptive viewport scaling and retro CRT styling
