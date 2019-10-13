# MCTS-TicTacToe
Monte Carlo Tree Search Algorithm based AI Tic Tac Toe Solver
# About
This project aims at devloping an AI game solver for board games. Since tic -tac-toe is a clasical example of board games. I try to implement the Monte Carlo Tree Search Algorithm.
# Monte Carlo Tree Search Algorithm (MCTS)
Monte Carlo tree search (MCTS) is a heuristic search algorithm for some kinds of decision processes, most notably those employed in game play. MCTS was introduced in 2006 for computer Go.
# Why MCTS?
For solving board games like tic-tac-toe, genrally algorithms like MinMax are used. This project is a way of trying out techniques to create a AI solver which can be used to play an AI vs Human or AI vs AI game.

# How does MCTS work?
read this to understand the [working of mcts](https://github.com/kushagra1198/MCTS-TicTacToe/blob/master/MCTS_Kushagra_Notes.pdf).
<img src="https://i.stack.imgur.com/EieiQ.png" alt="Logo">

# The project
So, this project is a python based code implementation of MCTS to solve two player tic-tac-toe. Player1 is X and Player2 is O.

# Working of code and sample
So, the code working can be shown by the following examples:

![exmp](https://user-images.githubusercontent.com/43116010/66701529-a2eec380-ed1a-11e9-973a-13113d545ee1.PNG)

In this snippet, we have a 3 * 3 grid. The 0s represent empty spaces i.e the cells that are empty and a player can play their moves on them. Symbol -1 reresents the cell is occupied by player O while symbol 1 represents that cell is occupied by X. In the snippet the AI algorithm suggests move 3 which means row = 2 and column = 1. Which is the most optimal move by player X to stay in the game without losing. 
