# 🚀 ART_Projects

This repository contains interactive Jupyter Notebooks that explore **Agent Reinforcement Trainer (ART)** — a framework for training *language model (LLM) agents* using **reinforcement learning (RL)**. The goal of this repo is to provide runnable examples of how ART can be used for training, evaluating, and experimenting with agentic workflows.

ART (Agent Reinforcement Trainer) is an open‑source RL framework that helps developers train LLM‑based agents to improve performance and reliability through experience. It provides easy‑to‑use abstractions and tools for integrating RL into agent workflows — allowing agents to learn from interactions rather than relying solely on static prompts. :contentReference[oaicite:1]{index=1}

---

## 📖 Notebooks Overview

### 🧪 `art_call.ipynb`

This notebook demonstrates a **basic ART workflow**:

- How to configure an ART training session
- How to send agent rollouts to ART for reinforcement updates
- How to inspect intermediate rewards and policy updates
- Basic examples of agent behavior improvement over training

This notebook is ideal as a starting point if you are new to ART and want to see how reinforcement learning can influence agent performance.

---

### 🤖 `art_call_custom_judge.ipynb`

This notebook extends the basic workflow by introducing:

- A **custom judge function** (custom reward evaluator)
- Task‑specific evaluation logic
- How to guide an agent towards your own scoring criteria instead of default rewards

Useful for scenarios where you want **more control over agent learning signals**, such as task‑specific QA, planning constraints, or domain priorities.

---

## 🧠 What You’ll Learn

By working through the notebooks, you will:

- Set up and interact with ART’s client & backend training loop
- Understand how reinforcement learning lets LLM agents *learn from experience*
- Integrate custom scoring (judges or evaluators) for agent behavior
- Debug, monitor, and interpret agent trajectories and reward signals

ART’s design supports seamless RL integration and abstracts complex elements like environments, rollouts, and policy optimization. :contentReference[oaicite:2]{index=2}

---

## 🛠 Getting Started

To run the notebooks locally:

1. Clone this repository  
   ```bash
   git clone https://github.com/venetisgr/ART_Projects.git
