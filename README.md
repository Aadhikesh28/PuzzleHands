# 🧩 PuzzleHands

### 🖐️ A Gesture-Controlled Puzzle Game

PuzzleHands is an interactive puzzle game that allows players to solve image-based puzzles using **hand gestures, mouse, touch, or camera input**.

The project combines computer vision, interactive gameplay, sound effects, animations, and game statistics to create an engaging puzzle-solving experience.

---

## 🎮 Features

### 🖐️ Gesture-Based Gameplay

* Control puzzle pieces using hand movements.
* Pinch gestures can be used to select and move pieces.
* Smooth cursor movement using hand tracking.
* Camera-based gameplay using MediaPipe.

### 🖱️ Multiple Control Methods

* Hand gesture controls
* Mouse controls
* Touch controls
* Camera-based interaction

### 🖼️ Multiple Puzzle Images

Choose from different puzzle themes:

* 🌄 Mountain
* 🐱 Cat
* 🚗 Car
* 🌌 Space
* 🦸 Avengers

The puzzle system automatically divides the selected image into pieces for gameplay.

### 😀 Interactive Mascot

* Dynamic mascot reactions during gameplay.
* Encouraging messages based on game progress.
* Floating emoji reactions for important game events.

### 🎵 Sound & Music

* Background music with an enable/disable toggle.
* Puzzle interaction sound effects.
* Victory and reset sounds.

### ↩️ Undo & Redo

* Undo previous puzzle moves.
* Redo previously undone moves.
* Move history is maintained during gameplay.

### 📥 Download Completed Puzzle

After successfully solving a puzzle, players can download the completed image.

### 🧠 Adaptive Difficulty

The game includes an adaptive difficulty system that can adjust the puzzle challenge based on gameplay performance.

### 📊 Statistics

Track your performance with:

* Games completed
* Best score
* Best time
* Average moves
* Difficulty breakdown
* Recent games
* Performance information

### 🏆 Leaderboard

View and compare puzzle performance through the built-in leaderboard.

---

## 🛠️ Technologies Used

* **Next.js**
* **React**
* **TypeScript**
* **Tailwind CSS**
* **MediaPipe**
* **HTML5 Canvas**
* **Web APIs**
* **Git & GitHub**

---

## 🧠 How It Works

The game provides two main ways to start a puzzle:

### 📷 Camera Mode

1. Start the game.
2. Select the camera option.
3. The camera captures the selected image.
4. The image is divided into puzzle pieces.
5. MediaPipe tracks the player's hand.
6. Pinch and movement gestures allow pieces to be selected and moved.
7. The player arranges the pieces to complete the puzzle.

### 🖼️ Image Selection Mode

1. Start the game.
2. Select **Choose Image**.
3. Pick a puzzle image.
4. The image is divided into pieces.
5. Arrange the pieces using gestures, mouse, or touch.
6. Complete the puzzle and view your result.

---

## 🎯 Objective

The objective of PuzzleHands is to complete the image puzzle in the **least possible time and number of moves** while providing an interactive and enjoyable gesture-based gaming experience.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Aadhikesh28/PuzzleHands.git
```

### 2. Navigate to the Project

```bash
cd PuzzleHands
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```

### 5. Open in Browser

Open:

```text
http://localhost:3000
```

---

## 📁 Project Structure

```text
PuzzleHands/
│
├── public/
│   ├── music/
│   │   └── background.mp3
│   │
│   └── puzzles/
│       ├── mountain.jpg
│       ├── cat.jpg
│       ├── car.jpg
│       ├── space.jpg
│       └── avengers.jpg
│
├── src/
│   ├── app/
│   │   └── page.tsx
│   │
│   └── utils/
│       └── synth.ts
│
├── package.json
├── README.md
└── ...
```

---

## 🌐 Live Demo

🎮 **Play PuzzleHands:**

https://puzzlegamepro.netlify.app

---

## 💻 GitHub Repository

🔗 **Source Code:**

https://github.com/Aadhikesh28/PuzzleHands

---

## 👥 Team

**PuzzleHands** was developed as a collaborative mini-project by a team of three students.

---

## 🔮 Future Improvements

Possible future improvements include:

* More puzzle image categories
* More advanced gesture recognition
* Additional game modes
* Improved accessibility
* Online multiplayer support
* More detailed performance analytics

---

## 📜 License

This project is developed for educational and project demonstration purposes.

---

## ⭐ Support

If you find PuzzleHands interesting, consider giving the repository a ⭐ on GitHub!

**Have fun solving! 🧩🖐️**
