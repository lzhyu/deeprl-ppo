This is an implementation of [proximal policy optimization](https://arxiv.org/abs/1707.06347).   I made this as part of my work getting up to speed in Deep RL under a grant from the [Machine Intelligence Research Institute](https://intelligence.org/).  I left many of my debug notes in intentionally, in hopes they might be helpful to anyone else attempting a similar project.  Also see [my postmortem](https://coreystaten.com/2018/10/03/ppo-postmortem.html) for a breakdown of (known) errors made during the implementation.

If all prerequisites are installed, type "python ppo.py" to run in the default configuration on Pong.

Here's a graph of performance on Pong with the default configuration:

![PPO performance graph for Pong](http://coreystaten.github.io/assets/ppo.png)

Note this uses 8 actors, so timestep t corresponds to 8\*t samples.
