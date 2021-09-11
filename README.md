# ♛♕  Simple Checkers Game  ♕♛
## Web Based Simple Checkers Game 

The Web Base Simple Checkers Game is a basic UI implementation with simple HTML, CSS and Vanilla Javascript.

## Design

1. The player is presented with an 8x8 squares board on the screen. 
2. The white & black pieces are arranged on the board at the initial state - each player has 12 game pieces.
3. The pieces are staggered on each dark square starting from the players starting row up to the third row from them. 
4. The player always starts first as the black player.
5. The player moves by:
- Clicking on the desired piece square,
- The player have a cancel selection button to reset the selection so the player could select another game piece.
6. Rules of movement
- The selected piece can only move diagonally, one square at a time, and forward to the opponent’s side.
- If there is an opponent piece in the next diagonally square and there is an empty space next to it, the player can jump over the opponent piece and remove that piece from the board. 
- If the player reaches the opponent’s starting row, the player piece stays there - there are no king/queen
7. If the movement is not valid
- The app shows a message next to the board - movement is not valid.
- The movement be canceled and the player will be able to choose again a game piece to move
8. Victory
The first player that has two game pieces on the opponent starting row is the winner. 

## Getting Started

Preparations:
```sh
$ git clone https://github.com/iritashuri/simple_checkers.git
$ cd simple_checkers
```

Usage:
You can simply open the HTML with your prefered Web Browser (Currently tested only with Google Chrome Version 92.0.4515.159)
