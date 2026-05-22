# Cliff-Walking Q-Learning Agent

A Python-based reinforcement learning project that trains an AI agent to find the optimal path across a grid without falling off a cliff. Built with Gymnasium, this notebook showcases the step-by-step mathematical implementation of the Q-Learning algorithm and tracks the agent's performance improvements over time.

## 🚀 Features
* **Custom Algorithm implementation:** Implements the classic Q-Learning algorithm from scratch without relying on high-level RL libraries.
* **Exploration vs. Exploitation:** Utilizes an epsilon-greedy policy to balance discovering new paths and optimizing known routes.
* **Performance Tracking:** Logs and evaluates the total reward and episode length across 500 training episodes.
* **Testing Phase:** Includes a final evaluation loop to demonstrate the agent's learned optimal path using the populated Q-table.

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** * `gymnasium` (for the CliffWalking-v1 environment)
  * `numpy` (for Q-table matrix operations)
  * `random` (for the exploration policy)

## ⚙️ Hyperparameters Used
* **Discount Factor (Gamma):** `0.99`
* **Learning Rate (Alpha):** `0.5`
* **Exploration Rate (Epsilon):** `0.1`
* **Training Episodes:** `500`



