# 🏆 Glass Scoreboard

![Version](https://img.shields.io/badge/version-1.0-blue.svg) ![License](https://img.shields.io/badge/license-MIT-green.svg) ![Size](https://img.shields.io/badge/size-Single%20File-orange)

A modern, visually stunning digital scoreboard designed for card games, board games, or any tabletop activity. Built with a beautiful **Dark Glassmorphism UI**, it handles score tracking, winning conditions, and data persistence automatically.

## ✨ Key Features

* **💎 Glassmorphism UI:** A sleek, modern interface with real-time blur effects and animations.
* **🎯 Auto-Win Condition:** Set a "Winning Score" (e.g., 50). The game automatically detects when a player reaches the target and triggers the celebration.
* **💾 Auto-Save:** Uses **LocalStorage**. You can close the browser tab and reopen it later—your players and scores will still be there.
* **↩️ Undo Functionality:** Made a mistake? The "Undo" button tracks your history and lets you revert score changes.
* **🎉 Celebration Mode:** Automatic emoji rain animation and overlay when a winner is crowned.
* **✏️ Editable Names:** Click directly on any player's name to rename them instantly.
* **📱 Responsive:** Works perfectly on Desktop, Tablets, and Mobile phones.

## 🚀 Live Demo

[**Click here to View Scoreboard**](https://forscore.netlify.app/)

## 🛠️ How to Use

1.  **Add Players:** Type a name and click "Add Player" (or press Enter).
2.  **Set Target (Optional):** Enter a number in "Set Winning Score". If a player hits this number, the game ends automatically.
3.  **Track Scores:** Use the **+1, +2, +3** or **-1** buttons to manage points.
    * *Rows flash Green for positive points and Red for negative.*
4.  **Edit Names:** Typo? Just click on the player's name text to edit it.
5.  **End Game:** Click "End Game" manually, or let the Auto-Win trigger.
6.  **New Game:** Resets all scores to 0 but keeps the player list so you can play another round instantly.

## 📦 Installation & Running

Unlike complex web apps, this project is **Zero-Dependency**.

### Option 1: Run Locally (Offline)
1.  Download the `index.html` file.
2.  Double-click it.
3.  It runs instantly in your browser. No server or internet required.

### Option 2: Host Online
1.  Upload `index.html` to GitHub.
2.  Enable **GitHub Pages** in Settings.
3.  Share the link with your friends for game night.

## 🔧 Technical Details

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6).
* **Storage:** Browser `localStorage` API for state persistence.
* **Styling:** CSS Custom Properties (Variables), Flexbox, Grid, and `backdrop-filter` for the glass effect.
* **Animation:** CSS Keyframes for flashing rows; JavaScript for the falling emoji particle system.

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Created by Shubham through vibe code*

