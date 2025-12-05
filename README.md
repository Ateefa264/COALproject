Project Overview:
This project demonstrates the use of low-level programming concepts such as:

Direct video memory access

Keyboard interrupts

Timers/delays

Conditional logic

Basic game mechanics (movement, collision, scoring)

The game displays alphabets falling from the top of the screen. The player controls a catcher (like a character or basket) using keyboard keys. If the catcher aligns with the alphabet before it reaches the bottom, the alphabet is “caught,” and the score increases.
Concepts Used

This project uses several COAL/Assembly concepts:

1. Video Memory (0xB8000)

Characters and colors are displayed using direct video memory manipulation.

2. Keyboard Interrupts

Reads user input to move the catcher in real time.

3. Randomization Logic

Generates random alphabets (A–Z) to fall.

4. Registers & Procedures

Efficient use of registers and modular code using procedures.

5. Loops & Delays

Used for frame refresh, falling motion, and timing control.
