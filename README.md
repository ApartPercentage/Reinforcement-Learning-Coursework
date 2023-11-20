# Reinforcement-Learning-Coursework

This coursework analyzes various reinforcement learning algorithms (MDP solvers, Monte Carlo, Q-learning, DQN, REINFORCE, and DDPG) to provide insights into their effectiveness and implementation.

# Hyperparameters

In this coursework, the optimal hyperparameters for the following algorithms are as shown:

Monte Carlo : 
* Epsilon, 0.6
* Gamma, 0.99

Q-Learning : 
* Epsilon, 0.6
* Gamma, 0.99
* Frequency, 5000

REINFORCE (on Bipedal environment) : 
* learning rate, 6e-3 

DQN (on CartPole environment) : 
* Epsilon Expoenetial decay strategy,exploration fraction: 0.01
* Epsilon Linear decay strategy ,exploration decay: 0.001

DDPG (on Bipedal environment): 
* Critic Hidden Layer
* Policy Hidden Layer

After tuning the DDPG (on Bipedal environment): 
* Policy leanring rate, 1e-3
* Critic leanring rate, 1e-2
* Critic Hidden Layer, [400,300]
* Policy Hidden Layer, [400,300]
* Gamma, 0.99
* Tau, 0.1
* Batch Size, 128
* Buffer Capacity, 1e6
