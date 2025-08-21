# Space-Defender-Game


A tiny, neon-soaked space shooter built as a single HTML file. Fast to load, easy to hack, and loud with pixel-less bravado — perfect for prototyping, learning, or convincing a friend you made an 8-bit masterpiece (without lying too hard).

This repo contains a complete, playable prototype: movement, shooting, enemies, particle explosions, score/lives UI, and a simple game-over / restart flow. It’s intentionally compact so you can read the whole thing, understand it, and extend it in an afternoon.

---

# Features

* Single-file HTML + JavaScript prototype — drop it in a browser and play.
* Smooth keyboard controls (WASD / Arrow keys), Spacebar to shoot.
* Enemy spawning with basic AI and enemy bullets.
* Collision detection, scoring, lives, and game over screen.
* Particle effects for explosions and hits.
* Retro neon UI and minimalist visual styling (CSS + canvas glow).
* Lightweight and easy to modify — a great learning base.

---

# Why this exists (a tiny philosophical aside)

Games are thought experiments in motion — small worlds where choices matter because the rules are simple and consequences are immediate. This project is a sandbox: change a number, discover a feel. If you want a lesson in how tiny code produces emergent play, this is your Petri dish.

---

# Controls

* Move: `W` / `A` / `S` / `D` or Arrow keys
* Shoot: `Spacebar`
* Restart (after game over): Click **Play Again** button

---

# How to run

Two simple options:

1. Open the file directly:

   * Double-click the HTML file (modern browsers should run it).
   * *Note:* some browser features perform best when served from a simple webserver.

2. Serve with a local webserver (recommended):

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000/ in your browser
```

---

# File structure (suggested repo layout)

```
/ (repo root)
├─ index.html        # the single-file prototype (provided)
├─ README.md         # this file
└─ assets/           # (optional) sprites, audio, models if you add them later
```

---

# Ideas for next steps (pick one, and I’ll help)

* Add persistent high score (localStorage).
* Introduce power-ups (spread shot, shield, extra life).
* Create boss waves with pattern-based bullets.
* Add sound and music (WebAudio / asset files).
* Make mobile-friendly touch controls & responsive canvas.
* Refactor into modular JS + asset pipeline (webpack / esbuild) for bigger features.

My strong opinion: add a single, memorable boss pattern before spending time on shaders — gameplay first, prettiness second.

---

# Contributing

This project is tiny and intentionally simple. Fork it, tinker with it, and send a PR if you:

* fix a bug,
* add a small mechanic (power-up, enemy type),
* or improve code readability and comments.

Please keep pull requests focused and atomic.

---

If you want, I’ll generate a ready-to-copy `README.md` file, add a `LICENSE` block, or convert the prototype into a tiny repo with modules, build scripts, and example assets. Which route do you want — pretty visuals, more mechanics, or a tidy dev repo?
