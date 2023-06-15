# Chess Puzzle Solver

Python program that recursively finds player moves to force the opponent to make certain moves and achieves a checkmate.

## How It Works

The program takes two inputs in the form of text files. The first file should include the current pieces and their

locations on the board line by line. The second file should include the moves we want our opponent to be able to

make after our recursive algorithm finds moves for us. In other words, after each move we make, only valid moves

our opponent can make should be the moves in the corresponding line of this second file. The program then

calculates the possible moves all the pieces can make, tries them one by one and calculates the moves our opponent

can make. It then compares opponent's possible moves to the second input file and if it checks makes the move.

After doing each move the program prints which move is made and the current state of the board in the console.

Eventually the algorithm achieves a checkmate and prints the chain of moves the player should make.

### Prerequisites

An IDE or text editor to run the python code.

## Running the tests

At the start of the code, enter the two file names that include current board pieces with their locations and moves

you want your opponent to be able to make, respectively. 4 example cases are provided in the repository.

