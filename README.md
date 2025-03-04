# SC1015-Project
This is a Mini-project for SC1015 (Introduction to Data Science & AI) utilizing a HDB resale dataset from Kaggle. Throughout this project, we will be using Jupyter notebook under Anaconda environment. We aim to conduct a comprehensive analysis to identify the key factors influencing resale prices of HDB flats and our analysis will seek to answer the following questions in problem statements.

![sample map image](Maps/sample.png "Resale locations in 200X")

## Problem Statements
1) Which variables has the greatest influence in HDB resale price?
2) Which model would be ideal for HDB resale price prediction?
3) How are HDB resales distributed across Singapore?

## Libraries
1) Pandas
2) Seaborn
3) Matplotlib
4) Sklearn
5) Folium

## Visualisation
1) Bar plot
2) Box plot
3) Violin plot
4) Scatter plot
5) Time series plot
6) Correlation heatmap
7) Interactive map of Singapore (in notebook + as html)

## Machine Learning Models
1) Linear regression
2) Ridge regression
3) Bayesian ridge regression
4) Gradient boosting regressor
5) Random forest regressor

## Conclusion
1) Floor area has the greatest influence in resale price of HDB flats.
2) Ridge and Bayesian ridge regression model did not improve the linear regression model.
3) Random Forest regressor model performed well in predicting the resale price.
5) The interactive map shows that most resale occurs on the outskirts of Singapore, and resales with the highest prices occur around the central region of Singapore.

## Contributions
[Singh Janhavee](https://github.com/JanhaveeSingh) - Data extraction, Data cleaning, Data visualisation, Gradient boosting regression 

[Vannes Wijaya](https://github.com/sentheta) - Data cleaning, Data visualisation, Random forest regression, Singapore map

[Thwun Thiri Thu](https://github.com/thiriii) - Data visualisation, Linear regression, Ridge regression, Bayesian ridge regression

## References

https://www.kaggle.com/datasets/teyang/singapore-hdb-flat-resale-prices-19902020

https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/

https://www.analyticsvidhya.com/blog/2022/04/bayesian-approach-to-regression-analysis-with-python/

https://scikit-learn.org/stable/auto_examples/ensemble/plot_gradient_boosting_regression.html

https://medium.com/@nandiniverma78988/gradient-boosting-regression-implementation-in-python-for-predictive-modeling-437e4ece8c9e

https://towardsdatascience.com/random-forest-regression-5f605132d19d

https://blog.prototypr.io/interactive-maps-with-python-part-1-aa1563dbe5a9
