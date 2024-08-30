# Capstone_Project_ML-Yes_Bank_Stock_Closing_Price_Prediction-

![Yes Bank Logo](https://drive.google.com/uc?export=view&id=1FxCC_KnScnjBt0ssblvVZ1Mlym3fPUpI)

## Summery-
This project focuses on predicting the closing price of Yes Bank's stock, a task complicated by the bank's recent challenges, including bad loans, fraud cases, and regulatory interventions. Utilizing monthly stock price data, the project applies various regression models to forecast prices and assess the impact of significant events. The goal is to provide valuable insights for stakeholders and support informed investment decisions amidst the bank's financial uncertainties.
## Objective:
Develop a robust predictive model to accurately forecast Yes Bank's stock closing prices, addressing challenges such as multicollinearity and the impact of significant events like fraud cases and regulatory interventions.

## Challenges:

**1. Multicollinearity:** Handling high correlations between independent variables to improve model interpretation and accuracy.

**2. Significant Events:** Accurately capturing the effects of events that influence stock prices.

## Performance Goal:
Achieve high accuracy, with the K-Nearest Neighbors (KNN) Regression model's 99% accuracy as a benchmark, to provide valuable insights for stakeholders and support informed investment decisions.

## Overall Goal:
Create a reliable model that enhances understanding of Yes Bank's stock performance and aids in making well-informed investment choices.

## Conclusion:
**1.Stock Price Decline:** A significant drop in Yes Bank's stock prices followed the Rana Kapoor fraud exposure in 2018.
**2.Data Quality:** The dataset was exceptionally clean with no missing values or duplicates, reducing the need for extensive wrangling.
**3.Outlier Management:** Outliers were effectively mitigated using log transformation, which also corrected positive skewness in the data.
**4.Correlations:** Strong positive correlations between independent variables (Open, High, Low) and the dependent variable (Close) suggested high predictive potential.
**5.Multicollinearity:** While multicollinearity was present, no feature removal was necessary due to the dataset's limited size.
**6.Model Selection:** Ridge Regression, optimized with GridSearchCV, was the top performer, achieving an RMSE of 8.3824 and an R² score of 0.9938.
**7.Feature Impact:** 'High' and 'Low' features had positive weights, while 'Open' had a negative weight, influencing predictions.
**8.Model Reliability**: The model met all key assumptions, confirming its reliability for predicting Yes Bank's stock prices.

This analysis underscores the significant impact of financial events on stock prices and the importance of meticulous data preparation and model selection for accurate predictions.






