# Reinforcement learning (RL)
![](https://bigdata-madesimple.com/wp-content/uploads/2018/02/Machine-Learning-Explained3.png)

## What is reinforcement learning?

Reinforcement learning (RL) is the subfield of machine learning concerned with decision making and motor control. 
It studies how an agent can learn how to achieve goals in a complex, uncertain environment.To get the machine to do what the programmer wants, the AI gets either rewards or penalties for the actions it performs. 
Its goal is to maximize the total reward.
It’s exciting for two reasons:

+ RL is very general, encompassing all problems that involve making a sequence of decisions.
For example, controlling a robot’s motors so that it’s able to run and jump, making business decisions like pricing and inventory management, or playing video games and board games. 
RL can even be applied to supervised learning problems with sequential or structured outputs.

+ RL algorithms have started to achieve good results in many difficult environments. RL has a long history, but until recent advances in deep learning, it required lots of problem-specific engineering. 
AlphaGo used deep RL algorithms which did not make too many assumptions about its environment, and thus can be applied in other settings.

## How does reinforcement learning work?
Reinforcement Learning is a very different type of ml from classic supervised and unsupervised. The key distinguishing factor of reinforcement learning is how the agent is trained. The learning system, called an agent in this context, can observe the environment, select and perform actions, and get rewards in return (or penalties in the form of negative rewards). It must then learn by itself what is the best strategy, called a policy, to get the maximum amount of rewards over time. A policy defines what action the agent should choose when it is in a given situation.


![](https://theaisummer.com/static/65d20186191a40d02e301a1dcc6c726b/ac25c/RL.jpg)

For a  given  environment and an agent (the thing that's going to move around in the environment) acting in the environment, the agents chooses actions (one at a time). 
Once an agent makes an action, the environment will accept this action(s) and then it transitions to its next state. 
We can think of a state as an observation on the environment. 
So going back to our example, the environment was the tic-tac-toe board, and I am the agent who chose to put an "o" in the middle of the board and once I choose that action the environment is updated and the next state is a picture of the board with an "o" in the middle.

So when an agent makes an action it changes the environment or can change the environment and that change in the environment regardless if it actually does change or not  gives you a new state. So new action new state and moreover for each action that the agent chooses to do, this new state then gives the agent a reward.  

State -> Action -> Reward
    (s_t, a_t, r_t)
