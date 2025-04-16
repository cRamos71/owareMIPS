# MIPS Assembly - OWARE Game

This repository contains the source code for an implementation of the OWARE game in MIPS Assembly. It serves as an educational project aimed at reinforcing core MIPS programming concepts through a fun, interactive application.

---

## Project Overview

OWARE is a traditional strategy game from the Mancala family. This version is implemented to run in a console environment using the MARS simulator. Players interact with the game via console input, and the game board updates visually after each move.

The project provides hands-on experience with:

- Control flow and branching  
- Looping and logic in assembly  
- System calls for I/O  
- Memory and register management  

---

## Getting Started

To run the OWARE game on your machine:

1. Install the [MARS MIPS Simulator](http://courses.missouristate.edu/kenvollmar/mars/).
2. Clone this repository or download the `.asm` file.
3. Open the file in MARS.
4. Run the simulation and follow the console prompts.

---

## How to Play

- The game supports two players, each controlling six pits.
- On each turn, a player selects a pit on their side to sow seeds counterclockwise.
- Seeds are distributed one per pit, skipping the original pit.
- Capturing follows standard OWARE rules.
- The game displays the board after each move and switches turns automatically.

---

## Educational Goals

This project is designed to help students practice and understand:

- Input/output operations using syscalls  
- Data manipulation using arithmetic and logical operations  
- Procedural decomposition in assembly  
- Managing game logic and state through registers and memory  

---

## Customization and Exploration

Students are encouraged to explore beyond the base implementation:

- Modify board size or seed count  
- Implement AI for single-player mode  
- Add error handling for invalid inputs  

---

## License

This project is open-source and intended for educational use.  
Feel free to modify, adapt, and share it with proper attribution.
