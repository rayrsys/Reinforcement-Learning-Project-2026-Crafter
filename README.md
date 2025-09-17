# Reinforcement-Learning-Project-2026-Crafter
# Crafter PPO Training (Stable-Baselines3)

This project trains a reinforcement learning agent using **Proximal Policy Optimization (PPO)** on the [Crafter](https://github.com/danijar/crafter) environment.  
It supports **parallel environment rollouts** (for faster training) and is portable across local machines and HPC clusters.

---

## 📦 Features

- **Parallelized PPO** with `SubprocVecEnv` (automatically scales to CPU threads).
- **Automatic log directory management** (separate log folder per environment).
- **TensorBoard support** for live monitoring.
- **Conda environment YAML** for reproducibility.
- Compatible with **GPU (CUDA)** or CPU-only training.

---

## 🛠 Setup

### 1. Clone the Project
```bash
git clone <your-repo-url>
cd Crafter_Project
