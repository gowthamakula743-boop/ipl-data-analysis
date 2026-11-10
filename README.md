# IPL Data Analysis and Match Outcome Prediction

Analysis of IPL matches (2008–2024) and a machine learning model to predict match winners.

**Dataset:** Kaggle – IPL Complete Dataset (2008–2024): matches.csv, deliveries.csv

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab

## Steps followed
1. **Data collection** – loaded match and ball-by-ball data from Kaggle
2. **Data preprocessing** – handled missing values, fixed renamed teams, removed no-result matches, encoded categorical columns
3. **Exploratory data analysis** – team wins, toss impact, batting first vs chasing, venues, season trends, top players
4. **Split data** – 80% training, 20% testing
5. **Model selection** – Logistic Regression and Random Forest
6. **Model training** – trained both models on team, toss and venue features
7. **Evaluation** – accuracy score and confusion matrix
8. **Prediction** – predicted the winner and win probability for a new match

## Key insights
- Toss winners won only 50.8% of matches, so the toss has almost no impact
- Chasing teams won 54.1% of matches
- V Kohli is the top run-scorer with 8,014 runs
- Both models reached 51.8% accuracy: toss and venue alone can't predict IPL results

## Next steps
Add team recent form and head-to-head record as features to improve accuracy.
