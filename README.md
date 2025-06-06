# RaceWise
**RaceWise** is a machine learning project originally designed to predict horse racing outcomes, later pivoted to NBA game predictions due to more accessible and structured data. It explores different models and data preprocessing pipelines to learn the fundamentals of sports prediction and data science.

---

## Goal

The primary goal of RaceWise was not to beat the bookmakers, but to:
- Practice end-to-end model development.
- Learn how data quality affects predictive power.
- Compare the effectiveness of different algorithms.
- Understand real-world performance limits in sports prediction.

---

## Features

- Web scraping of historical NBA game data.
- Cleaning and transformation of matchup and team statistics.
- Implementation of multiple classification models:
  - Logistic regression
  - Random forests
  - Gradient Boosting
- Evaluation based on accuracy
- Performance analysis vs bookmaker win probabilities.

---

## Model Features
- Best-performing model: **XGBoost Classifier**
- Accuracy: **~68%**, roughly aligned with the actual win rate of betting favorites in the NBA.
- Insight: Performance plateaued around the level of public betting wisdom, revealing the limits of data-only models for predicting professional sports.

---

## Tech Stack

- **Language**: Python
- **Libraries**: pandas, NumPy, scikit-learn, XGBoost, matplotlib
- **Data Source**: [basketball-reference.com](https://www.basketball-reference.com/)
- **Notebook Tools**: Jupyter

---

## Files

- `nba_scraping.ipynb`: Code to gather and clean NBA matchup data
- `nba_training.ipynb`: ML models, experiments, and evaluations
