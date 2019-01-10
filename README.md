# Self-Driving-car
self driving car using Reinforcement Learning (Q- Learning)

The AI car senses the environment(i.e. its distance from the goal, the distance and presence roadside boundaries etc.), takes actions 
(go sraight, left, right) depending on the situation and receives rewards from the environment (+5 if car reaches the goal, -1 if car 
hit the boundaries, -2 if car hits the roadside, +0.5 if car's distance from goal is less than its distance at last instance or -0.1 
otherwise i.e. negative reward for time spent)
Using Reinforcement learning(RL) car learns from its mistakes appropriate and less appropriate actions to take  while in particular 
situation. Q-Learning is the type of RL algorithm used in this project.
Experience Replay is the additional technique used to allow AI to learn from the 'rare experiences'. This technique stores the 
past experience in the memory and learn from it by sampling random entries from it.

Currently the car can tackle a path as complex as shown in the screenshot uploaded. Further development can be done using more advance 
techniques such as reward engineering, addnig additional sensory inputs such as 'time spent' starting from the inintial point which 
will compail car to search for the shortest path.

Environment: Python, Pytorch, Kivy(for UI)

References: Udemy AI course

Email: paras.v.prabhu@gmail.com
