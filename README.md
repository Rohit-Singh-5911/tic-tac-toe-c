# Tic Tac Toe in C
This is a console-based Tic Tac Toe game implemented in C language.  
The game is designed for two players who take turns placing `X` and `O` on a 3x3 board.  

# Features
- Console-based interface.  
- 3x3 board represented using a 2D array.  
- Players choose a cell by entering its number (1–9).  
- Each move replaces `#` with the player’s symbol (`X` or `O`).  
- Automatically checks after every move:
  - If a player has won.  
  - If the game ends in a draw.  
- Displays the winning player (`Player 1` or `Player 2`) in the console.  


# How to Play
1. Run the program in your terminal/console.  
2. The board starts with positions marked as numbers (1–9) or `#`.  
3. Player 1 uses `X`, and Player 2 uses `O`.  
4. Players take turns entering the number corresponding to the position they want to mark.  
5. The game continues until:
   - A player wins by getting 3 in a row (horizontally, vertically, or diagonally.  
   - Or the board is full, resulting in a draw.  


# Project Structure
tic-tac-toe-c/
│
├── tic_tac_toe.c   # Main C source code
├── README.md       # Project documentation

# Skills Demonstrated
- C Programming basics
- 2D Arrays for board representation
- Loops and conditionals for game logic
- Functions for modular design
- Input/output handling in C

# Future Improvements
- Add option to play again without restarting the program.
- Add single-player mode against computer (AI).
- Improve board visuals.
- Adding GUI for better user experience.

