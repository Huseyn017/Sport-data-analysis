⚽ Striker Performance Analysis in Python
This project focuses on the performance evaluation and statistical analysis of football strikers using Python. 
It combines exploratory data analysis, hypothesis testing, regression modeling, and classification to draw insights from player statistics.

🔍 Key Questions & Insights:
- Maximum goals scored by a striker: 34
-Right-footed striker proportion: 53.4%
-Nationality with highest average goals: Brazil and Spain
-Average conversion rate for left-footed players: 0.198
-Number of left-footed players from France: 42

📊 Statistical Analysis:
Normality Test (Shapiro-Wilk) on Consistency Score:
p-value: 0.451 → ✅ Normally distributed (p > 0.05)

Levene's Test for Homogeneity of Variance (ANOVA):
p-value: 0.808 → ✅ Heteroscedasticity accepted (p > 0.05)

Correlation between Hold-up Play & Consistency Score:

✅ Statistically significant
Linear Regression Beta Coefficient (Hold-up Play → Consistency):
β = 0.0015 → Each unit increase in Hold-up Play leads to a 0.0015 increase in Consistency Score

🏅 Striker Evaluation:
Average Total Contribution Score (Top Strikers): 123.39

🤖 Machine Learning Model (Logistic Regression):
Accuracy: 97%
- Correctly predicted regular strikers: 42
- Incorrectly predicted best strikers: 3

🛠 Technologies & Tools Used:
- Python (Pandas, NumPy, SciPy, scikit-learn, matplotlib, seaborn)
- Statistical testing: Shapiro-Wilk, Levene's, Pearson correlation
- Logistic Regression for classification
