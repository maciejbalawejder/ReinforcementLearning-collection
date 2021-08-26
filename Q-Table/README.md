![working](https://user-images.githubusercontent.com/47450700/113194920-92f1d900-9259-11eb-9419-78171d0d7e59.gif)
# CartPole-v0
-------
This is a solution for OpenAI's CartPole-v0 using Q-learning and Deep Q-Networks. 

Check out the article with in depth explanation: [Solving OpenAI's Cart-Pole using Q-learning Part 1](https://medium.com/analytics-vidhya/q-learning-is-the-most-basic-form-of-reinforcement-learning-which-doesnt-take-advantage-of-any-8944e02570c5)

## Definition of the problem 
> A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The system is controlled by applying a force of +1 or -1 to the cart. The pendulum starts upright, and the goal is to prevent it from falling over. A reward of +1 is provided for every timestep that the pole remains upright. The episode ends when the pole is more than 15 degrees from vertical, or the cart moves more than 2.4 units from the center.

## Q-Learning 
### __Hyperparameters__: => solved with these values by 28000 episode with average reward above 195. 
- Learning rate = 0.15
- Gamma = 0.995
- Epsilon = 0.15
### __Performance graph__ 
![Plot](https://user-images.githubusercontent.com/47450700/113200192-ec5d0680-925f-11eb-880f-80d80fc54311.png)

## Deep Q-Learning
------------
### __Hyperparameters__
![hyperparameters](https://user-images.githubusercontent.com/47450700/115386166-f627b900-a1d0-11eb-89e1-1e3830a8cfb2.PNG)

### __Testing model graph__ 
![TEST_policy_network](https://user-images.githubusercontent.com/47450700/115384925-7c430000-a1cf-11eb-9d4b-82ca37fef3b9.png)


