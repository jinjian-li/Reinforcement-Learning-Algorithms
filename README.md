# Reinforcement Learning & Stochastic Optimization Algorithms

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20RL-red)](https://pytorch.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## 📖 Overview

This repository contains implementations of fundamental and advanced **Reinforcement Learning (RL)** algorithms, developed as part of the Master's coursework in Machine Learning and Robotics. 

The project bridges the gap between **mathematical derivation** and **practical implementation**, progressing from classical tabular methods to state-of-the-art Deep RL algorithms (SAC) and Stochastic Search methods for robotic control.

## 🗂️ Project Modules

The codebase is organized into four main modules. Each implementation is self-contained in a Jupyter Notebook with detailed mathematical explanations.

| Module | Algorithm / Technique | Key Concepts |
| :--- | :--- | :--- |
| **01. Tabular RL** | **Q-Learning, SARSA** | Bellman Equation, Value Iteration, Off-policy Control |
| **02. Policy Gradients** | **REINFORCE** | Neural Networks, Policy Optimization, Monte Carlo Sampling |
| **03. MDP Design** | **SAC (Soft Actor-Critic)** | **Reward Shaping**, Continuous Control, Max-Entropy RL |
| **04. Stochastic Search** | **Natural Gradient (NPG)** | Information Geometry, KL-Divergence, Trust Region |

---

## 💻 Implementation Details

### 1. Tabular RL & Foundations
* **Focus:** Solving discrete environments (GridWorld) using dynamic programming.
* **Key Implementation:**
    * Analyzed convergence properties of TD-error.
    * Compared On-policy (SARSA) vs. Off-policy (Q-Learning) strategies.

### 2. Deep Policy Gradients (REINFORCE)
* **Focus:** Scaling RL to continuous action spaces using Neural Networks.
* **Key Implementation:**
    * Implemented the **REINFORCE** algorithm from scratch using **PyTorch**.
    * Designed a Gaussian Policy Network for continuous control tasks.
    * Applied variance reduction techniques to stabilize training.

### 3. MDP Design & Soft Actor-Critic (SAC)
* **Focus:** Designing the Markov Decision Process (MDP) for a complex robotic task.
* **Key Implementation:**
    * **Reward Shaping:** Engineered a dense reward function for a Multi-phase Reacher task.
    * **Algorithm:** Deployed **Soft Actor-Critic (SAC)** for sample-efficient learning.
    * **Result:** Successfully trained the agent to reach dynamic targets with high precision.

### 4. Stochastic Search & Natural Gradients
* **Focus:** Optimization beyond standard backpropagation using Information Geometry.
* **Key Implementation:**
    * Derived the closed-form solution for **Information Geometric Policy Update**.
    * Implemented **MORE (Model-Based Relative Entropy)** stochastic search.
    * Utilized **KL-Divergence** constraints to ensure safe policy updates (Trust Region).

---

## 🛠️ Tech Stack & Dependencies

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
