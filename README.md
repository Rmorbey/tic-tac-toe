# tic-tac-toe

This is a simple command line interface of the two player game Tic Tac Toe, this is built in Javascript and is played within your terminal.

The game requires two players, and will prompt the player X or player O to input their desired position on the board.

---

## 📦 Installation & Usage

### Installation

To install the game please follow these instructions:

  - Clone this repository by clicking the green code button on the top right hand side.
  - Copy the SSH link and go to your terminal.
  - Type ``` git clone ``` and paste your SSH link.
  - ```cd tic-tac-toe``` into the folder that was created.
  - Type ``` npm i ``` to install the dependencies.

### Usage

To run and play the game:

  - Type ```node tictactoe.js```

It will now display an empty board and will prompt Player X to input their desired grid space between 0 and 8.

### Gameplay

Player X and Player O will take turns inputting their desired locations until either player has won, or the game ends in a draw.

Players will be re prompted to make their move again if either, the move is outside the bounds of 0 to 8, or the grid space is already occupied by an X or O.

When the game is over the CLI closes and if you would like to play again you'll need to type ``` node tictactoe.js ``` into your terminal and start again with a fresh board.
