# ProActify: Churn Prediction with AIML for Banking Systems

## Overview

**ProActify** is an advanced Churn Prediction platform designed for banking systems, leveraging Artificial Intelligence and Machine Learning (AIML) algorithms to help banks proactively identify customers at risk of leaving. The project uses state-of-the-art modeling techniques, interpretable analytics, and robust feature engineering to provide actionable insights, enabling strategic interventions for customer retention.

Banking organizations face significant challenges caused by customer churn. ProActify empowers financial institutions to predict, analyze, and visualize churn risk, supporting data-driven retention strategies and improved service delivery.

## Features

- **Accurate Churn Prediction** using supervised ML models (Logistic Regression, Random Forest, XGBoost, etc.)
- **Comprehensive Data Preprocessing** including missing value handling, encoding, and scaling
- **Feature Engineering** tailored for banking customer data
- **Interpretable Model Outputs** for actionable business decisions
- **Visualization Dashboards** for stakeholder insights
- **Customizable Model Selection and Training Pipeline**
- **Easy Deployment** with modular design (API/CLI/Notebook support)

## Demo

## Getting Started

### Prerequisites

- Python 3.7+
- pip (Python package manager)
- (Recommended) virtualenv or conda environment

### Installation

Clone the repository:
```bash
git clone https://github.com/parth-lightning/ProActify---Churn-Prediction-with-AIML-for-Banking-Systems.git
cd ProActify---Churn-Prediction-with-AIML-for-Banking-Systems
```

Install dependencies:
```bash
pip install -r requirements.txt
```

### Dataset

Prepare the banking customer dataset with relevant features (e.g., account history, transaction data, demographics). Place your dataset in the `data/` directory as `customers.csv`.

### Usage

Jupyter Notebook version:
```bash
jupyter notebook notebooks/Churn_Prediction.ipynb
```

## Model Pipeline

1. **Data Ingestion:** Load and preprocess banking data.
2. **Feature Engineering:** Transform and select features relevant for churn.
3. **Model Training:** Select and train AIML models.
4. **Evaluation:** Assess model performance using metrics (AUC, F1-score, etc.).
5. **Interpretation:** Feature importance, explainability reports.
6. **Prediction:** Generate churn risk scores.
7. **Visualization:** Interactive dashboards/reports.

## Examples

#### Training and Testing

```python
from src.model import train_model, predict_churn

train_model("data/customers.csv")
risk_scores = predict_churn("data/new_customers.csv")
```

#### Model Results Example:

| CustomerID | Churn Probability | Risk Level |
|------------|-------------------|------------|
| 1001       | 0.80              | High       |
| 1002       | 0.23              | Low        |

## Contact
email: parthdheerajpatil@gmail.com
