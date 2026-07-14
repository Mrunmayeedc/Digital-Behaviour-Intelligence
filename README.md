# Digital Behaviour Intelligence Platform

## AI-Driven Framework for Assessing Digital Exhaustion, Attention Span, Notification Dependency, Aggression Risk, and Digital Wellbeing

---

## Project Overview

Digital Behaviour Intelligence Platform is an end-to-end Data Science and Machine Learning project that analyzes modern digital behaviour and its impact on human wellbeing.

The project studies how excessive screen time, social media usage, gaming habits, notification overload, sleep patterns, and digital addiction influence attention span, mental wellbeing, and behavioural risks.

The platform combines statistical analysis, feature engineering, machine learning, explainable AI, and recommendation systems to generate actionable insights for digital wellbeing.

---

## Problem Statement

The increasing dependence on smartphones and digital technologies has led to concerns regarding:

- Digital Exhaustion
- Reduced Attention Span
- Notification Dependency
- Sleep Disruption
- Technology Addiction
- Aggression due to Digital Withdrawal
- Declining Digital Wellbeing

Current systems mainly focus on screen time statistics and fail to provide comprehensive behavioural analysis.

This project proposes an AI-driven behavioural intelligence framework to assess multiple aspects of digital behaviour simultaneously.

---

## Project Objectives

- Analyze digital behaviour patterns using real-world data
- Develop a Digital Exhaustion Index (DEI)
- Predict Attention Span using Machine Learning
- Create a Notification Dependency Index (NDI)
- Estimate Aggression Risk
- Explain model predictions using SHAP Explainable AI
- Perform Statistical Hypothesis Testing
- Generate Personalized Digital Wellbeing Recommendations

---

## Project Workflow

Raw Dataset

↓

Data Cleaning & Preprocessing

↓

Exploratory Data Analysis (EDA)

↓

Feature Engineering

↓

Digital Exhaustion Index (DEI)

↓

Attention Span Prediction

↓

Notification Dependency Index (NDI)

↓

Aggression Risk Assessment

↓

Explainable AI (SHAP)

↓

Statistical Research Analysis

↓

Digital Wellbeing Recommendation Engine

---

## Project Architecture

```
Raw Dataset
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
      ├──────────────► Digital Exhaustion Index (DEI)
      │
      ├──────────────► Attention Span Prediction
      │
      ├──────────────► Notification Dependency Index (NDI)
      │
      └──────────────► Aggression Risk Assessment
                              │
                              ▼
                     Explainable AI (SHAP)
                              │
                              ▼
                  Statistical Research Analysis
                              │
                              ▼
            Digital Wellbeing Recommendation Engine
```

---

# Repository Structure

```
Digital-Behaviour-Intelligence/

│── README.md

│
├── notebooks/
│   ├── 01_dataset_understanding.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   ├── 04_digital_exhaustion_index.ipynb
│   ├── 05_attention_span_predictor.ipynb
│   ├── 06_notification_dependency_analysis.ipynb
│   ├── 07_explainable_ai.ipynb
│   ├── 08_statistical_research_analysis.ipynb
│   ├── 09_recommendation_engine.ipynb
│   └── 10_powerbi_dashboard_preparation.ipynb

│
├── data/
│   ├── cleaned_data.csv
│   ├── DEI_dataset.csv
│   ├── attention_dataset.csv
│   ├── dependency_dataset.csv
│   ├── research_dataset.csv
│   ├── dashboard_dataset.csv
│   └── final_dashboard_dataset.csv

│
├── images/

│
├── report/

│
└── requirements.txt
```

---

# Dataset

The project uses publicly available digital behaviour datasets and performs extensive preprocessing and feature engineering.

### Features

- Age
- Gender
- Daily Screen Time
- Social Media Usage
- Gaming Hours
- Work / Study Hours
- Sleep Hours
- Notifications Per Day
- App Opens Per Day
- Stress Level
- Academic / Work Impact
- Addiction Level

---

# Feature Engineering

The project creates several new behavioural features including:

### Digital Exhaustion Index (DEI)

Measures digital fatigue based on:

- Screen Time
- Sleep Pattern
- Stress
- Productivity

---

### Attention Score

Predicted using:

- Random Forest Machine Learning Model

---

### Notification Dependency Index (NDI)

Computed using:

- Notifications Per Day
- App Opens
- Digital Exhaustion
- Attention Score

---

### Aggression Risk

Estimated using:

- NDI
- DEI
- Attention Inversion

---

### Wellbeing Score

Calculated using:

- Sleep
- Attention
- DEI
- NDI
- Aggression Risk

---

# Machine Learning

Model Used

- Random Forest Classifier

Tasks

- Attention Prediction
- Behaviour Classification

Model Evaluation

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# Explainable AI

Explainability was implemented using:

- SHAP (SHapley Additive Explanations)

Visualizations include:

- Feature Importance
- SHAP Summary Plot
- Force Plot
- Dependence Plot

---

# Statistical Analysis

The project validates findings using:

- Pearson Correlation
- Spearman Correlation
- Independent T-Test
- ANOVA
- Chi-Square Test

---

# Recommendation Engine

The platform generates personalized recommendations based on behavioural indicators.

Examples include:

- Reduce daily screen time
- Improve sleep schedule
- Disable unnecessary notifications
- Practice focused work sessions
- Schedule regular digital detox periods

---

# Technologies Used

Programming Language

- Python

Development Environment

- Google Colab

Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- SHAP

Version Control

- Git
- GitHub

---

# Project Outcomes

The project successfully demonstrates:

- Behavioural Feature Engineering
- Machine Learning Prediction
- Explainable AI
- Statistical Validation
- Recommendation Generation
- End-to-End Data Science Workflow

---

# Future Improvements

Potential future enhancements include:

- Deep Learning Models
- Mobile Application Integration
- Real-Time Behaviour Monitoring
- IoT and Wearable Device Support
- Time-Series Behaviour Prediction
- Interactive Power BI Dashboard
- Web Application Deployment

---

# Installation

Clone the repository:

```bash
git clone https://github.com/<Mrunmayeedc>/Digital-Behaviour-Intelligence.git
```

Navigate to the project:

```bash
cd Digital-Behaviour-Intelligence
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebooks using:

- Jupyter Notebook
- Google Colab

---

# Results

Key outputs generated by the project include:

- Digital Exhaustion Index
- Attention Score
- Notification Dependency Index
- Aggression Risk Score
- Wellbeing Score
- SHAP Explainability
- Statistical Research Findings
- Personalized Recommendations

---

# Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Machine Learning
- Explainable AI
- Statistical Analysis
- Behavioural Analytics
- Data Visualization
- Research Methodology
- Git & GitHub

---

# Author

**Mrunmayee Chavan**

Computer Engineering Graduate

Interests:

- Data Science
- Machine Learning
- Artificial Intelligence
- Behavioural Analytics
- Explainable AI

---

## License

This project is intended for educational, research, and portfolio purposes.
