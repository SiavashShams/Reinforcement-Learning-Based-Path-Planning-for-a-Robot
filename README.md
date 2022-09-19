# Reinforcement-Learning-Based-Path-Planning-for-a-Robot
This project is about finding the optimal path between a start point and an end point in an environment with blocks. Reaching the end goal has a reward, and hitting or moving close to the obstacles has negative rewards (punishments). Also, there is a small punishment for moving for the robot. 
------
The monte-carlo algorithm for finding the optimal policy for any place is as follows:
![This is an image](/Images/monte-carlo.png)

Next we are going to take an smarter approach based on reinforcement learning to teach the robot the optimal path. In this method the robot learns the optimal policty for each place through policy iteration.
![This is an image](/Images/RL.png)

the algorithm for policy iteration is as follows:
![This is an image](/Images/policy_iter.png)
