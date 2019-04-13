# Tic_Tac_toe_Ruby

This game will be able to be played by two players from the command line.

The board is a 3 x 3 grid and players will play until a player wins or until there is a draw.

Winning the game can be achieved by securing three adjacent positions in a row, column or diagonal. The game ends in a draw if neither player has won but all the positions on the board are occupied.

The following principles are followed in designing this game.

* single purpose classes are designed so that the source code is easy to modify. The process to do this includes identifying the nouns from specifications.

* the game is built from a TDD perspective.

* the Bundler gem was used to create a gem called tic_tac_toe so that it can be included in other projects.

## Setup

* created the directory for the project
* run 'bundle init' from the terminal
* in the Gemfile add 'bundle gem tic_tac_toe' (if you agree to all the permissions follow the displayed instructions)


## Classes

* Since the board is has 3 rows and 3 columns, the board consists of 9 individual cells, each with unique coordinates to identifiy its location.

* Each cell can be either blank, or occupied with 'x' or 'o'.
