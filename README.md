# Aurora Drift

Aurora Drift is a fast-paced, neon-lit space survival game built with HTML, CSS, and JavaScript.

🎮 **Play Aurora Drift Online:** [Launch Game](https://philosopherscodez.github.io/Auroa-Drift/)

🛸 Aurora Drift – A Space Survival Arcade Game  
Aurora Drift is a fast-paced, neon-lit space survival game built with HTML, CSS, and JavaScript. Players pilot a glowing ship through an asteroid field, dodging threats, collecting power-ups, and unlocking upgrades at a futuristic station. With smooth controls, dynamic visuals, and a growing list of features, this game blends classic arcade reflexes with modern design.

---

## How to Play

- **Move:** Use **WASD** keys to move your ship.
- **Shoot:** Press **Spacebar** to shoot at asteroids and enemies.
- **Collect Power-Ups:** Grab shield and speed boost power-ups for special abilities.
- **Survive:** Avoid asteroids and enemy ships. Colliding without a shield ends your run.
- **Score:** Earn points by surviving, destroying asteroids/enemies, and collecting power-ups.
- **Secret:** Collect both Shield and Boost at the same time to unlock **SUPER MEGA ULTRA BOOST**!

Additional input methods

- **Mouse (desktop / laptop):** Move your mouse over the game canvas to steer the ship toward the pointer. Click (or click & hold) to fire — a single click fires immediately, holding down fires continuously (subject to the game's shoot cooldown).
- **Touch (mobile / tablet):** Touch and drag on the canvas to steer. Tap to fire; tap-and-hold fires continuously. The touch control maps to the same movement/shoot logic as the keyboard, so gameplay and balance are preserved.

---

## Features

- WASD controls for fluid ship movement
- Randomized asteroid spawns and collision detection
- Live Points system for unlocking upgrades
- Upgrade Station with shields, speed boosts, EMPs, and more
- Start screen, score tracking, and game over logic
- Responsive design for browser play

---

## Coming Soon

- Enemy ships and boss battles
- Campaign mode with story progression
- Sound effects and background music
- Save system

---

Changelog (recent)

- Added pointer controls (mouse & touch) so the game can be played with a mouse on desktop and by touch on phones/tablets. Pointer input maps to WASD internally and sets shooting on pointer/touch down. Small dead-zone prevents jitter near the ship. 

Testing locally

1. Open `index.html` in your browser (double-click or use your editor's "Open in Browser").
2. For a better local test (recommended), serve the folder with a simple static server. From PowerShell in the project folder run:

```powershell
# Python 3 built-in server (works if Python is installed)
python -m http.server 8000

# Then open http://localhost:8000 in your browser (desktop) or on your phone via your machine's LAN IP.
```

If you'd like a virtual joystick UI for handheld play (separate left thumb for movement and right for shooting), I can add that as a follow-up.
