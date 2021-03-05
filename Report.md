[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Training

Below shows average score the agent achieved every 100 episodes. The increasing score value indicates the agent is learning about the environment and adapting his actions to maximise their score. The process took 572 episodes and a total training time of 14 minutes on the udacity workspace with GPU enabled to achieve an average score of 13.03.


```
Episode 100	Average Score: 0.21
Episode 200	Average Score: 2.22
Episode 300	Average Score: 5.70
Episode 400	Average Score: 9.38
Episode 500	Average Score: 11.48
Episode 572	Average Score: 13.03
Environment solved in 472 episodes!	Average Score: 13.03
```

![Screenshot 2021-03-05 at 10 30 37](https://user-images.githubusercontent.com/74315440/110096061-d4e44800-7d9d-11eb-9d32-edd912059548.png)
