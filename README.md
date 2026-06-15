# 🚀 Infotact Technical Internship Program 2026

## Advanced Data Science & Machine Learning Projects

> Building enterprise-grade AI solutions through rigorous experimentation, reproducible pipelines, and professional ML engineering practices.

---

## 📌 About

This repository contains the implementation of the **Infotact Technical Internship Program – Advanced Data Science & Machine Learning Projects**.

The internship focuses on solving real-world business problems using modern AI techniques, including:

* Predictive Maintenance using IoT and Contextual Data Fusion
* Reinforcement Learning for Dynamic Pricing
* Geospatial Real Estate Valuation using Graph Neural Networks

The projects are designed to simulate the workflow followed by deep-tech startups and AI teams, emphasizing:

* End-to-end ML pipelines
* Weekly engineering sprints
* Experiment tracking
* GitHub issue management
* Version control best practices
* Production-oriented development

---

# 🛠 Tech Stack

### Languages

* Python 3.x

### Machine Learning

* Scikit-learn
* LightGBM
* XGBoost
* Imbalanced-learn (SMOTE)

### Deep Learning

* PyTorch
* DGL / PyTorch Geometric

### Reinforcement Learning

* Gymnasium / OpenAI Gym
* DQN
* Q-Learning
* PPO (Optional)

### Geospatial Analytics

* GeoPandas
* Shapely
* Folium
* Kepler.gl

### Visualization

* Matplotlib
* Seaborn
* SHAP

### Deployment

* Streamlit

### Version Control

* Git
* GitHub Projects
* GitHub Issues

---

# 📂 Repository Structure

```
├── Project-1-IoT-Predictive-Maintenance/
├── Project-2-Dynamic-Pricing-RL/
├── Project-3-Geospatial-Valuation/
├── notebooks/
├── src/
├── docs/
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 📌 Project 1: Contextual Predictive Maintenance (IoT Edge AI)

## Objective

Develop an intelligent predictive maintenance system by combining:

* Internal IoT telemetry
* External environmental signals

to predict machine failures before they occur.

---

## Key Features

✅ Time-series signal processing

✅ Contextual data fusion

✅ Feature engineering

✅ LightGBM classification

✅ SMOTE within Cross Validation

✅ SHAP explainability

✅ Noise robustness testing

---

## Evaluation Metric

**Target Macro F1 Score:**

```
Macro F1 ≥ 0.85
```

even under moderate noise conditions.

---

## Weekly Roadmap

### Week 1

* IoT telemetry ingestion
* Rolling statistics generation

### Week 2

* External data integration
* Contextual feature engineering
* Ablation study

### Week 3

* Stratified 5-Fold Cross Validation
* SMOTE implementation
* LightGBM training

### Week 4

* Noise sensitivity analysis
* Precision-Recall optimization
* Threshold tuning

---

# 📌 Project 2: Reinforcement Learning for Dynamic Pricing

## Objective

Train an autonomous pricing agent capable of maximizing revenue for finite inventory businesses such as:

* Airlines
* Hotels
* Event ticketing platforms

---

## Key Features

✅ Custom Gym Environment

✅ MDP formulation

✅ Baseline heuristic pricing

✅ Q-Learning

✅ Deep Q-Network (DQN)

✅ Experience Replay

✅ Epsilon-Greedy Exploration

✅ Revenue optimization dashboard

---

## Evaluation Metric

The RL agent must outperform baseline pricing strategies using:

```
Total Episodic Reward
(Total Revenue Generated)
```

---

## Weekly Roadmap

### Week 1

* MDP design
* Gym environment creation

### Week 2

* Fixed-price baselines
* Q-Learning implementation

### Week 3

* DQN development
* Experience replay

### Week 4

* 1,000 season simulations
* Policy comparison
* Price trajectory visualization

---

# 📌 Project 3: Geospatial Real Estate Valuation

## Objective

Build a next-generation Automated Valuation Model (AVM) capable of learning spatial relationships between properties.

---

## Key Features

✅ GeoPandas processing

✅ Haversine distance calculations

✅ Interactive geospatial visualization

✅ XGBoost baseline

✅ K-Nearest Neighbor Graphs

✅ Spatial embeddings

✅ Graph Neural Networks

✅ Streamlit deployment

---

## Evaluation Metric

Primary success metric:

```
Mean Absolute Percentage Error (MAPE)
```

The spatial model must outperform traditional ML baselines.

---

## Weekly Roadmap

### Week 1

* Geospatial preprocessing
* Interactive mapping

### Week 2

* Baseline feature engineering
* XGBoost training

### Week 3

* Graph construction
* Spatial embeddings

### Week 4

* GNN/Attention model training
* Streamlit dashboard deployment

---

# 📊 GitHub Workflow & Contribution Standards

## GitHub Projects

A Kanban Board is maintained with:

* To Do
* In Progress
* Done

Each task is tracked using GitHub Issues.

---

## Commit Standards

Commit frequently:

```
3–5 commits per active development day
```

Example:

```
feat: implement SMOTE inside cross-validation folds (fixes #4)

model: train DQN agent with experience replay (fixes #8)

docs: update Streamlit deployment instructions (fixes #12)
```

---

## Notebook Guidelines

Before committing notebooks:

* Restart Kernel
* Clear Outputs

or use:

```
nbstripout
```

---

## Data & Model Management

The following directories are excluded using `.gitignore`:

```
data/
models/
```

Large datasets and model weights should not be pushed to GitHub.

---

# 🎯 Learning Outcomes

By completing these projects, I aim to strengthen my expertise in:

* Machine Learning Engineering
* Reinforcement Learning
* Graph Neural Networks
* Explainable AI
* Time-Series Analytics
* Geospatial Intelligence
* MLOps Best Practices
* Professional GitHub Collaboration

---

## 📜 Internship Evaluation Requirement

⚠️ Evaluation is based not only on final deliverables but also on maintaining a transparent and consistent development lifecycle through all four weeks of GitHub contributions.

---

## 👨‍💻 Author

**Tamilarasan**

B.Tech – Computer Science & Engineering
SRM Institute of Science and Technology, Chennai

GitHub: https://github.com/tamil1208

LinkedIn: https://www.linkedin.com/in/tamil-arasan-a2466b274

---

⭐ If you find this repository useful, consider giving it a star!

