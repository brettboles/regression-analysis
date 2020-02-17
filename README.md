# regression-analysis

Multivariate Regression on Excess US Stock Returns

*For Illustrative Purposes only

Based on Level II of the CFA Curriculum(Volume 1, Quantitative Methods, page 389)
Additional Credit to the following links: https://towardsdatascience.com/simple-and-multiple-linear-regression-with-python-c9ab422ec29c
https://www.statsmodels.org/stable/regression.html

Dependent Variable(y): Excess Nasdaq 100 One-Month Stock Returns = One-Month Nasdaq 100 Stock Returns minus One-Month T-Bill

Independent Variables(x):

Default Spread(monthly), t-1 = Previous Months Yield on AA Bonds minus yield on AAA Bonds

Term Spread(monthly), t-1 = Previous Months Yield on 10 Yr US Treasury minus Yield on 1 YR US Treasury

Presidential Party Dummy Variable(monthly), t-1: 1 if President is Democrat, 0 if Republican
