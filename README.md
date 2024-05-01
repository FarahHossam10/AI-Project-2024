## TicTacToe AI game implemented with python 

The game has two levels, level 0 is human vs AI that chooses where to play during its turn using random functions,
and level 1 is human vs AI implemented using minimax algorithm, and also an option for a normal human vs human game,
the AI in level 0 is not that smart (plays randomly) so it can lose, but the AI in level 1 never loses, it can of course 
tie with human but it never loses.

## How it works:
you click on the 'Level 0' button to play in the human vs random AI mode, 
click on the 'Level 1' button to play in the human vs AI mode,
click on the 'Player vs Player' button to in the normal human vs human mode,
there is also a button 'Restart' of course for restarting the game.

## libraries we used:
- pygame to create the game screen, draw the shapes, lines and display images
- numpy  
- random
- sys and copy

## what is minimax algorithm?
minimax is a backtracking algorithm, used in game theory to find the optimal move for a player,
assuming that the opponent also plays optimally, it is widely used in two player turn-based games 
such as TicTacToe, In Minimax the two players are called maximizer and minimizer. The maximizer
tries to get the highest score possible while the minimizer tries to do the opposite and get the lowest score possible.
Every board state has a value associated with it. In a given state if the maximizer has upper hand then, the score of
the board will tend to be some positive value. If the minimizer has the upper hand in that board state then
it will tend to be some negative value.

# You can check out how this code works in more detail here:
[https://youtu.be/L36nbxMPvwk?si=B3fURQP5YTNbvWzw]
