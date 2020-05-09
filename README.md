# Project 1: Navigation

In this project, we train an agent in the Unity ml-agents environment to pick up bananas. The goal of the agent is to pick up as many yellow bananas as possible avoiding the blue ones.


![](https://user-images.githubusercontent.com/23094225/81484019-2dd36600-91f7-11ea-9917-03d74e164a86.gif)


The agent gets a +1 reward for each yellow banana it picks up and a reward of -1 for each blue banana.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* 0 - move forward
* 1 - move backward
* 2 - turn left
* 3 - turn right

For the environment to be solved, the agent has to collect an average reward of +13 over 100 consecutive episodes.

## Training the agent:
To train the agent, clone this repository in your local directory. 

Dependencies:

* tensorflow=1.7.1
* unityagents=0.4.0
* mlagents=0.16.0
* mlagents-envs=0.16.0
* torch
* matplotlib
* numpy


Run the Navigation.ipynb notebook. We set the no_graphics flag to be True when we load the environment, inorder to speed up the training process.
 

## Testing the agent:
Once the agent is trained, we can test the trained agent by loading the model from the checkpoint.pth file. The Navigation.ipynb contains code for testing the trained agent.   
For testing, we set the no_graphics to be False for visualization.

