# rl_banana

## Project Overview

This project contains code to train reinforcement agents to navigate (and collect bananas!) in a large, square world (Unity Environment).

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.<br/>
1 - move backward.<br/>
2 - turn left.<br/>
3 - turn right.<br/>

## Criteria

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started

To get start, first install all the packages in the "requirements.txt" with pip command: 

```
pip install --user --requirement requirements.txt
```

then, unzip the "Banana.zip" with contain the Unity environment for this project.

## How to Run

Start Report.ipynb in jupyter notebook, which contain the code to train the RL agent and plot its performance over time. 
The RL agent should be able to solve the environment within 500 episode.

Report.html -- the status version of the output from Report.ipynb <br/>
dagent.pt -- the saved weights of the learned network that can solve the environment <br/>