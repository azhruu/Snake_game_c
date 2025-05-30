🐍 Console Snake Game in C
This is a simple Snake Game implemented in C language, playable in the Windows console. It uses basic functions for drawing the game board, handling keyboard input, and game logic (collision detection, scoring, etc.).


🎮 Controls
Key	Action
W	Move Up
A	Move Left
S	Move Down
D	Move Right
X	Exit Game

🔧 Requirements
Windows OS (uses <windows.h>, <conio.h>)

C Compiler (like GCC or Turbo C)

Console window (CMD)

📂 How to Run
Clone this repository:

bash
Copy
Edit
git clone [https://github.com/your-username/snake-game-c.git](https://github.com/azhruu/Snake_game_c)
Compile the code:

bash
Copy
Edit
gcc snake.c -o snake
Run the game:

bash
Copy
Edit
./snake
📦 Features
Console-based classic snake gameplay

Random fruit placement

Score tracking

Snake tail grows with each fruit

Game over when snake hits the wall or itself

🚀 Future Improvements (Optional)
Add a start menu and difficulty levels

Implement sound effects

Make it cross-platform (remove <conio.h> and <windows.h> dependencies)
