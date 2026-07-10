Snake Game (C++)

A simple implementation of the classic Snake game using C++ and a console-based interface. The snake moves around the screen, eats fruit to grow, and avoids colliding with the walls or itself. Window OS used.

Project Description

This is a console-based Snake game written in C++ that simulates the well-known game where the player controls a snake that moves around the screen. The goal is to collect fruit (denoted by F), causing the snake to grow in size while avoiding collisions with the screen boundaries or its own tail.

Key Features:

Simple console-based interface.
Snake can move in four directions: left, right, up, and down.
Fruit randomly appears on the screen.
The game ends when the snake collides with a wall or itself.
Installation

<iostream> – Used for input and output operations (printing to the console).
<vector> – Used to store the tail of the snake and manage dynamic arrays.
<deque> – Used for managing the snake’s tail more efficiently, allowing elements to be added to both ends.
<cstdlib> – Provides functions like rand() for generating random numbers (used for generating the fruit's position).
<ctime> – Used for seeding the random number generator using the current time.
<conio.h> – Provides functions like _kbhit() and _getch() for detecting user input without waiting for Enter (used to control snake movement).
<windows.h> – Used to control the sleep interval (game speed) and clear the console screen between frames (via the Sleep() function).
Usage

Start the game: When you run the program, the snake will appear at the center of the screen, and you’ll be prompted with the current score.
Move the snake: Use the following keys to control the snake:
W - Move up
A - Move left
S - Move down
D - Move right
X - Quit the game
Objective: Eat the fruit (denoted by F) to grow longer and increase your score. Avoid colliding with the walls or the snake’s tail.
