# Q-Sigma-grid-world
Q(sigma) algorithm on a simple grid world


Environment parameters that can be changed:

BOARD_ROWS = 5 <br />
BOARD_COLS = 4<br />
WIN_STATE = (1, 2)<br />
LOSE_STATE = (3, 2)<br />
START = (2, 0)<br />
WALL = {(1,1),(2,2)}<br />

Q(sigma) hyperparameters:<br />
alpha = 0.2<br />
gamma = 0.7<br />
n step = 3<br />
Behaviour epsilon = 0.7-0.1 with decay of 0.8 every 10 episodes<br />

Trains over 100 episodes<br />
Outputs the Q values at each state <br />
Outputs the environment and the agent's path using the greediest path.<br />
Outputs the length of the episode and plots them<br />



