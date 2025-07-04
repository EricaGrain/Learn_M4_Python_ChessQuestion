# M4S1 Graded task - Python - Chess Question

Implement a Python program that will answer a simple question – given a board state that the user enters, with 1 white figure and up to 16 black figures, which black figures can the white figure take?

## Contents

1. User Input for White Piece
The program must prompt the user to input a white piece and its position on the board.
The user must choose between two predefined piece types (e.g., pawn and rook).
The input format must be: (e.g., knight a5).
The program must confirm a successful addition or display an error message if the input is invalid.

2. User Input for Black Pieces
After the white piece is set, the user must input the black pieces one by one.
Each black piece must follow the same format (e.g., bishop d6).
The user must add at least one and at most sixteen black pieces.
The user can enter "done" to stop adding black pieces only after at least one black piece has been added.
The program must confirm a successful addition or display an error message if the input is invalid.

3. Input Validation
The program must ensure that input coordinates follow the correct format (where the letter is a-h and the digit is 1-8, e.g., a1, d4, h8).
The program must handle edge cases, such as:
Attempting to enter "done" before adding at least one black piece.
Providing invalid chess piece names.
Entering out-of-bounds coordinates.

4. Output and Gameplay Logic
After all pieces are added, the program must display a list of black pieces that the white piece can capture based on valid chess moves.
If no black pieces are captured, the program should indicate this clearly.
Optional Tasks
After the main functionality is implemented, your code works correctly, and you feel that you want to upgrade your project, choose one or more improvements from this list. Again, this is strictly optional. Some of these optional tasks may be challenging.


5. Implement a Nice Visualization Function
Create a function to print the chessboard using Unicode chess symbols to represent each piece accurately.
Ensure proper alignment of pieces in an 8x8 grid, with row and column labels.

## Access to the Project

Project is uploaded to github as Jupyter Notebook file
