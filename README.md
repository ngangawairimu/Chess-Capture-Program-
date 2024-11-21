# Chess-Capture-Program
This program simulates a simple chess scenario where a white piece (either a knight or a pawn) tries to capture black pieces on the board. Users input the positions of the white piece and multiple black pieces, and the program calculates which black pieces are capturable based on chess rules.
## How It Works:
- The user provides the type and position of the white piece (e.g., knight d4).
- They then input up to 16 black pieces with their positions (e.g., pawn c5).
   Validation:
The program ensures all inputs follow proper chess notation (e.g., a1 to h8).
It prevents duplicate positions and supports only valid piece types (knight or pawn).
  #### Chess Logic:
For a knight, the program calculates all possible "L-shaped" moves.
For a pawn, it considers diagonal captures one square forward.

## Features
User Input:

- The user inputs the type and position of a white piece (knight or pawn).
- The user adds black pieces to the board, ensuring proper input format and valid positions.
## Movement Logic:

- The knight moves in an "L" shape, and the pawn captures diagonally one square.
- The program calculates which black pieces are in the capturing range of the white piece.
## Validation:

- Validates user input for piece types and positions.
 - Ensures there are no duplicate black piece positions and that at least one black piece is added.
### Output:

Displays the list of black pieces that the white piece can capture, if any.
## Technologies Used
Python (No external libraries required)
Interactive user inputs and outputs in a terminal/console.
## Usage
Run the program, input the white piece and its position, then add black pieces. The program will output which black pieces the white piece can capture.
