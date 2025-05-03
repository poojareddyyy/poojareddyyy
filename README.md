# 🎮 Shadow Jumper

**Shadow Jumper** is a 2D vertical platformer game built using HTML5 Canvas and vanilla JavaScript. In this game, the player jumps across platforms while being chased by a shadow enemy. The objective is to stay ahead, climb higher, and set a new high score!

## 🚀 Features

- Smooth player movement with gravity and jumping physics  
- Procedural platform generation as the player climbs  
- Increasing difficulty with enemy speed scaling  
- High score persistence using `localStorage`  
- Soundtrack and retro-style graphics  
- Restart button with player credits

---

## 🕹️ Controls

| Key          | Action                |
|--------------|------------------------|
| `S`          | Start the game         |
| `↑ (Arrow Up)` | Jump                 |
| `← (Arrow Left)` | Move left         |
| `→ (Arrow Right)` | Move right       |

---

## 🧠 How It Works

- The game starts when the player presses `S`.
- The player jumps on platforms to increase their score.
- An enemy shadow chases the player, becoming faster as the score increases.
- If the enemy catches the player or the player falls off the screen, it's game over.
- The restart button appears on game over, allowing you to try again.
- High scores are stored locally.

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- JavaScript (Canvas API)  

---

## 📁 File Structure

JAVASCRIPT GAME/
├── assets/
│   ├── background.png      # Background image for the game
│   ├── enemy.png           # Image sprite for the enemy
│   ├── music.mp3           # Background music or game audio
│   ├── platform.png        # Platform texture used in game
│   └── player.png          # Player character sprite
│
├── index.html              # Main HTML file that renders the canvas
├── style.css               # CSS styling for the game interface
├── script.js               # JavaScript file with game logic
├── README.md               # Game documentation and project info

---

## 📷 Screenshots

### 🧍‍♂️ Gameplay with Score and Enemy
![Gameplay Screenshot](./assets/gamePlay.png)


## ✨ Credits

Developed by **CSE-AI Student of Dayananda Sagar College Bangalore**  
- Pooja Reddy
---

## 📜 License

This project is for educational and demo purposes only. Free to use and modify.

---

Enjoy the game and beat your high score! 🚀
