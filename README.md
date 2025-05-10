# Tic-Tac-Toe-Project
# Tic Tac Toe - Java Console Game

A simple command-line implementation of the classic **Tic Tac Toe** game in Java, where a human player competes against an AI opponent.

---

## 🎮 Features

- 3x3 grid-based Tic Tac Toe game
- Human vs Computer (AI) mode
- Basic AI that selects random available positions
- Win detection (rows, columns, diagonals)
- Game ends with win or draw

---

## 🧠 How It Works

- The game board is represented by a 2D `char` array.
- Players take turns to mark positions with `'X'` (human) or `'O'` (AI).
- The game checks after every move for a win or a draw.
- The AI chooses a random empty cell for its move.

---

## 🛠️ Requirements

- Java JDK 8 or higher
- A terminal or command-line interface

---

## 🚀 How to Run

1. **Clone or download** the project files.
2. Compile the code using:

   ```bash
   javac LaunchGame.java

Run the game:  
java LaunchGame

📁 Project Structure

TicTacToe/
├── LaunchGame.java      # Main class to run the game
├── TicTacToe.java       # Contains board logic and game rules
├── Player.java          # Abstract class for Human and AI players
├── HumanPlayer.java     # Implements player input from console
├── AiPlayer.java        # AI that selects random empty cell


✅ Example Gameplay

Jegan Turn
Enter the row and column:
0 0

-------------
| X |   |   |
-------------
|   |   |   |
-------------
|   |   |   |
-------------

Alexa Turn
...

🧹 Future Improvements
Smarter AI using Minimax algorithm

Graphical User Interface (GUI) with Java Swing or JavaFX

Multiplayer (Human vs Human)

Input validation for non-integer entries

📝 License
This project is free to use for educational purposes.

---

Let me know if you'd like a downloadable `README.md` file or want to turn this into a GitHub repository.
