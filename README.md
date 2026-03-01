# 🌋 Under the Surface

> *An underground lava tunnel endless runner — built completely from scratch in Godot 4.*
---

I made this game as my first Godot project during a hackathon. The idea was simple — build a runner game set deep underground where lava is everywhere and rocks are trying to kill you. What made it interesting is that I built everything using only basic shapes and code. No downloaded images, no sprite sheets, nothing like that. Every rock, every lava glow, every stalactite dripping from the ceiling — all made with ColorRect nodes and GDScript.

While everyone else at the hackathon used Unity, I picked up Godot 4 from zero and shipped a complete game in one session.

---

## 🎮 How to Play

Press **SPACE** to jump over obstacles. Collect yellow coins for bonus points. Survive as long as you can — the game gets faster every second. Press **R** to restart after Game Over.

---

## ✨ Features

- Pixel explorer character with helmet, visor, suit and boots
- Two obstacle types — cave rocks and glowing lava cracks
- Animated lava river at the bottom with bubbling effect
- Stalactites hanging from ceiling with dripping lava
- Flickering lava light atmosphere
- Scrolling ground pattern
- Screen shake on death
- Jump and death sounds generated purely through code
- Yellow coins that bob up and down
- Score increases over time
- Speed increases the longer you survive
- Start screen and Game Over screen

---

## 🛠️ Built With

- **Engine** — Godot 4
- **Language** — GDScript
- **Graphics** — ColorRect nodes only, zero external assets
- **Audio** — AudioStreamGenerator, zero audio files
- **Resolution** — 640 x 360

---

## 🚀 How to Run

1. Install [Godot 4](https://godotengine.org)
2. Clone or download this repository
3. Open Godot → Import Project → select the folder
4. Press **F5** to run
5. No extra setup needed

---

## 💡 What I Learned

- CharacterBody2D physics and gravity
- Spawning scenes dynamically at runtime
- AABB collision detection with Rect2
- Delta time for frame rate independent movement
- Generating sounds with sine wave math
- Screen shake with Camera2D offset
- Sine wave animations for bobbing and flickering
- Breaking a game into multiple reusable scenes

---

## 🗺️ Future Ideas

- High score that saves between sessions
- Double jump
- Moving lava ceiling that slowly drops
- Mobile touch controls
- Background music

---

## 📄 License

Feel free to use this to learn from. If you build something cool with it I'd love to see it!

---

*Made with Godot 4 — my first ever game 🎮🌋*
*Built during a hackathon in one session*
