# Chess-Capture-Program-Overview
This project is a Python-based interactive chess program that allows users to determine which black pieces can be captured by a specified white piece (either a knight or pawn) based on its position on the board.

## Features
User Input:

The user inputs the type and position of a white piece (knight or pawn).
The user adds black pieces to the board, ensuring proper input format and valid positions.
## Movement Logic:

The knight moves in an "L" shape, and the pawn captures diagonally one square.
The program calculates which black pieces are in the capturing range of the white piece.
## Validation:

Validates user input for piece types and positions.
Ensures there are no duplicate black piece positions and that at least one black piece is added.
Output:

Displays the list of black pieces that the white piece can capture, if any.
## Technologies Used
Python (No external libraries required)
Interactive user inputs and outputs in a terminal/console.
## Usage
Run the program, input the white piece and its position, then add black pieces. The program will output which black pieces the white piece can capture.
