# Crafter RL Project – PPO & A2C Training

This project demonstrates **training and evaluating two reinforcement learning algorithms** on the [Crafter](https://github.com/danijar/crafter) environment using [Stable-Baselines3](https://stable-baselines3.readthedocs.io/).

The goal is to teach students how to:
- Train an RL agent on a **seen environment** using one algorithm (PPO).
- Test generalization on **unseen environments** (different random seeds) with a second algorithm (A2C).
- Compare performance across algorithms to understand **robustness and generalization**.

---

## 🧠 Learning Objectives

By the end of this project, students should be able to:
- Understand the difference between **training on seen data** vs. **evaluating on unseen data**.
- Configure and run **two RL algorithms** (PPO & A2C) on the same environment.
- Analyze results by comparing performance across **seen** and **unseen seeds**.

---

## 📦 Features

- **Parallelized training** with `SubprocVecEnv` (auto-scales to available CPU threads).
- **Two algorithms implemented:**
  - **PPO (Proximal Policy Optimization)** — trained on seen seed(s).
  - **A2C (Advantage Actor-Critic)** — trained and compared for generalization.
- **Evaluation on unseen seeds** to measure generalization ability.
- **TensorBoard logging** for both algorithms.

---

## 🛠 Setup

### 1. Clone the Project
```bash
git clone <your-repo-url>
cd Crafter_Project

