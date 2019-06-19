# Deep Q Learning to solve Unity ML Banana Collector environment


This project is one of the three projects of the Udacity Deep Reinforcement Learning Nanodegree. The code was expanded and adapted based on a DQN tutorial developed by the Udacity DRL Team, in which the code was used to solve OpenAI's Lunar Lander environment.

## The Environment

In this project, a Deep Q Learning agent was trained to navigate and collect bananas in a square world. 

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

### State space

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions.

### Action space

Four discrete actions are available, corresponding to:

0 - move forward.

1 - move backward.

2 - turn left.

3 - turn right.

## Results

The task is episodic and the environment is considered solved when the agent achieves an average score of +13 over 100 consecutive episodes. The agent was able to solve the environment is 600 training episodes in which it achieved an average score of 13.57.
