# 🚀 Infotact Technical Internship Program 2026.

## Advanced Data Science & Machine Learning Projects

> Building enterprise-grade AI solutions through rigorous experimentation, reproducible pipelines, and professional ML engineering practices.

----

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

----

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

----

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
#🚀 Manufacturing & Automotive – Contextual Predictive Maintenance (IoT Edge AI)

#🚀 Contextual Predictive Maintenance using IoT Edge AI
Advanced Data Science & Machine Learning Project

#🔗 Live Dashboard: https://predictivemaintencedashborad.netlify.app/

## Advanced Data Science & Machine Learning Project

> Predicting machine failures before they occur using IoT telemetry, feature engineering, machine learning, and Explainable AI.

---

## 🌐 Live Dashboard

🔗 https://predictivemaintencedashborad.netlify.app/

---

## 📌 Project Overview

This project develops an intelligent predictive maintenance system for manufacturing and automotive environments. By analyzing machine sensor telemetry and engineered features, the system predicts potential machine failures and provides actionable maintenance insights.

The solution combines machine learning, data analytics, and Explainable AI (SHAP) to improve operational efficiency and reduce unexpected downtime.

---

## 🎯 Business Problem

Unexpected machine failures can lead to:

* Production downtime
* Increased maintenance costs
* Equipment damage
* Reduced operational efficiency

This solution helps maintenance teams identify risks early and schedule preventive maintenance before failures occur.

---

## 📊 Dataset

### AI4I 2020 Predictive Maintenance Dataset

**Features:**

* Air Temperature
* Process Temperature
* Rotational Speed (RPM)
* Torque
* Tool Wear
* Product Type

### Target Variable

* Machine Failure (0 = Normal, 1 = Failure)

### Failure Types

* Tool Wear Failure (TWF)
* Heat Dissipation Failure (HDF)
* Power Failure (PWF)
* Overstrain Failure (OSF)
* Random Failure (RNF)

---

## 🛠️ Technology Stack

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Machine Learning

* Scikit-Learn
* Random Forest
* XGBoost
* Logistic Regression
* Decision Tree
* K-Nearest Neighbors

### Explainable AI

* SHAP

### Visualization

* Plotly
* Matplotlib
* Seaborn

### Deployment

* Netlify

---

## ⚙️ Feature Engineering

### Temperature Difference

Process Temperature − Air Temperature

### Power Estimate

Rotational Speed × Torque

### Tool Wear Rate

Normalized tool wear indicator used for maintenance prediction.

---

## 🔄 Project Workflow

```text
Data Collection
      ↓
Data Cleaning
      ↓
EDA
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Hyperparameter Tuning
      ↓
SHAP Explainability
      ↓
Dashboard Development
      ↓
Deployment
```

## 🤖 Machine Learning Models

### Models Evaluated

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors
* XGBoost

### Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 85.95%   |
| Decision Tree       | 97.30%   |
| Random Forest       | 98.60%   |
| XGBoost             | 98.35%   |

### 🏆 Best Model

**Random Forest Classifier**

* Accuracy: 98.60%
* Precision: 90%
* F1 Score: 76.27%
* Cross Validation F1 Score: 78.01%

---

## 📈 Dashboard Features

### Executive Dashboard

* Machine health overview
* KPI monitoring
* Failure statistics

### Sensor Analytics

* Temperature monitoring
* Torque analysis
* RPM trends

### Feature Engineering Insights

* Correlation analysis
* Engineered feature evaluation

### Explainable AI

* SHAP Summary Plot
* Feature Importance
* Local Prediction Explanations

### Maintenance Recommendations

* Failure risk assessment
* Preventive maintenance actions
* Operational insights

---

## 🔍 Explainable AI (SHAP)

SHAP analysis helps:

* Understand model predictions
* Identify key failure drivers
* Increase model transparency
* Support maintenance decision-making

---

## 📊 Key Insights

* Heat Dissipation Failure is the most common failure type.
* High torque significantly increases failure probability.
* Tool wear strongly influences machine breakdown.
* Feature engineering improves predictive performance.
* Random Forest achieved the highest accuracy.

---

## 📂 Repository Structure

```text
predictive-maintenance/
│
├── data/
├── notebooks/
├── models/
├── dashboard/
├── reports/
├── images/
├── src/
├── requirements.txt
└── README.md
```

## 🚀 Future Improvements

* Real-time IoT integration
* Edge AI deployment
* Predictive maintenance alerts
* Cloud monitoring platform
* Digital Twin integration

---

## 👨‍💻 Author

**Tamilarasan P**

B.Tech – Computer Science & Engineering
SRM Institute of Science and Technology

GitHub: https://github.com/tamil1208

LinkedIn: https://www.linkedin.com/in/tamil-arasan-a2466b274

---

⭐ If you found this project useful, consider giving it a star!


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

