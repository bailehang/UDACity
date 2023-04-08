
# Banana Collecting Agent
# Introduction
Train an agent using Deep Reinforcement Learning to collect bananas in a unity enviroment.

![banana](.\banana.gif)

# Project Details
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

# Getting Started
There is a provided conda enviroment file `drlnd.yml` create an enviroment as shown below.

```
conda env create -n drlnd --file drlnd.yml
```
Then activate the envroment.

```
conda activate drlnd
```

Finally launch jupyter.

```
jupyter-lab
```

# Instructions
Open the file `AgentsTrain.ipynb` and run all code section to train a model `checkpoint.pth`

Open the file `AgentsPlay.ipynb` and run all code section to use the model, watch the game in action.



