#### Blackjack

Implementation of the game blackjack as described in Sutton & Barto book Example 5.1 as an Markov Decision Process(MDP). The implementation is based on OpenAI standards for creating an environment.
Two versions of the environment are implemented, one stochastic and other deterministic.

We find the optimal policy for the environment using Q Learning, which is a model free, off policy tabular method to learn the action-state value function for an MDP.