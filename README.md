# Reinforcement Learning & Stochastic Optimization Algorithms

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20RL-red)](https://pytorch.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📖 Overview

This repository contains implementations of fundamental and advanced **Reinforcement Learning (RL)** algorithms. The project progresses from classical tabular methods to state-of-the-art Deep RL algorithms (SAC) and Stochastic Search methods.

> **💡 Note for Reviewers:**
> This repository contains **extensive visualization results** (over 100+ plots).
> To keep this README clean, please click the links below to view specific result graphs or open the Notebooks for full implementation details.

---

## 🗂️ Project Modules & Results

### 1. Tabular RL & Foundations
* **Algorithm:** Value Iteration, Policy Iteration, Q-Learning (Off-policy).
* **Code:** [📄 01_Tabular_RL_Fundamentals.ipynb](01_Tabular_RL_Fundamentals.ipynb)
* **Key Results (Click to view):**
    * [📈 Policy Iteration Convergence](assets/policy_iteration.png)
    * [📈 Value Iteration Convergence](assets/value_iteration.png)
    * [📈 Q-Learning Performance](assets/q_learning.png)

### 2. Deep Policy Gradients (REINFORCE)
* **Algorithm:** REINFORCE (Monte Carlo Policy Gradient) with Baseline.
* **Code:** [📄 02_Deep_Policy_Gradients_REINFORCE.ipynb](02_Deep_Policy_Gradients_REINFORCE.ipynb)
* **Key Results (Click to view):**
    * [📊 Deep Policy Gradients Training Curve](assets/deep_policy_gradients.png)
    * [📊 Natural Policy Gradient Comparison](assets/natural_policy_gradient.png)
    * [📊 REINFORCE Algorithm Performance](assets/reinforce.png)
    * [📜 Policy Gradient Theorem Derivation](assets/policy_gradient_theorem.png)

### 3. MDP Design & Soft Actor-Critic (SAC)
* **Algorithm:** Soft Actor-Critic (SAC), Reward Shaping, Continuous Control.
* **Code:** [📄 03_MDP_Design_SAC.ipynb](03_MDP_Design_SAC.ipynb)
* **Key Results (Click to view):**
    * [🤖 Multiphase Reacher Robot Demo](assets/Q4_multiphase_reacher.png)
    * [📉 Infinite Horizon Analysis](assets/Q3a_infinite-horizon.png)
    * [📉 Discount Factor Analysis](assets/Q3c_discount.png)

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Deep Learning:** PyTorch
* **Simulation:** Gymnasium (OpenAI Gym), MuJoCo
* **Math:** NumPy, SciPy

## 🚀 How to Run

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YourUsername/Reinforcement-Learning-Algorithms.git](https://github.com/YourUsername/Reinforcement-Learning-Algorithms.git)
    ```
2.  Install dependencies:
    ```bash
    pip install numpy torch matplotlib gymnasium stable-baselines3
    ```
3.  Open the notebooks:
    ```bash
    jupyter notebook
    ```

---

## 📬 Contact

**Master Student in Mechatronics & AI** Focus: Robotics, Control Systems, and Deep Learning.
