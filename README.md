Deep Q-Learning on Pong (DQN → Double DQN → Tuned Double DQN)

This repository contains a complete reinforcement-learning study of Atari PongNoFrameskip-v4 using a baseline DQN, a Double DQN variant, and a tuned Double DQN configuration. The code is derived from the course starter notebook:

Starter code:
https://github.com/everestso/summer25/blob/main/c166f25_02b_dqn_pong.ipynb

The project includes:

a reproducible notebook,

learning curves for each experimental condition,

short videos showing early/random behavior and trained policies,

an experiment log with hyperparameters and final returns.

Notebook

Final_Pong_Run_v2 (1).ipynb
Complete training script: environment setup, replay buffer, DQN architecture, Double DQN option, tuned hyperparameters, logging, plotting, and video generation.

Videos
Early behavior

Random agent:
pong_random.mp4

Baseline and variant evaluations

DQN baseline:
pong_dqn_baseline.mp4

Double DQN baseline:
pong_ddqn_baseline.mp4

Tuned Double DQN (final, stable policy):
pong_ddqn_tuned.mp4

Learning Curves

DQN baseline:
pong_dqn_baseline_learning_curve.png

Double DQN baseline:
pong_ddqn_baseline_learning_curve.png

Tuned Double DQN:
pong_ddqn_tuned_learning_curve.png

Experiment Log

experiment_log.csv
Contains run names, hyperparameters, training lengths, epsilon schedules, and final mean returns.
