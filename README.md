# 🦖 Dino Runner 🦖

A classic, pixel-art style endless runner game built with pure HTML, CSS, and JavaScript. Jump over obstacles, rack up a high score, unlock achievements, and discover new characters.

## ✨ Features

* **Endless Gameplay**: The game continues endlessly, with the speed and difficulty gradually increasing.
* **Scoring System**: Your score increases the longer you survive.
* **High Score & Leaderboard**: The game saves your all-time high score and a leaderboard of the top 10 scores locally in your browser.
* **Achievement System**: Unlock various achievements by reaching score milestones and completing in-game challenges.
    * 🏆 **Getting Started**: Reach 100 points.
    * 🏆 **Dino Master**: Reach 500 points.
    * 👑 **Dino Legend**: Reach 1000 points.
    * 💀 **First Fall**: Experience your first game over.
    * 🦘 **Jump Master**: Jump 50 times in a single game.
* **Unlockable Characters**: Meet certain criteria to unlock new playable characters with unique designs.
    * **Classic Dino**: Available by default.
    * **Raptor**: Unlocked by reaching a score of 500.
    * **Robot Dino**: Unlocked by earning all 5 achievements.
* **Dynamic Day/Night Cycle**: The background scenery transitions from day to night as your score increases.
* **Procedural Audio**: Sound effects for jumping, game over, and milestones are generated on-the-fly using the Web Audio API.
* **Retro Aesthetics**: Features crisp, pixelated graphics and a classic "Press Start 2P" font for a nostalgic feel.
* **Persistent Progress**: All your unlocked characters, achievements, and high scores are saved in your browser's `localStorage`.
* **Reset Progress**: An option is included to reset all saved game data.

## 🎮 How to Play

* **Start the game**: Select an unlocked character from the main menu and click the start button.
* **Jump**: Press the **SPACEBAR** to make your character jump over the cacti.
* **Restart**: After a game over, press the **SPACEBAR** to instantly play again.

## 🚀 Running Locally

No server or complex setup is needed!

1.  Make sure you have the `pixel_dino_game.html` file.
2.  Open the `pixel_dino_game.html` file directly in any modern web browser (like Chrome, Firefox, or Edge).
3.  Enjoy the game!

## 🛠️ Technical Details

* **Frontend**: The entire game is built using vanilla HTML, CSS, and JavaScript.
* **Graphics**: All character and obstacle graphics are rendered using inline SVG.
* **Audio**: The Web Audio API is used to programmatically generate all sound effects, avoiding the need for external audio files.
* **Data Persistence**: Game progress is saved using the browser's `localStorage` API.
* **Fonts**: Uses the 'Press Start 2P' font from Google Fonts.

## 📜 Credits

* This game was created by Jacob Graham.
