# Reinforcement-Learning-Based-Path-Planning-for-a-Robot
This project is about finding the optimal path between a start point and an endpoint in an environment with blocks. Reaching the end goal has a reward, and hitting or moving close to the obstacles has negative rewards (punishments). Also, there is little punishment for moving for the robot. 

The Monte-Carlo algorithm for finding the optimal policy for any place is as follows:
![This is an image](/Images/monte-carlo.png)

Next, we are going to take a smarter approach based on reinforcement learning to teach the robot the optimal path. In this method, the robot learns the optimal policy for each place through policy iteration.
![This is an image](/Images/RL.png)

The algorithm for policy iteration is as follows:
![This is an image](/Images/policy_iter.png)
