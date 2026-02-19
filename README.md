♟️ Console Checkers Game in C

A fully functional Checkers (Draughts) game implemented in C, playable in the terminal. The program follows standard checkers rules, supports mandatory captures, multiple jumps, and pawn promotion to queens.

🎮 Game Features

Two-player gameplay in console

Enforces official checkers rules:

White moves first

Mandatory captures when available

Multiple jumps in a single turn

Backward captures allowed

Pawn promotion to Queen upon reaching the last row

Queens can move and capture in all diagonal directions

Automatic detection of valid moves and win conditions

Colored board display using ANSI escape codes

Structured move validation and game logic

🧠 Technical Highlights

Implemented using C structures and dynamic memory

Move tree and node logic for capture sequences

Board state management with 8×8 matrix

Modular functions for drawing, move validation, and game status

▶️ How to Run
gcc Checkers.c -o checkers
./checkers

📌 Controls

Follow on-screen prompts to select and move pieces.
