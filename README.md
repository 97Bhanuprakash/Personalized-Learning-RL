
# 🎓 Personalized Online Learning System using Reinforcement Learning

## 📌 Project Overview

This project implements a **Personalized Online Learning System** using **Reinforcement Learning (RL)** techniques. The goal is to simulate and optimize learning content recommendations for students by modeling their performance, behavior, and engagement in an educational setting.

Reinforcement Learning provides a framework where a learning agent can **interact with students' data** as an environment, receiving feedback in the form of rewards to improve future decision-making. The ultimate objective is to maximize long-term student success through personalized and adaptive learning paths.

## 🤖 What is Reinforcement Learning?

**Reinforcement Learning (RL)** is a subset of machine learning where an agent learns to make decisions by **interacting with an environment** and receiving feedback in the form of rewards. The agent’s goal is to learn a **policy** that maximizes cumulative rewards over time.

### Core Components of RL:
- **Agent**: The learner or decision-maker (e.g., a recommendation system)
- **Environment**: The context or system the agent interacts with (e.g., student records and behavior)
- **Policy**: The strategy the agent uses to determine actions
- **Reward Signal**: Feedback given to the agent to evaluate its actions

## 📂 Dataset Description

**Dataset Source**: [Kaggle - Students Grading Dataset](https://www.kaggle.com/datasets/mahmoudelhemaly/students-grading-dataset?utm_source=chatgpt.com)

This dataset contains **~5000 real-world records** from a private learning provider, offering a wide range of variables suitable for personalized learning simulations. It includes multiple files:

- `Metadata.csv`
- `Student Performance Dataset (CSV and JSON)`
- `Students_Grading_Dataset_Biased (CSV and JSON)`

### Key Features:
- **23 columns** of student interaction and demographic data
- Variables include: quiz scores, multiple attempts, engagement timing, and more
- Fine-grained **student-level granularity**
- Ideal for **modeling state transitions**, **rewards**, and **policy learning** — all critical for reinforcement learning

## 🎯 Why This Topic Was Chosen

- **Rich Educational Dataset**: Includes real behavioral patterns and performance metrics
- **Highly Interactive Data**: Captures detailed student interactions, such as time spent and multiple attempts
- **Personalization Potential**: Enables the development of individualized learning strategies
- **RL Applicability**: Offers the ability to simulate dynamic decision-making via state transitions and feedback loops
- **Real-World Impact**: Addresses the growing need for adaptive learning in modern education platforms

## 🏗️ System Design

1. **State**: Combination of a student's current performance, engagement, and topic history
2. **Action**: Recommend a learning activity (e.g., video, quiz, reading material)
3. **Reward**: Improvement in score, reduced time to complete, or number of attempts
4. **Policy**: A strategy learned by the agent to maximize student improvement

## 💡 Project Goals

- Build a **simulation environment** representing student behavior
- Implement RL agents (e.g., Q-learning, DQN) to optimize learning recommendations
- Evaluate and compare policy performance based on cumulative rewards
- Visualize and analyze learning improvements over episodes

## 📈 Tools and Libraries

- Python (NumPy, Pandas, Seaborn, Matplotlib)
- PyTorch (for DQN implementation)
- Scikit-learn (for baseline models and preprocessing)
- Power BI (for visual dashboards and performance reporting)

## ✅ Outcomes

- Developed a working DQN-based recommender agent
- Visualized agent training performance using reward curves
- Achieved improved student learning trajectories in simulation
- Demonstrated value of RL in educational recommendation systems

## 📎 Future Improvements

- Integration with real-time dashboards (Power BI + Python backend)
- Incorporation of NLP-based feedback analysis (from open text fields)
- Exploration of policy gradient methods (e.g., PPO)
- Deployment-ready interactive learning environment

## 📚 Keywords

`Reinforcement Learning` `Personalized Education` `DQN` `Student Behavior Modeling` `Power BI` `Education Analytics` `Q-learning` `RL Simulation` `Adaptive Learning`

## 🔗 Repository Navigation (Recommended Sections)

```
📁 /data                → Dataset files (CSV, JSON, Metadata)
📁 /notebooks           → RL simulations, EDA, preprocessing
📁 /models              → DQN model and supporting scripts
📁 /visualizations      → Power BI exports and reward plots
📄 README.md            → Project overview and documentation
```

## 🧠 Contact

For questions or collaboration:
- 📧 bhanu.gandla@ue-germany.de
- 📍 Berlin, Germany
