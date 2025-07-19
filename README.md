# OOP-Gameboy

ameBoy Console Simulation (C++ & SFML)
A multi-game simulation project built using C++ and SFML in Visual Studio.

📚 Table of Contents
Introduction
Games Included
Features
Screenshots
Installation
Usage
Known Issues
Contribution
Author
License
📘 Introduction
GameBoy Console Simulation is a creative desktop application that mimics the behavior of a handheld gaming console. It features a graphical main menu, game selector, and three fully playable classic games: Hangman, Snake, and Wordle.

Developed using C++ and the Simple and Fast Multimedia Library (SFML), this project focuses on interactive gameplay, keyboard controls, and retro-inspired game mechanics. The UI is built using SFML's graphics module, and everything runs in real time.

This game was created as part of the first semester Programming Fundamentals course.

🎮 Games Included
🟢 Wordle
A 5-letter guessing game.
Green = correct letter and position.
Yellow = correct letter, wrong position.
Red = letter not in the word.
5 attempts to guess the word.
🔤 Hangman
Choose from 3 categories:
1 → Animals | 2 → Fruits | 3 → Countries
Guess letters before the man is fully drawn.
Fun word pool and simple visuals.
🐍 Snake
Classic snake mechanics.
Eat fruits to grow longer.
Avoid colliding with yourself or the wall.
Real-time movement with keyboard input.
✨ Features
🎨 SFML-powered graphical interface
🎹 Keyboard navigation using arrow keys + Enter
📜 Menu system with Play, Instructions, and Exit
📦 Organized C++ files with .cpp and .h
🔠 Category selection using number keys in Hangman
✅ Designed and compiled in Visual Studio
🔁 Replay functionality for each game
💡 Minimal dependencies (SFML only)
🖼️ Custom assets: Includes menu1.png for main menu visuals and arial.ttf for clean, readable in-game fonts
📸 Screenshots
Screenshot 2025-06-11 200836 Screenshot 2025-06-11 200932 Screenshot 2025-06-11 201007 Screenshot 2025-06-11 201101 Screenshot 2025-06-11 201228

⚙️ Installation
📥 Requirements
Visual Studio 2019 or newer
SFML (Simple and Fast Multimedia Library)
🔧 Setting up SFML with Visual Studio
Download SFML from: https://www.sfml-dev.org/download.php
Extract it to a location on your PC.
In Visual Studio:
Go to Project → Properties → VC++ Directories
Add SFML include/ to Include Directories
Add SFML lib/ to Library Directories
Go to Linker → Input → Additional Dependencies
Add:
sfml-graphics-d.lib
sfml-window-d.lib
sfml-system-d.lib
Copy .dll files from SFML/bin/ to your project's Debug folder.
✅ Note: The official .cpp and .h files provided in this project contain the complete gameplay logic.
🎨 The menu1.png file is used as the main menu background.
🔤 The font arial.ttf is used for all textual elements across the games.

🚀 Usage
🔁 Build & Run
Clone or download this repository.
Open the .sln file in Visual Studio.
Build the solution.
Press F5 or click Start Debugging to run.
🎮 Controls
↑ ↓ → Navigate menu or game list
Enter → Select menu/game
1 / 2 / 3 → Choose Hangman category
W A S D or Arrow Keys → Snake movement
Alphabet Keys → Word input
🐞 Known Issues
Word validation is basic (no dictionary check)
Game resolution is fixed (may not scale well)

🤝 Contribution
You're welcome to contribute!

Fork this repository
Clone it:
git clone https://github.com/yourusername/gameboy-console.git
Create a new branch:
git checkout -b feature/your-feature
Make your changes
Commit and push:
git commit -m "Add new feature"
git push origin feature/your-feature
Open a Pull Request
👨‍💻 Author
Hassaan Mudassar
📧 mudassarhassaan@gmail.com
🎓 BSCS — NUCES FAST Islamabad (Batch 2023–2027)

🪪 License
This project is licensed under the MIT License.

"Built from scratch using C++ and SFML — No built-in libraries, just logic, graphics, and a love for old-school games."
