### 🎮 Tic-Tac-Toe with AI 👾

A cross-platform console game featuring an **unbeatable AI** using the minimax algorithm.  
Tested on Windows, Linux, and macOS.

![Gameplay](screenshots/gameplay.png)

### ✨ Features:

- 🧠 **Unbeatable AI** powered by the minimax algorithm
- 📊 Dynamic score tracking (Player vs. AI)
- 🖥️ Cross-platform support (Windows/Linux/macOS)
- ✅ Robust input validation
- 🔄 Play again option


### 🚀 Getting Started

   # Prerequisites
- **C++ Compiler**: `g++` (GNU Compiler Collection)
  - Windows: Install [MinGW](http://www.mingw.org/)
  - Linux/macOS: `sudo apt install g++` (Debian/Ubuntu) or `brew install gcc` (macOS)

   ## Clone the Repository
   ```bash/Terminal
   1.HTTPS:
      git clone https://github.com/Rabby0501/Tic-Tac-Toe-AI.git

   2.SSH:
      git clone git@github.com:Rabby0501/Tic-Tac-Toe-AI.git


### How to Run & Play: 

# Compile the code
   bash/Terminal or VS Code:
   # For Linux/macOS # For Windows
      g++ -o tictactoe tictactoe.cpp
      g++ -o tictactoe.exe tictactoe.cpp

   ## Executable File (`tictactoe.exe`)  
      A pre-compiled Windows executable is included for immediate gameplay.  

   ### Run:
   # Linux/macOS
      .\tictactoe

   ## Windows
   1. Download `tictactoe.exe`.  
   2. Double-click the file or run via Command Prompt:  
      ```cmd  
         .\tictactoe.exe  

### 🧩 Game Rules:
 1. Enter 1-9 to place your mark (X) on the 3x3 grid:
   | 1 | 2 | 3 |
   -------------
   | 4 | 5 | 6 |
   -------------
   | 7 | 8 | 9 |

2. AI (O) responds instantly with its move
3. First to 3 in a row (horizontal/vertical/diagonal) wins!
4. Type y/n to play again or quit

### 📸 Screenshots:
1. Windows
2. Linux/macOS

### 📁 Project Structure:

📁 Tic-Tac-Toe-CPP/
├── 📁 screenshot/          # Gameplay screenshot.png 
├── 📁 src/ 
│   ├── 📄 tictactoe.cpp    # Source code 
│   ├── 📄 tictactoe        # Compile File for Linux/macOS
│   └── 📄 tictactoe.exe    # Windows executable  
├── 📄 .gitignore           # 
├── 📄 README.md            # Compilation guide, screenshots
└── 📄 screenshot.png       # Gameplay screenshot