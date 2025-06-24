#  Movie Success Prediction and Sentiment Analysis

This project aims to predict the commercial success of movies using the IMDb Top 1000 dataset. It combines Exploratory Data Analysis, Sentiment Analysis using NLP (VADER), and Regression Modeling to understand what factors influence a movie's gross revenue.

---

##  Dataset
- **Source**: IMDb Top 1000 Movies Dataset (Kaggle)
- **Columns Used**: Title, Genre, Runtime, Gross, IMDB_Rating, Meta_score, No_of_Votes, Overview

---

##  Project Objectives
- Perform sentiment analysis on movie overviews using VADER (NLP)
- Explore genre-wise sentiment trends
- Build a regression model to predict box office success
- Visualize and interpret the most influential features

---

##  Tools & Technologies
- Python (Pandas, Seaborn, Matplotlib, Scikit-learn, NLTK)
- Jupyter Notebook

---

##  Key Steps
1. **Data Cleaning** – Handled missing values and cleaned numeric columns.
2. **Feature Engineering** – Created `Gross_Million`, extracted `Primary_Genre`, added sentiment scores.
3. **Sentiment Analysis** – Used VADER to score sentiment from movie overviews.
4. **Modeling** – Built a Linear Regression model to predict `Gross_Million`.
5. **Evaluation** – Evaluated model performance using MAE, RMSE, and R² score.
6. **Visualization** – Plotted sentiment distribution and feature importance.

---

##  Results
- The model was able to predict box office gross with reasonable accuracy.
- Sentiment and genre were moderately correlated with movie success.
- Features like `Votes`, `Runtime`, and `Meta_score` had strong predictive power.

---

##  Files in This Repository
- `movie_success_analysis_with_markdown.ipynb` – Final project notebook with comments and structure.
- `report.pdf` – 2-page project summary report.
- `imdb_top_1000.csv` – Dataset used (optional if permitted).
- `README.md` – This file.

---

##  Author
- **Your Name**: Arun kumar M
- **Project Timeline**: June 2025

---
