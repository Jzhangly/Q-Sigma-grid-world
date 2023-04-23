# Q-Sigma-grid-world
Q(sigma) algorithm on a simple grid world


Environment parameters that can be changed:

BOARD_ROWS = 5 <\br>
BOARD_COLS = 4
WIN_STATE = (1, 2)
LOSE_STATE = (3, 2)
START = (2, 0)
WALL = {(1,1),(2,2)}

Q(sigma) hyperparameters:
alpha = 0.2
gamma = 0.7
n step = 3
Behaviour epsilon = 0.7-0.1 with decay of 0.8 every 10 episodes

Trains over 100 episodes
Outputs the Q values at each state 
Outputs the environment and the agent's path using the greediest path.
Outputs the length of the episode and plots them



