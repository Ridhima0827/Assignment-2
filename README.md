# Assignment-2
1. Repository Link

Original game:
https://github.com/shoonyank/game

2. Overview of the Game

The existing project is a simple terminal-based running game where a player character must avoid obstacles by jumping at the right time. The screen refreshes continuously to simulate motion. It uses basic C programming concepts such as loops, conditionals, keyboard input and rendering using text.

3. Game Loop Behavior

The game follows a classic infinite loop structure:

Read Input

Check if user presses a key.

If pressed, the player jumps.

Update State

Move obstacles.

Update jump height.

Check collisions.

Render Frame

Clear the screen.

Print updated positions.

Show player and obstacle on a grid.

Delay

Sleep for a fixed number of milliseconds to control game speed.    

This loop continues until the player hits an obstacle, which stops the game.

4. Input Handling

The game uses kbhit() and getch() for non-blocking keyboard input.
This allows:

Continuous game movement

Player control without pausing the game

Real-time jumping

This method is widely used in old-school C terminal games.


5. Strengths of the Existing Game

✔ Very simple and readable code — good for learning and teaching basics of C

✔ Modular project structure — organized into multiple files

✔ Real-time input handling — demonstrates non-blocking I/O

✔ Easy to extend and modify — good for adding student-designed features

✔ Lightweight and fast — runs smoothly on any system

6. Weaknesses and Limitations

✘ No scoring or progression system

✘ Only one type of obstacle → gameplay becomes repetitive

✘ No difficulty scaling (speed remains constant)

✘ No restart or pause functionality

✘ No sound, animations, or end-game transitions

