# 🏏 Cricket Match Prediction System

A simple machine learning project that predicts cricket match outcomes using a Naive Bayes classifier.

## 📌 Overview
This project predicts whether **Team 1 wins or loses** a match based on basic match statistics like score, wickets lost, and toss result.

## 🛠️ Tech Stack
- Python
- scikit-learn (GaussianNB)
- pandas, matplotlib, seaborn
- Google Colab

## 📊 Dataset
A small custom dataset of 20 cricket matches with 4 features:
- `team1_score` — runs scored by Team 1
- `team2_score` — runs scored by Team 2
- `team1_wickets_lost` — wickets lost by Team 1
- `toss_won` — whether Team 1 won the toss (1 = yes, 0 = no)

Target: `result` (1 = Team 1 Wins, 0 = Team 1 Loses)

## 🤖 Algorithm
**Naive Bayes (GaussianNB)** — chosen for its simplicity and effectiveness on small datasets.

## ▶️ How to Run
Click below to open and run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/cricket-match-prediction-ml/blob/main/cricket_prediction_naive_bayes.ipynb)

Or run locally:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook cricket_prediction_naive_bayes.ipynb
```

## 📈 Result
The model is evaluated using accuracy score, classification report, and a confusion matrix.

## 👤 Author
Noor# cricket-match-prediction
