# 🎮 Predicting the Success of Steam PC Games

## 📌 Project Overview

This project uses predictive analytics to estimate the potential success of new PC games on the Steam platform, leveraging clustering, classification, and regression models. Built using the CRISP-DM framework, this model aims to support developers and marketers in forecasting sales and planning effective game launches.

---

## 🎯 Objectives

1. Segment audiences using clustering (K-Means, DBSCAN, OPTICS) to inform marketing strategies.
2. Predict game ratings using classification models (Naive Bayes, SVM, KNN).
3. Estimate revenue with regression models (Ridge, Lasso, Polynomial, Linear).
I
---

## 📂 Data Source

- Main source: [Kaggle Steam Dataset](https://www.kaggle.com/datasets/mohamedtarek01234/steam-games-reviews-and-rankings)
- Supplemented by: [SteamDB](https://steamdb.info/) and [games-stats.com](https://games-stats.com/)

Features:
- Game age, price, followers, user reviews, revenue, and ratings

---

## 🧪 Exploratory Data Analysis (EDA)

- Distribution of price, reviews, and followers
- Correlation between revenue and user engagement
- Outlier detection using boxplots
- Cosine similarity heatmaps to identify game clusters

---

## 🛠️ Data Preprocessing

- Missing value imputation
- Normalization of skewed data
- Encoding categorical variables
- Feature engineering & binning

---

## 🔍 Modelling

### 🔹 Clustering
- K-Means: 4 clusters (best silhouette score)
- DBSCAN: 2 clusters + noise
- OPTICS: 11 fine-grained clusters, best for outlier detection

### 🔹 Classification
| Model        | Accuracy | F1 Score |
|--------------|----------|----------|
| Naive Bayes  | 88.46%   | 0.89     |
| SVM          | 84.61%   | 0.85     |
| KNN          | 73.07%   | 0.71     |

### 🔹 Regression
| Model              | MSE     | R² Score |
|-------------------|---------|----------|
| Ridge Regression   | 9173.46 | 0.4078   |
| Lasso Regression   | 9303.03 | 0.3995   |
| Linear Regression  | 9346.00 | 0.3967   |
| Polynomial         | 9575.86 | 0.3819   |

---

## 🧠 Tools Used

- Python: pandas, sci-kit-learn, matplotlib, seaborn
- SPSS: correlation, regression
- Jupyter Notebook
- CRISP-DM framework for structure

---

## ✅ Key Takeaways

- User engagement metrics (reviews, followers) are the strongest predictors of success.
- Ridge Regression performs best for predicting revenue.
- Naive Bayes and SVM give high accuracy for game rating prediction.
- Effective data preprocessing is essential for accurate modelling.

---

## 📁 Repository Structure

```
steam-game-success-prediction/
├── data/
├── notebooks/
├── images/
├── results/
├── Preprocessing SPSS Files
├── README.md
└── requirements.txt
```

---

## 👨‍💻 Author

Ransom Robins Fernando  
MSc in Business Analytics, University of Birmingham  
