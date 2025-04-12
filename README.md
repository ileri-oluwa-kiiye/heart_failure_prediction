# Cardiovascular Disease Prediction

A neural network-based solution for predicting the presence of cardiovascular disease using clinical and demographic data.

## 📌 Overview

This project was developed as part of a private machine learning challenge focused on cardiovascular disease (CVD) prediction. CVDs are among the top global causes of mortality, and early detection plays a vital role in prevention and treatment.

The goal was to build a model that accurately predicts whether an individual is at risk of developing cardiovascular disease based on medical records.

## 📝 Problem Statement

Given a dataset of clinical and demographic information, classify individuals into:

- `0` – No Cardiovascular Disease  
- `1` – Cardiovascular Disease Present

## 🧠 Methodology

- **Model**: Fully connected neural network (ANN)
- **Framework**: PyTorch
- **Loss Function**: Binary Cross Entropy
- **Optimizer**: Adam
- **Evaluation Metric**: F1 Score
- **Data Handling**: Standard preprocessing including normalization and train-validation splitting

## 📈 Results

- **F1 Score**: `0.73` on private leaderboard

This score reflects the balance between **precision** and **recall**, which is essential in medical diagnostics where both false positives and false negatives carry serious consequences.

## 📁 Submission Format

Final submissions included a CSV file in the format below:

```csv
id,cardio
1001,0
1002,1
1003,0
...
