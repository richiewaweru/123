# Tic-tac-toe

The project implements a 4 by 4 tic-tac-toe board and creates a computer agent that can play against a human agent.The project uses minimax and alpha-beta pruning to program the computer agent.

# Project Description
I have created an agent in Python that uses the minimax algorithm with alpha beta pruning to play against human opponents. The minimax algorithm is a recursive function that searches through all possible moves and their outcomes to determine the best move for the current player. The algorithm uses a heuristic evaluation function to score each possible move and selects the move with the highest score for the current player.

The alpha beta pruning optimization is a way to speed up the minimax algorithm by pruning out branches of the game tree that cannot possibly lead to a better result than what has already been found. By keeping track of the upper and lower bounds on the scores of each possible move, the algorithm can skip over branches that are guaranteed to be worse than the best move found so far.

My agent is able to use these algorithms to play a strong game of tic-tac-toe against human opponents. It is able to look ahead several moves and anticipate the moves of the opponent to make the best possible move for itself. Overall, this version of tic-tac-toe provides a fun and challenging game for players of all levels.




