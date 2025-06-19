# 🎮 Tic Tac Toe – Android App (Java)

A simple **Tic Tac Toe** game built using **Java** and **Android Studio**, allowing two players to play turn by turn. This project demonstrates basic UI interaction, condition checking, and simple game logic implementation on Android.

---

## 📱 Features

- Two-player mode (X and O)
- Game board resets after win or draw
- Win detection: all rows, columns, and diagonals
- Toast message to display winner or draw result
- Clean and minimal UI layout (XML based)

---

## 🧠 How It Works

- The game board is a 3x3 grid made of 9 buttons.
- On each button click:
  - The current player's symbol (`X` or `O`) is placed.
  - Turn alternates using a `flag`.
  - After 5+ moves, the app checks for a win condition.
  - If a player wins or the board is full (draw), a toast appears and the game resets.

---

## 🛠️ Tech Stack

| Component         | Details                      |
|------------------|------------------------------|
| Language          | Java                         |
| IDE               | Android Studio               |
| UI Design         | XML                          |
| Min SDK           | Based on default setup       |
| Game Logic        | Pure Java logic in activity  |

---

## 📂 Project Structure

com.example.tiktactoe
├── MainActivity.java # Core game logic and UI handling
├── res/
│ └── layout/
│ └── activity_main.xml # 3x3 button layout


---

## 🚀 How to Run

1. Clone this repository
2. Open in **Android Studio**
3. Run on an emulator or physical Android device
4. Tap the buttons and enjoy playing!

---

## 🧾 Notes

- This is a basic project for learning purposes — no AI, scores, or advanced UI.
- No external libraries or third-party APIs used.
- All win/draw logic handled manually using string comparison.

---

## 🧑‍💻 Author

**Subhash Kumar**  
📧 subhashsaw070@gmail.com  
📍 Android Developer, Kotlin/Java enthusiast

---

