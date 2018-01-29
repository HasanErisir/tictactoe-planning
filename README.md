# Tic-tac-toe Planning

This is a simple game of Tic Tac Toe with nine turns. This is because there are only nine slots on a tic tac toe board. The winner is determined by whoever has a straight or diagonal line using their symbol. If no one has been able to achieve a straight or diagonal line by the end of the ninth turn, both players draw 


## Plan

A Data structures, files:
For the tic tac toe game, I will be using a set of arrays and booleans. These will be used to verify the user’s positions on the board and check which user has won. I will also be using integers for the user to place their position. This will be done by taking the number inputted by the user and placing it on the board if there already isn’t a symbol on it.

B. variables and constants
I will be using a set of variables throughout the game to update the player’s position. I will be using a constant to limit the amount of turns. This is so the game doesn’t get stuck and play on forever.

C. User Interface:
In order to make sure the user understands where they are in the game, I will be printing the board out to the user each time a turn ends. This will make the game easier and more enjoyable to play as they will be able to see the positions in the game.


## Flowchart
![A flow chart of how the program will work.](https://nova.s-ul.eu/glmB22JF.png)

## Testing

#### Test PLan

|Test Number     |Test                                   |Test Data                           | Test Type | Expected Result | Actual Result|
|----------------|-------------------------------|-----------------------------|--------|--------------------------|---------------------------|
|1|Testing user input for position on grid.|10|Erroneous| Error: Please enter a number between 0 - 9.
|2|Testing user input for position on grid|1| Valid| User symbol is placed on position if not taken.
|3|Testing user input for position on grid|-5 | Extreme| Error, position doesnt exist on the board.
|4|User wins when they have a straight or diagonal line| 012, 345, 678, 036, 147, 258, 048, 246 | Valid| Game ends, winner is outputted|
|5|Game ends when turn count = 9| 9| Valid| Game ends, outputted as a draw.


