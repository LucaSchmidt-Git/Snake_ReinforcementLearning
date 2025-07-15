## Project on using reinforcement learning (Q-Learning) to train the agent to play the iconic game Snake. 

Special tweek: Typically, in Snake it is not possible to move beyond the boarder. The given game is different. Here, the snake proceeds on the opposite site of the grid. 

Furthermore, the Snake has a parameter "echorange" that specifies how much the snake sees around itself. For example: echorange=2 implies that the snake has a 3x3 vision around its head. 

### Given Files: 
Jupyter Notebook: Provides a class for the Grid, a class for the Snake and a class for the Q Learning strategy. 
Results/ : Two precompiled models. One is given by Echorange2 and one is given by Echorange3. 

### Needed modules: 
pygame, numpy, matplotlib, pandas

### Use the precompiled models:
1. Drag the wanted Echorange into the same directory as the Notebook (Both policy and values).
2. In the Notebook, execute "load_q_and_policy", after entering your path to the files.
4. Execute "run_q". Make sure that "visualize_snake", "Snake" and "Grid" are defined. 

### Train your own agent. 
1. Initialize Snake, Grid, QValues, q_learning. Optional: Initialize GridSearch and QLearningTrainer if you want to tune hyperparameters.
2. Execute q_learning() with your settings. Optional: For Hyperparamter tuning, execute GridSearch(QLearningTrainer, param_grid, verbose)
3. To show a sample game, initialize visualize_snake() and call run_q(). 


