# Yes-Bank-Stock-Closing-Price-Prediction-Capstone-ProjectML-Regression

![](https://upload.wikimedia.org/wikipedia/commons/d/d1/Yes_Bank_Logo-01.png)



This project aims to address the challenge of predicting the closing price of Yes Bank's stock, which is a crucial task for stakeholders, investors, and market participants. Yes Bank, as a prominent private sector bank in India, has encountered significant hurdles in recent years, including a substantial number of bad loans and involvement in fraud cases. These challenges have led to regulatory intervention by the Reserve Bank of India, making the prediction of Yes Bank's stock prices complex and uncertain.

## Problem Statement
The main objective of this project is to develop a robust and accurate predictive model that can effectively forecast the closing price of Yes Bank's stock. The challenge lies in understanding and capturing the complex dynamics and trends in the stock prices, considering various factors such as the historical trend of an increasing price followed by a sudden decline after 2018.

## Summary and Conclusion
1. A careful examination of the data reveals a pronounced decline in the stock prices of Yes Bank following the exposure of the Rana Kapoor fraud in 2018.

2. The dataset exhibited exceptional cleanliness, devoid of any missing values or duplicated rows, minimizing the need for extensive data wrangling.

3. Although outliers were present in the features, effective outlier mitigation was achieved through the implementation of a log transformation across all features.

4. The log transformation successfully addressed the positive skewness observed in all features, ensuring adherence to the assumptions of the linear regression models.

5. Strong positive correlations were observed between the independent variables (Open, High, Low) and the dependent variable (Close), implying a high predictive potential of the dependent variable based on the independent variables.

6. The presence of positive correlations among the independent variables suggested the presence of multicollinearity; however, given the limited dataset size, feature removal was deemed unnecessary.

7. Among the various implemented regression models, the Ridge Regression model, combined with GridSearchCV for hyperparameter optimization, emerged as the preferred choice. It achieved a commendable performance, boasting an RMSE of 8.3824 and an R-2 score of 0.9938.

8. Notably, the 'High' and 'Low' features demonstrated positive weights, indicating a favourable impact on the predictions. Conversely, the 'Open' feature displayed a negative weight, signifying a detrimental influence on the predictions.

9. Satisfactorily meeting the assumptions of homoscedasticity, absence of autocorrelation, and a mean of zero, the residuals bolstered the reliability of the regression model.

10. The robustness of the conclusions was supported by a thorough exploration of the data, leaving little room for ambiguity.

11. The observed decline in Yes Bank's stock prices following the Rana Kapoor fraud exposure underscored the substantial impact of such events on the financial market.

12. The meticulous data-cleaning process instilled confidence in the dataset's integrity, fostering accurate and reliable analyses.

13. Employing an appropriate transformation technique mitigated the influence of outliers, ensuring a more accurate representation of the data.

14. Addressing positive skewness through a log transformation enhanced the conformity of the data to the assumptions of linear regression models.

15. The strong positive correlations between the independent and dependent variables bolstered the predictive power of the regression models.

16. Careful consideration of multicollinearity, despite its presence, deemed feature removal unnecessary, given the limited dataset size.

17. The selection of Ridge Regression with GridSearchCV as the final prediction model was substantiated by its exceptional performance, as demonstrated by the low RMSE and high R-2 score.
