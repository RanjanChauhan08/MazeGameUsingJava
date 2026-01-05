🧩 Maze Game in Java
📌 Project Overview

This project is a console-based Maze Game written in Java.
The player moves through a maze to reach the exit using keyboard controls.
The game also demonstrates Data Structures and Algorithms like Stack, Queue, and BFS.

🎯 Features

Player movement using W A S D

Undo last move using Stack

Two types of hints

Exit position hint

Closest direction hint (UP / DOWN / LEFT / RIGHT)

Shortest path calculation using BFS

Move history logging

Wall and boundary validation

🕹️ Controls
Key	Action
W	Move Up
A	Move Left
S	Move Down
D	Move Right
U	Undo last move
H	Show exit position hint
C	Show closest direction hint
Q	Quit game
🧠 Concepts Used

2D Arrays for maze representation

Stack for undo functionality

Queue for BFS traversal

Breadth First Search (BFS) for shortest path

Parent tracking for direction-based hints

Object Oriented Programming (OOP)

📂 Project Structure
MazeGame.java
 ├── Maze
 ├── Player
 ├── Position


All classes are included in a single file for simplicity.

🗺️ Maze Symbols
Symbol	Meaning
#	Wall
.	Path
P	Player
E	Exit
💡 Hint System Explanation
H – Exit Hint

Uses BFS

Finds and prints the exit coordinates

Helps player understand where the goal is

C – Closest Hint

Uses BFS + parent tracking

Calculates the next best move

Prints UP / DOWN / LEFT / RIGHT

▶️ How to Run

Save the file as MazeGame.java

Compile:

javac MazeGame.java


Run:

java MazeGame

🎓 Educational Purpose

This project is ideal for:

Learning DSA with Java

Understanding BFS in grids

College mini-projects

Practical exams and viva

✅ Conclusion

This Maze Game combines game logic with core DSA concepts in a simple and interactive way.
It demonstrates how algorithms like BFS are used in real applications such as pathfinding and navigation.
