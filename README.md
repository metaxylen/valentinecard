# 💌 Valentine Card - Interactive Love Letter

An interactive, multi-stage Valentine's Day experience built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies — just love and code.

## ✨ Features

### 📧 Stage 1: The Envelope
A beautifully animated envelope with a heart seal. Click to open it and reveal what's inside.

### 🧩 Stage 2: The Puzzle
A 3x3 sliding puzzle challenge. Slide the tiles to complete the hidden image. Solve it to unlock the next surprise!

### 💕 Stage 3: The Question
The classic "Will you go to dinner with me?" card (in Turkish: *"Benimle yemeğe çıkar mısın?"*). The "No" button? Good luck catching it — it runs away! 😄

### 🌸 Stage 4: The Surprise
After saying yes, a magical "Want to see more?" prompt leads to a stunning night garden with:
- 🌺 Animated glowing flowers that bloom
- 🌙 A pulsing moon with emoji bursts
- 🌌 Aurora borealis effect
- ✨ Fireflies floating in the dark
- 🎮 A "Love Bar" mini-game with global leaderboard

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/metaxylen/valentine-card.git
   ```

2. Open `index.html` in your browser — that's it! No build tools needed.

3. Or deploy to GitHub Pages for a shareable link 💝

## 📁 Project Structure

```
valentine-card/
├── index.html        # Entry point — envelope + puzzle
├── card.html         # "Benimle yemeğe çıkar mısın?" card
├── flowers.html      # Magical night flowers animation
├── style.css         # Flower animation styles
├── script.js         # Flower animation & love bar game logic
├── puzzle-image.png  # Puzzle heart image
├── images/           # Puzzle tile images
│   ├── full-image.png
│   ├── tile-1.png
│   ├── tile-2.png
│   ├── ...
│   └── tile-9.png
└── README.md
```

## 🎯 Flow

```
💌 Envelope → 🧩 Puzzle → 💕 Dinner Question → 🌸 Flower Surprise
```

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Animations, gradients, glassmorphism, responsive design
- **Vanilla JavaScript** — Game logic, DOM manipulation, animations
- **No frameworks or libraries** — 100% vanilla

## 📱 Responsive

Fully responsive across all devices:
- 📱 Mobile (optimized animations for performance)
- 📲 Tablet
- 🖥️ Desktop

## 💡 Highlights

- **CSS-only flower animations** — No canvas or WebGL needed
- **Escaping "No" button** — Runs away on hover (desktop) or click (mobile)
- **Sliding puzzle** — Classic 3x3 tile puzzle with smooth interactions
- **Global leaderboard** — Love Bar game syncs scores via JSONBlob API
- **GPU-accelerated** — Uses `transform` and `will-change` for smooth 60fps

## 📄 License

Made with ❤️ — Feel free to fork and customize for your special someone!
