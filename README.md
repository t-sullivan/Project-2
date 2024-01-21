# Project-2

## Predicting Inflation Dynamics in the US Economy: A Machine Learning Model Leveraging Commodities and Political Shifts for Forecasting Future Inflation Trends
### Project Overview:
The project aims to develop an algorithmic model for forecasting inflation trends in the US economy by leveraging historical data of commodities (gold, crude oil, soybeans, wheat, corn) and political shifts from 1960 - 2024, a 64-year time frame.
### Correlation to Fintech:
A predictive model that accurately forecasts CPI trends can assist in risk management strategies within FinTech applications, helping companies hedge against inflation risk and optimize their portfolios accordingly.
### Methodology
In our approach, the integration of TPOT (Tree-based Pipeline Optimization Tool), an advanced AutoML library, played a pivotal role in the streamlined development and optimization of machine learning pipelines. Specifically designed for traditional predictive modeling challenges, TPOT efficiently processes datasets by leveraging multiple machine learning models, generating Cross-Validation (CV) scores to evaluate their performance. In our scenario, after conducting 10 tests, the Extra Tree Regressor, an ensemble learning algorithm, emerged as the top-performing model based on the highest CV score. This showcases the effectiveness of TPOT in automating the selection and optimization of machine learning models, with the Extra Tree Regressor standing out as the optimal choice in our specific use case.

