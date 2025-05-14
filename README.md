# SCT_WD_03 - 🎮 Ultimate Tic Tac Toe(Neon Themed AI/Multiplayer Game)

**Ultimate Tic Tac Toe** is a modern, neon-styled version of the classic 3x3 Tic Tac Toe game. It supports **Player vs Player** and **Player vs AI** modes, a unique glowing UI, score tracking, sound effects, move undo, and an interactive instruction modal—all created using **HTML, CSS, and JavaScript**.

---

## 📋 Task Description

This project implements a fully functional Tic Tac Toe game that includes:

- Two gameplay modes: PvP and PvAI  
- Score tracking for both players and draws  
- Stylish, glowing neon visuals  
- Undo last move feature  
- Sound effects and theme feedback  
- Pop-up instructions modal

---

## 🚀 Features

### ✅ Game Modes
- **🧑‍🤝‍🧑 Player vs Player**: Local multiplayer
- **🧑‍🤖 Player vs AI**: Battle against a simple AI

### ✅ Intuitive UI
- Neon glowing effects for each cell
- Win animations and pulsing effect
- Dynamic game status messages

### ✅ Scoreboard
Tracks:
- X Wins 🧑
- O Wins 🧑 or 🤖
- Draws 🤝

### ✅ Audio Feedback
- Click, win, and lose sounds  
- Toggle sound on/off

### ✅ Undo Last Move
Revert the most recent move (PvP or PvAI)

### ✅ Instructions Modal
- Pop-up with game rules and tips
- Easy-to-understand layout

---

## 📁 File Structure

📦 ultimate-tic-tac-toe/

┣ 📄 index.html # Main HTML file with all logic embedded

┣ 🎵 mouse-click-290204.mp3 # Sound for clicks

┣ 🎵 level-win-6416.mp3 # Win sound

┣ 🎵 violin-lose-3-180435.mp3 # Lose/draw sound


---

## 🛠️ Tech Stack

| Technology | Description                    |
|------------|--------------------------------|
| HTML5      | App structure & content layout |
| CSS3       | Glowing neon styling, animations, responsive layout |
| JavaScript | Game logic, AI moves, sound, state management |

---

## 💻 How to Run Locally

### 🔹 Option 1: Using VS Code + Live Server
1. Open folder in VS Code
2. Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
3. Right-click `index.html` → **Open with Live Server**

### 🔹 Option 2: Manual Run
1. Open the project folder
2. Double-click `index.html`

---

## 🎨 Design Highlights

- **Neon pink** for player X  
- **Neon cyan** for player O  
- Glowing borders and pulse animations  
- Smooth transitions for UI interactions

---

## 🎧 Sound Effects

| Action         | Sound                  |
|----------------|------------------------|
| Click cell     | `mouse-click-290204.mp3` |
| Win            | `level-win-6416.mp3`     |
| Lose/Draw      | `violin-lose-3-180435.mp3` |

Sound can be toggled on/off via the UI button.

---

## 🧠 AI Logic

The AI selects a **random available cell**. It provides a basic challenge for casual gameplay and can be enhanced further with Minimax or other algorithms.

---

## 📃 License

This project is open-source for educational or personal use. Attribution is appreciated.


