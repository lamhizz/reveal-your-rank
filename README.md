# 🏰 Reveal Your Rank

You can try game here [Play the game](https://machupicchu.lt/game-demo/).

**Reveal Your Rank** is a browser-based tactical strategy game inspired by classic titles like *Stratego*. Players battle for control of the board by strategically positioning units, revealing ranks through combat, and capturing the opponent's castle.

This project is built using **HTML**, **Vanilla JavaScript**, and **Tailwind CSS**, with optional sprite customization for a pixel-art or emoji-based experience.

---

## 🎮 Game Overview

- **Modes:**  
   - *Reveal Your Rank*: Units reveal their identity upon attack. Frontline confrontations automatically trigger combat.  
   - *Stratego Mode*: Units stay hidden until combat; standard Stratego rules apply.

- **Victory Conditions:**  
   - Capture the opponent's Castle (🏰)  
   - Eliminate all movable enemy units  
   - Opponent has no valid moves  

- **Unit Types:**  
   - **Castle (🏰):** Your stronghold. Lose it, and the game is over.  
   - **Mine (💣):** Destroys attacking units, except Engineers.  
   - **Engineer (E):** Disarms Mines.  
   - **Scout (🐎):** Moves unlimited spaces in straight lines.  
   - **Knights (K1–K9):** Tiered combat units.  
   - **Mortir (M10):** Highest-ranking movable unit.  
   - **Water (🌊):** Impassable terrain.  

- **Customization:**  
   - Change sprites via built-in presets or provide your own URLs.  
   - Adjust army compositions (with limits).  
   - AI difficulty and simulation speed settings.

---

## 🛠️ Features

✔️ Interactive 9x12 grid-based board  
✔️ Fully responsive design (desktop & mobile)  
✔️ AI opponent with scalable difficulty  
✔️ Simulation mode: Watch AI vs AI battles  
✔️ Visual highlights for valid moves, attacks, and last moves  
✔️ Frontline detection (Reveal mode only)  
✔️ Sound effects for combat, victory, and more  
✔️ Custom sprite support (pixel art or emojis)  
✔️ Army setup with real-time validation  
✔️ In-game tabs for status, setup, sprites, and references  
✔️ Debug tools and cheat modes for testing  

---

## 💻 Technologies Used

- **Vanilla JavaScript:** Game logic, AI behavior, UI rendering  
- **Tailwind CSS:** Layout and responsive design  
- **HTML5:** Structure and accessibility  
- **Google Fonts:** Retro-style monospace typography  
- **Sound Effects:** Basic audio feedback (customizable)  

---

## 💻 Getting Started

### Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/reveal-your-rank.git
   cd reveal-your-rank
   ```

2. Open `index.html` in your browser:
   ```bash
   open index.html
   ```
   *(Or drag it to your browser window)*

**No server required**, it's a pure client-side project.

---

## 🖼️ Sprite Customization

Three sprite options:

- **Default:** Emoji-based board  
- **Machu Picchu Theme:** Pixel art assets hosted externally  
- **Custom URLs:** Provide your own sprites via direct links  

You can customize:
- Unit images (Castle, Knight levels, Scout, etc.)  
- Terrain (Grass, Water)  
- Special effects (Fire, Victory images)  

---

## 🎯 Controls & Hotkeys

| Action           | Key/Button           |
|-----------------|---------------------|
| Select Unit     | Click on unit        |
| Move/Attack     | Click valid cell     |
| Deselect Unit   | Click elsewhere      |
| Toggle Cheat Mode | `C` key           |
| Show Sound Info | `S` key             |
| Start New Game  | "New Game" button   |
| Start/Stop Simulation | "Simulate" button |
| Get AI Advice   | "Get Advice ✨" button |
| Debug Menu      | "D" button          |

---

## 🧰 Project Structure

```
index.html          # Main HTML structure, embedded styles and scripts
assets/             # (Optional) Folder for hosting custom sprite images
README.md           # This documentation
```

*Note:* All logic and styles are embedded in `index.html` for simplicity.

---

## 🔧 Future Improvements

- Multiplayer support  
- Smarter AI with advanced decision trees  
- Save/load games  
- Expanded unit types  
- Improved mobile UI  

---

## 📌 License

This project is open-source under the [MIT License](LICENSE).

---

## ❤️ Credits

- Inspired by *Stratego*  
- Sounds and pixel art by [Machupicchu.lt](https://machupicchu.lt)  
- Developed with love for strategy games  

---

**Enjoy conquering the battlefield!** 🏰⚔️🐎
