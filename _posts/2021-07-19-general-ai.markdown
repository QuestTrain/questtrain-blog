---
layout: post
title: "Where will general AI come from?"
date: 2021-07-19 15:00:00 -0700
categories: background
---

**By: Michael Vogelsong**

Where is general-purpose artificial intelligence going to come from?

First, let's take a look at some of the main candidates:

## Reinforcement Learning (RL)

At this point, many researchers believe RL presents the strongest opportunity for AI. RL is about learning actions to take in an environment, where the learning signal is a scalar reward. This formulation seems to get closest to the idea of "have a numerical proxy of a goal, and optimize an agent's behavior toward that goal." The reward itself can come from a lot of sources, or be a combination of sub-rewards and penalties.

There are variations on the RL formulation -- for example, you can formulate joint rewards to optimize a collection of agents. Or you may introduce certain intrinsic motivations or rewards (e.g., curiousity or surprise), to allow an agent to explore without an extrinsic reward signal.

At this point, we still have many difficulties getting RL to work in more general settings, in the real world.

RL -- under our current algorithms -- is not very sample-efficient. It requires a lot of examples of interaction with the environment to learn policies. This is less of a problem in simulators or games, where you can run environments faster, in parallel, cheaply, and safely. But much more difficult in the real world. The real world runs at one speed, and it may be extremely costly or unsafe to have an agent explore the environment and make mistakes during the learning process. It may not be possible to "reset." And most importantly, there is no game oracle or simulator access to a global reward signal. Instead, we have to come up with proxies for what we believe are rewarding.

## Unsupervised Learning