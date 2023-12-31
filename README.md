# Snake-Game

### Project Description

The project is a classic snake game created in C++ using Object-Oriented Design principles where the player controls the snake using directional keys (WASD) to consume food items on the board until a self collision.

### Project Features
- Object Oriented Design
- Memory efficient
- Array List with objects for body and food positions

### Gameplay features
- 'X' Food: increases snake length by 3 characters. Increases score by 1
- '$' Food: does not increase snake length. Increases score by 10
- 'o' Food: increases snake length and score by 1

### Development
- Used CUTE test suite to test class implementation in isolation
- Used Dr. Memory Profiler to assess memory leakages and to optimize memory usage
- Used GNU debugger to resolve bugs within program

### Getting Started
Clone the repository and run the command `.\Project.exe` within terminal with the provided Project.exe file

  **OR**

To edit and build the program: 
  1. Ensure proper setup of GCC compiler
  2. Configure makefile and MacUILib.h. Current configuration is for Windows. To run on Mac:
     - Uncomment line 5 in makefile, the POSTLINKER
     - Comment out line 4 and uncomment line 5 in MacUILib.h
  4. Run the command `make` within project directory to create the .exe file
  5. Run the command `.\Project.exe` within terminal to run the program.

### Acknowledgments
This project was created for COMPENG 2SH4
