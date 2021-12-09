# RL-application-of-RL

## Overview
1. https://neptune.ai/blog/reinforcement-learning-applications
2. https://towardsdatascience.com/applications-of-reinforcement-learning-in-real-world-1a94955bcd12
2. shortcomings of RL: https://www.alexirpan.com/2018/02/14/rl-hard.html

## Topics
1. self-driving cars
2. industry automation (robots, Deepmind to cool Google Data Centers, s. https://deepmind.com/blog/article/safety-first-ai-autonomous-data-centre-cooling-and-industrial-control)
3. RL in trading and finance (additionally to supervised time series models, an RL agent can determine the action to take at a particular stock price, s. https://medium.com/ibm-data-ai/reinforcement-learning-the-business-use-case-part-2-c175740999)
4. NLP (text summarization, question answering, machine translation)
5. healthcare (patients can receive treatment from policies learned from RL systems, s. https://arxiv.org/pdf/1908.08796.pdf)
6. engineering (personalize suggestions, more meaningful notifications to users, optimize video stream quality, Facebook's Horizon, s. https://engineering.fb.com/2018/11/01/ml-applications/horizon/)
7. news recommendations, s. http://www.personal.psu.edu/~gjz5038/paper/www2018_reinforceRec/www2018_reinforceRec.pdf
8. gaming, s. https://arxiv.org/pdf/1802.09756.pdf
9. robotics (grasp objects - even unseen during training)
10. Resources management in computer clusters, s. https://people.csail.mit.edu/alizadeh/papers/deeprm-hotnets16.pdf 
11. traffic light control, s. http://web.eecs.utk.edu/~ielhanan/Papers/IET_ITS_2010.pdf 
11. Web system configuration, s. https://ranger.uta.edu/~jrao/papers/ICDCS09.pdf
11. Chemistry, s. https://pubs.acs.org/doi/full/10.1021/acscentsci.7b00492
12. Bidding and Advertising, s. https://arxiv.org/pdf/1802.09756.pdf

## Requirements for further RL applications
Understanding your problem: You do not necessarily need to use RL in your problem and sometimes you just cannot use RL. You may want to check if your problem has some of the following characteristics before deciding to use RL: a) trial-and-error (can be learned to do better by receiving feedback from the environment); b)delayed rewards; c)can be modeled as MDP; d)your problem is a control problem.
A simulated environment: Lots of iterations are needed before a RL algorithm to work. I am sure that you don’t want to see a RL agent trying different things in a self-driving car on a highway, right? Therefore, a simulated environment that can correctly reflect the real world is needed.
MDP (Markov decision process): You world need to formulate your problem into a MDP. You need to design the state space, action space, reward function and so on. Your agent will do what it is rewarded to do under the constraints. You may not get the results you want if you design the things differently.
Algorithms: There are different RL algorithms you can choose and questions to ask yourself. You want to directly find out the policy or you want to learn the value function? You want to go model-free or model-based? Do you need to combine other kinds of deep neural network or methods to solve your problems?

## Methods and Algorithms
1. Q-learining, s. https://towardsdatascience.com/simple-reinforcement-learning-q-learning-fcddc4b6fe56
2. QT-Opt https://arxiv.org/abs/1806.10293
2. AWS deepracer, s. https://aws.amazon.com/fr/deepracer/
