# Project 1: Navigation

In this project, we train an agent in the Unity ml-agents environment to pick up bananas. The goal of the agent is to pick up as many yellow bananas as possible avoidiing the blue ones.

The agent gets a +1 reward for each yellow banana it picks up and a reward of -1 for each blue banana.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* 0 - move forward
* 1 - move backward
* 2 - turn left
* 3 - turn right

For the environment to be solved, the agent has to collect an average reward of +13 over 100 consecutive episodes.

## Training the agent:
To train the agent, clone this repository and run the Navigation.ipynb notebook. 
The agent trains for about 400 episodes. 

## Testing the agent:
Once the agent is trained, we can test the trained agent by loading the model from the checkpoint.pth file. The Navigation.ipynb contains code for testing the trained agent.   

