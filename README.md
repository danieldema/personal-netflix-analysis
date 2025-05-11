This project is an analysis of viewing data pulled from my own personal Netflix account - data is available in ViewingActivity.csv.

# Initial Analysis

In netflix_analysis.ipynb I used pandas to examine the viewing count, viewing time (overall and average), and titles viewed by different profiles on my account. I used Matplotlib to build a visual comparison of viewing count between different profiles and to visualize the devices most commonly used and titles with the highest viewing counts.

# Logistic Regression

In netflix_logreg.ipynb I used scikit-learn to construct a logistic regression model with an AUC score of 0.81 to predict profile based on viewing time and device type. I used Matplotlib and seaborn to visualize the confusion
matrix through a heatmap and to plot an ROC curve.
