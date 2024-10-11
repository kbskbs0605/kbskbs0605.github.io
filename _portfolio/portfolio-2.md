---
title: "Reinforcement Learning in grid world"
excerpt: "Implemented Deep Q-learning Network on grid world <br/><img src='/images/RL_stage.gif'>"
collection: portfolio
---
We implemented Deep Q-learning for agent reaching goal passing obstacles in grid world. We trained MLP to output Q values of four possible actions from input of current coordinate(position) of the agent. This network is trained from the stored history of state-action-reward-next state quadriplet.

![Editing a markdown file for a talk](/images/RL_stage.gif)

Observation from this experiment includes the average return of each episode as the training progresses and the ratio of goal reached episode over timeout episodes.

![Editing a markdown file for a talk](/images/RL_stage.gif)
