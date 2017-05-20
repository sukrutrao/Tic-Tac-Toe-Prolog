# Tic-Tac-Toe-Prolog
A one player Tic-Tac-Toe Game in Prolog

### Prerequisites

* gplc v1.3.0 or higher. In Ubuntu 14.04 and 16.04, this can be installed using
```
sudo apt-get install gprolog
```

### Download and Run
* Download `TicTacToeGame.pl`.
* To compile, run
```
$ gplc --no-top-level TicTacToeGame.pl
```
* To play, run
```
$ ./TicTacToeGame
```

### How to Play
* This is a one player Tic-Tac-Toe console-based game.
* The human player always plays first. The human player's moves are denoted by a `1`, and the computer player's moves are denoted by a `0`.
* The game board is a 3x3 one-indexed grid. To play, two integers are given as the input. The first is the row number, and the second is the column number. For example, to play in the centre square, the input will be `1 1`.
* The game assumes that all inputs given will be valid inputs.
