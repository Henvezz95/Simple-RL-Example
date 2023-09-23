# Simple-RL-Example
The repository contains a simple example of Black-Box function approximation using Reinforcement Learning. The technique used is based on the algorithm of [Deep Deterministic Policy Gradient](https://arxiv.org/abs/1509.02971), but for this application, the algorithm can be simplified since there are no future states. The final solution is a simple Actor-Critic algorithm that can approximate a continuous Black-Box function with a Neural Network.
![Actor-Critic](https://github.com/Henvezz95/Simple-RL-Example/blob/main/Actor-Critic.png)

# Problem Overview - Car Tank Leakage
A car has a tank leakage. The car is moving at constant speed v toward the mechanic shop. The air resistance is proportional to the cube of the velocity. The leakage rate is constant. Find the speed that minimizes fuel consumption and maximizes the chance of arriving at the mechanic in time before the car stops, given the air resistance and the leakage rate.
![Car](https://github.com/Henvezz95/Simple-RL-Example/blob/main/car.png)

