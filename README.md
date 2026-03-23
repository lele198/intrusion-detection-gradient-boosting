# Intrusion Detection Using Gradient Boosting

This project implements a machine learning model to detect malicious network activity using Gradient Boosting.

## Project Overview
The goal of this project is to classify network traffic as normal or anomalous using supervised learning techniques.

## Dataset
- Intrusion_data.csv
- Contains network activity features

## Methodology
- Data preprocessing and one-hot encoding
- Train/test split (80/20)
- Gradient Boosting model (Scikit-learn)
- Hyperparameter tuning using GridSearchCV

## Evaluation Metrics
- ROC-AUC Score
- Confusion Matrix
- Classification Report
- Cross-validation
- 
## Results
- ROC-AUC Score ≈ 0.999
- High precision, recall, and F1-score
- Strong model performance across all data splits

## Key Concepts
- Machine Learning
- Classification Models
- Feature Engineering
- Model Evaluation
- Cybersecurity Analytics

## Project Structure
- notebooks/ → Jupyter notebook
- docs/ → Project report
- images/ → Model outputs

## Author
Aliyah Benson
## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Open the notebook:
   jupyter notebook

3. Run all cells to train and evaluate the model
