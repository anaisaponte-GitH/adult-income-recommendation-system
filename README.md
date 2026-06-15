# Adult Income Recommendation System

## Overview

This project uses demographic and employment data from the Adult Census Income dataset to predict whether an individual is likely to earn more than $50,000 per year.

Beyond classification, the project incorporates a recommendation approach based on similarity analysis to identify profiles associated with higher income levels and provide interpretable insights that could help improve earning potential.

The objective is not only to predict an outcome but also to demonstrate how Machine Learning can support decision-making through actionable recommendations.

---

## Business Problem

Organizations often need to understand which factors are associated with higher income levels in order to:

- Identify relevant socioeconomic patterns.
- Support workforce and education analysis.
- Generate personalized recommendations.
- Improve decision-making through data-driven insights.

This project explores how predictive analytics and recommendation techniques can be combined to move from prediction to action.

---

## Dataset

The project uses the Adult Census Income dataset, which contains demographic, educational and employment-related information.

Examples of variables include:

- Age
- Education level
- Occupation
- Hours worked per week
- Marital status
- Relationship
- Capital gain
- Capital loss

### Target Variable

- Income > $50K
- Income ≤ $50K

---

## Methodology

### 1. Data Preparation

- Data cleaning
- Missing value handling
- Feature encoding
- Exploratory analysis

### 2. Classification Model

A Machine Learning model was trained to predict whether an individual belongs to the high-income group.

Evaluation metrics included:

- Accuracy
- Precision
- Recall
- F1 Score

### 3. Recommendation Engine

A content-based recommendation approach was implemented using profile similarity.

The system:

1. Identifies individuals with similar characteristics.
2. Compares them against higher-income profiles.
3. Generates interpretable recommendations based on observed patterns.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## Results

The project successfully demonstrates how predictive models can be combined with recommendation techniques to provide more business value than classification alone.

Instead of simply predicting income level, the solution offers insights into the characteristics commonly associated with higher-income profiles.

---

## Project Structure

```text
adult-income-recommendation-system/
│
├── recommendation_system.ipynb
├── README.md
└── assets/
```

---

## Key Learnings

- End-to-end Machine Learning workflow.
- Feature engineering and model evaluation.
- Similarity-based recommendation systems.
- Translating analytical outputs into business insights.
- Building solutions that move from prediction to decision support.

---

## Author

**Anaís Aponte**

Senior Product Owner | Agile Delivery | Data & AI

GitHub: https://github.com/anaisaponte-GitH
