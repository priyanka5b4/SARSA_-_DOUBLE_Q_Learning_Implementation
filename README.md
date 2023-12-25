# Title: SARSA and Double Q-Learning Project

## Description
This project focuses on the implementation and analysis of two reinforcement learning algorithms: SARSA (State-Action-Reward-State-Action) and Double Q-Learning. These methods are explored to solve a environment based on agent reaching destination in a maze like environment. The project aims to compare the efficiency, learning rate, and overall performance of these algorithms under various conditions.

## Dependencies
```bash
List all libraries and frameworks used. Example:
- Python 3.x
- NumPy
- Gym (for reinforcement learning environments)
- Matplotlib (for visualizations)
```

## Installation
```bash
# Example:
pip install numpy gym matplotlib
````



## Algorithms Overview
### SARSA
SARSA is an on-policy reinforcement learning algorithm used to solve Markov Decision Processes (MDP). 
In SARSA, the agent learns a policy which it then follows, making it an on-policy method.

### Double Q-Learning
Double Q-Learning is a variant of the standard Q-Learning algorithm, designed to address the overestimation bias inherent in traditional Q-Learning. In standard Q-Learning, the same value estimate is used for both selecting and evaluating an action, which can lead to systematically overestimated action values. Double Q-Learning uses two independent sets of action-value estimates (Q-values) to decouple the action selection from the action evaluation. 
