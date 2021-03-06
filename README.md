# marl-gathering
Multi Agent Reinforcement Learning in Apple Gathering Game


## Training

To train the agents use scripts `python run_single.py` or `python run_two.py`.


## Evaluation

To evaluate the trained agents and produce a video use `python test_single.py` or `python test_two.py`.

## Gifs

### Supplementary gif 1
Optimal strategy of a single agent trained in isolation.

![](gifs/Supplementary_gif_1.gif)

### Supplementary gif 2
Collaboration of two DQN agents.

![](gifs/Supplementary_gif_2.gif)

### Supplementary gif 3 & 4
DQN playing against a random agent.

![](gifs/Supplementary_gif_3.gif)
![](gifs/Supplementary_gif_4.gif)



### Supplementary gif 5
DQN playing against a random agent in low resource abundance environment.

![](gifs/Supplementary_gif_5.gif)

### Supplementary gif 6
Two DQN agents that learned defecting policy in a low resource abundance environment.

![](gifs/Supplementary_gif_6.gif)


### Supplementary gif 7
Game in the team setting. Blue team consists of two DQN agents that learned to cooperate when using reward signals of R1 + 0.25\*R2 for the first player and R2 + 0.25\*R1 for the second player. Red team executes a random policy.

![](gifs/Supplementary_gif_7.gif)
