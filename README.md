# Building Reinforcement Learning Trading Model

## Introduction

This project is a reinforcement learning trading model that uses the OpenAI Gym environment to simulate trading. The model uses a deep Q-learning algorithm to learn the optimal trading strategy. The model is trained on historical stock price data and learns to maximize the cumulative returns by taking long and short positions in the stock.

## Project Steps

1. Setup and Data Preparation: You will begin by setting up your development environment and preparing historical market data for training your agent.
2. Environment Design: Next you will create a simulated trading environment where your agent can learn and test its strategies.
3. Agent Implementation: You will then encode the DQN model, defining the neural network architecture and training loop.
4. Training the Agent: Once all components are complete, you get to train your agent using historical data. For this project, we will be using a small dataset and a low number of training rounds, in order to save time and focus on the process of building our agent and training loop.
5. Evaluation and Testing: Finally, you will evaluate your agent's performance through a single validation test.