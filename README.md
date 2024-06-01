# Multiobjective RL-Based Wireless Routing Optimization

## Project Overview

This project implements a reinforcement learning algorithm designed to find the Pareto Optimal Front in the context of wireless network routing. The approach leverages multi-objective reinforcement learning (MORL) to optimize various metrics such as latency and data throughput, crucial for efficient network management.

## Features

- **Pareto Optimal Front**: Identification of non-dominated solutions considering multiple objectives.
- **Q-learning**: Implementation of Q-learning to optimize decision-making without a model of the environment.
- **Customizable Network Simulation**: Simulate different network scenarios by adjusting parameters like grid size and delay distributions.

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed along with the following packages:
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Algorithm Explanation
The algorithm initializes a grid-based simulation environment representing a wireless network. Each cell in the grid represents a network node. The RL agent navigates through this network, making routing decisions at each step to optimize the defined objectives. The learning process is based on the Q-learning algorithm, where the Q-values represent the utility of taking a certain action at a particular state.

## Key Components
State Space: Defined by the position in the grid.
Action Space: Includes possible moves (up, down, left, right).
Rewards: Configured to reflect the network's performance metrics like delay and throughput.

 ## Contact
For any queries or further assistance, please reach out through GitHub issues or directly contact on preetgupta189@gmail.com.
