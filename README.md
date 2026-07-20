# 🔧 Contextual Predictive Maintenance using IoT Edge AI

> **Infotact Solutions – Technical Internship Program (Data Science & Machine Learning)**

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-013243?style=for-the-badge&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-F7931E?style=for-the-badge&logo=scikitlearn)
![LightGBM](https://img.shields.io/badge/LightGBM-Gradient%20Boosting-green?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-181717?style=for-the-badge&logo=github)

---

## 📖 Project Overview

Predictive Maintenance is an Industrial AI application that predicts machine failures before they occur using sensor data and machine learning. This project integrates IoT telemetry, contextual information, feature engineering, and LightGBM to build an intelligent failure prediction system.

The objective is to reduce unexpected equipment failures, minimize maintenance costs, and improve operational efficiency by enabling proactive maintenance strategies.

---

## 🎯 Objectives

- Build an end-to-end predictive maintenance pipeline.
- Perform exploratory data analysis on IoT sensor data.
- Engineer meaningful time-series and statistical features.
- Handle imbalanced failure datasets using SMOTE.
- Train a LightGBM model for failure prediction.
- Evaluate model robustness under noisy sensor conditions.
- Maintain proper GitHub commit history throughout the internship.

---

# 🏭 Problem Statement

Manufacturing industries rely heavily on machines operating continuously. Unexpected failures can result in:

- Production downtime
- High repair costs
- Reduced productivity
- Safety risks

Using historical sensor readings, the goal is to predict machine failures before they happen, allowing industries to perform preventive maintenance at the right time.

---

# 📂 Repository Structure

```
INFOTACT-TECHNICAL-INTERNSHIP-PROGRAM
│
├── Dataset/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── Week1_EDA.ipynb
│   ├── Week2_Contextual_Features.ipynb
│   ├── Week3_Model_Training.ipynb
│   └── Week4_Model_Evaluation.ipynb
│
├── reports/
│
├── results/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# ⚙️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn, LightGBM |
| Imbalanced Learning | SMOTE |
| Model Validation | Stratified Cross Validation |
| Notebook | Jupyter Notebook |
| Version Control | Git & GitHub |

---

# 📊 Dataset

The project uses industrial IoT sensor telemetry containing machine operating parameters such as:

- Temperature
- Pressure
- Humidity
- Vibration
- Voltage
- Current
- Rotational Speed
- Machine Status
- Failure Label

---

# 🔍 Project Workflow

```
Industrial IoT Sensor Data
            │
            ▼
      Data Collection
            │
            ▼
      Data Cleaning
            │
            ▼
 Exploratory Data Analysis
            │
            ▼
 Feature Engineering
            │
            ▼
 Contextual Data Integration
            │
            ▼
  Data Preprocessing
            │
            ▼
 LightGBM Model Training
            │
            ▼
 Model Evaluation
            │
            ▼
 Failure Prediction
```

---

# 📅 Internship Progress

## ✅ Week 1 — Data Collection & Exploratory Data Analysis

### Completed Tasks

- Repository initialization
- Git version control setup
- Dataset loading
- Missing value analysis
- Statistical summary
- Distribution analysis
- Correlation heatmap
- Rolling Mean
- Rolling Standard Deviation
- Rolling Maximum
- Rolling Minimum
- Initial feature engineering

### Deliverables

- EDA Notebook
- Correlation Report
- Feature Engineering Report

## Week 1 — Day 3 Progress

### Completed

- Built baseline Random Forest model
- Performed train-test split
- Generated classification report
- Created confusion matrix
- Analyzed feature importance

### New Features

- Temperature difference
- Power proxy feature

### Outcome

Successfully trained first predictive maintenance model and evaluated performance.

## Week 1 — Day 4 Progress

### Completed

- Studied class imbalance
- Applied SMOTE oversampling
- Trained improved Random Forest model
- Compared model performance
- Evaluated confusion matrix

### Outcome

Improved handling of rare machine failure cases through data balancing techniques.

## Week 1 — Day 5 Progress

### Completed

- Simulated external contextual data
- Ambient temperature generation
- Factory load simulation
- Humidity simulation
- Contextual feature engineering

### Ablation Study

Compared:

1. Internal telemetry only
2. Telemetry + contextual signals

### Outcome

Verified impact of contextual variables on predictive maintenance performance.

---

## ✅ Week 2 — Contextual Feature Engineering

### Completed Tasks

- Time-based feature extraction
- Statistical feature generation
- Contextual variable integration
- Data preprocessing
- Feature scaling
- Feature selection

### Deliverables

- Cleaned Dataset
- Engineered Dataset
- Feature Documentation

---

## ✅ Week 3 — Machine Learning Development

### Completed Tasks

- Train-Test Split
- SMOTE Oversampling
- LightGBM Classifier
- Hyperparameter Optimization
- Stratified Cross Validation
- Feature Importance Analysis

### Deliverables

- Trained Model
- Model Comparison
- Performance Report

---

## ✅ Week 4 — Evaluation & Robustness Testing

### Completed Tasks

- Precision Evaluation
- Recall Evaluation
- F1 Score
- ROC-AUC Analysis
- Confusion Matrix
- Threshold Optimization
- Noise Sensitivity Testing
- Final Report Preparation

### Deliverables

- Final Model
- Evaluation Report
- Internship Submission

---

# 📈 Evaluation Metrics

The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

---

# 🚀 Expected Outcome

The developed solution enables industries to:

- Predict failures before occurrence
- Reduce maintenance costs
- Minimize downtime
- Improve production efficiency
- Increase equipment reliability

---

# 📌 Future Improvements

- Streamlit Dashboard
- FastAPI Deployment
- Docker Containerization
- Explainable AI using SHAP
- Real-Time IoT Integration
- Cloud Deployment (AWS/Azure)

---

# 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/tamil1208/INFOTACT-TECHNICAL-INTERNSHIP-PROGRAM.git
```

Move into the project directory:

```bash
cd INFOTACT-TECHNICAL-INTERNSHIP-PROGRAM
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📌 Requirements

```
Python >= 3.11
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
LightGBM
imbalanced-learn
Jupyter Notebook
```

---

# 👥 Team Members

| GitHub | Name |
|---------|------|
| [@MeghaKA](https://github.com/MeghaKA) | Megha K A |
| [@tamil1208](https://github.com/tamil1208) | Tamilarasan P |
| [@Zenishaa](https://github.com/Zenishaa) | Devani Zenisha |

---

# 👨‍💻 Project Mentor

**Infotact Solutions**

Technical Internship Program

Data Science & Machine Learning

---

# 📄 License

This project was developed for educational and internship purposes under the **Infotact Technical Internship Program**.

---

# 🙏 Acknowledgements

Special thanks to:

- Infotact Solutions
- Internship Mentors
- Project Review Team
- Open Source Python Community

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork the repository

📢 Share it with others

---

# 📬 Contact

**Tamilarasan P**

🎓 B.Tech – Computer Science and Engineering

🏫 SRM Institute of Science and Technology

🔗 GitHub: https://github.com/tamil1208

💼 LinkedIn: https://www.linkedin.com/in/tamilarasan-a2466b274/

---

> **"Predicting failures today for a more reliable tomorrow."**
