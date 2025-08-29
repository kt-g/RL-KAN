# Offline Reinforcement Learning with Kolmogorov-Arnold Networks

This is our final project for **10-701: Introduction to Machine Learning** as taught by Geoff Gordon and Nina Balcan at CMU in Fall 2024.

The purpose of the project is to explore whether [Kolmogorov-Arnold Networks (KANs)](https://arxiv.org/pdf/2404.19756) can offer similar performance to Multi-Layer Perceptrons (MLPs) while using fewer parameters. We focused on performance for offline reinforcement learning, specifically for the [Behavioral Proximal Policy Optimization (BPPO)](https://arxiv.org/pdf/2302.11312) algorithm. To do this, we train and evaluate our models using [Gymnasium MuJoCo's Hopper](https://gymnasium.farama.org/environments/mujoco/hopper/) dataset. 

We draw heavily from these prexisting codebases:
- https://github.com/Dragon-Zhuang/BPPO for our base code and BPPO implementation
- https://github.com/Blealtan/efficient-kan for an efficient implementation of KANs
