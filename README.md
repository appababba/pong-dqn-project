# Deep Q-Learning on Pong (DQN → Double DQN → Tuned Double DQN)

This repository studies **PongNoFrameskip-v4** using a baseline DQN, a Double DQN variant, and a tuned Double DQN configuration. 

**Starter code:**  
https://github.com/everestso/summer25/blob/main/c166f25_02b_dqn_pong.ipynb


---

## Notebook

- **Final_Pong_Run_v2 (1).ipynb**  
  Full training pipeline: environment preprocessing, frame stacking, replay buffer, DQN architecture, Double DQN option, tuned hyperparameter schedule, logging, curve generation, and video export.

---

## Videos

### Early Behavior
- **Random agent:**  
  [`pong_random.mp4`](pong_random.mp4)

### Baseline and Variant Policies
- **DQN baseline:**  
  [`pong_dqn_baseline.mp4`](pong_dqn_baseline.mp4)

- **Double DQN baseline:**  
  [`pong_ddqn_baseline.mp4`](pong_ddqn_baseline.mp4)

- **Tuned Double DQN (final learned policy):**  
  [`pong_ddqn_tuned.mp4`](pong_ddqn_tuned.mp4)

---

## Learning Curves

- **DQN baseline:**  
  [`pong_dqn_baseline_learning_curve.png`](pong_dqn_baseline_learning_curve.png)

- **Double DQN baseline:**  
  [`pong_ddqn_baseline_learning_curve.png`](pong_ddqn_baseline_learning_curve.png)

- **Tuned Double DQN:**  
  [`pong_ddqn_tuned_learning_curve.png`](pong_ddqn_tuned_learning_curve.png)

---

## Experiment Log

- **experiment_log.csv**  
  Contains hyperparameters, variant names, training lengths, epsilon schedules, and final mean rewards for all runs.

---
