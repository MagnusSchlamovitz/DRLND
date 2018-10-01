# DRLND
For this project, I will train an agent to navigate (and collect bananas!) in a large, square world. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of my agent is to collect as many yellow bananas as possible while avoiding blue bananas.

# Dependencies

This is an amended version of the `python/` folder from the [ML-Agents repository](https://github.com/Unity-Technologies/ml-agents).  It has been edited to include a few additional pip packages needed for the Deep Reinforcement Learning Nanodegree program.

# Project Navigation
For this project, I will train an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. The goal of my agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.

The task is episodic, and in order to solve the environment, the  agent must get an average score of +13 over 100 consecutive episodes.

##### The project requires following dependencies:

Numpy
Jupyter
JupyterLab
PyTorch
Matplolib
UnityML agents

These dependencies can be installed using the pip or conda install command, in your Anaconda environment. 

```
conda create -r requirements.txt
```

The agent is trained using the Deep Q Network. The code I used is available in  Navigation.ipynb. The  agent reached a reward of 13.50 , which it managed within 2500 Episodes.

