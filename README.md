# Power4_AI

The goal here is to code a simple (not optimal) implementation of the famous Connect 4 game https://en.wikipedia.org/wiki/Connect_Four

We will train a pair of agents against each other with Reinforcement Learning to learn the game.
Notice that we take an 8X8 grid instead of a 6X7 one to probe something new.

Performance is evaluated against a random agent at the moment.

Learning is made via a simple DQN model with standard hyperparameters.

Further improvements:

- Try out other models like TRPO
- Hyperparameters optimization
- More self-play history to gather
- Diversity in self-play : swap out the agents from time to time to learn diverse strategies
- Robust performance tracking by making the agent play against past versions of itself
