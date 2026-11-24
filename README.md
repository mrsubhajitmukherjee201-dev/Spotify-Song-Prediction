# 🎵 Spotify Song Popularity & Recommendation Predictor

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

An end-to-end machine learning pipeline that analyzes Spotify audio features to predict song popularity and generate personalized track recommendations.

---

## 📌 Overview
What makes a song go viral on Spotify? This project explores the relationship between a track's musical attributes (such as danceability, energy, tempo, and valence) and its commercial success. Using supervised learning models, the pipeline classifies whether a song will become a chart-topping hit or predicts its exact popularity score.

---

## ✨ Key Features
* **Exploratory Data Analysis (EDA):** Visualizes distributions, feature correlations, and genre-specific audio trends.
* **Feature Engineering:** Normalizes audio metrics, encodes categorical metadata, and extracts release-date seasonality.
* **Model Benchmarking:** Compares Logistic Regression, Random Forest, and Decision Tree Classifier on classification/regression metrics.

---

## 📂 Project Structure
```text
├── Spotify song preduction/
│   ├── data/
│   │   └── songs_normalize.csv              # Cleaned and feature-engineered dataset
│   │
│   ├── src/
│   │   └── notebooks/
│   │       └── spotify_src.ipynb            # Notebook file for model training, tuning, and evaluation
│   │
│   └── procedure.pdf
│
├── LICENSE
└── README.md
