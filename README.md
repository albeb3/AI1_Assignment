# Walking Cliff – SARSA Reinforcement Learning

This repository contains a Python implementation of the **Walking Cliff** problem solved using the **SARSA reinforcement learning algorithm**.

The project models a grid-world environment where an agent must learn how to reach a goal while avoiding cliff cells. The agent learns through trial and error using an ε-greedy policy and updates a Q-table according to the SARSA on-policy learning rule.

## Project Contents

* `WalkingCliff.ipynb`: Jupyter Notebook containing the full implementation.
* Custom Walking Cliff environment.
* ε-greedy policy for exploration and exploitation.
* SARSA algorithm implementation.
* Greedy policy extraction from the learned Q-table.
* Visualization of the agent moving in the grid-world.

## Main Features

* Definition of states, actions, rewards, and terminal conditions.
* Implementation of the SARSA algorithm from scratch.
* Q-table learning for state-action values.
* Visualization of the learned behavior.
* Evaluation of the final greedy policy.

## Technologies Used

* Python
* Reinforcement Learning
* SARSA
* Q-table
* Jupyter Notebook
* Matplotlib
* OpenAI Gym

## Objective

The goal of the project is to demonstrate how an agent can learn an optimal navigation strategy in a risky environment by balancing exploration and exploitation.
