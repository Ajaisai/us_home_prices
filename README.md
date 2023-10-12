# U.S. Home Prices Analysis

## Dataset

The data collected for this assignment are sourced from [fred.stlouisfed.org](https://fred.stlouisfed.org/). These datasets contain quarterly data on key factors that influence US home prices nationally.

- **DATE**: The date of the observation. (2003 - 2023)
- **CSUSHPISA**: S&P/Case-Shiller U.S. National Home Price Index (Index Jan 2000=100, Seasonally Adjusted). This variable serves as a proxy for home prices and represents the home price index for the United States.
- **GDP**: Gross Domestic Product (Billions of Dollars, Seasonally Adjusted Quarterly Rate).
- **MORTGAGE15US**: 30-Year Fixed Rate Mortgage Average in the United States (Percent, Not Seasonally Adjusted). It indicates the average interest rate for a 30-year fixed-rate mortgage.
- **MSPUS**: Median Sales Price of Houses Sold for the United States.
- **POPTHM**: Population, which includes resident population plus armed forces overseas. It indicates the total population of the U.S. over the last 20 years.

The data is recorded quarterly, providing observations at the end of each quarter.

## Data Preprocessing

The data preprocessing steps include:

1. Importing data using Python libraries such as Pandas and Numpy.
2. Merging datasets to create a comprehensive dataset for analysis.
3. Data type conversion and rounding to ensure data consistency.

## Exploratory Data Analysis

The project includes an exploratory data analysis to understand the correlations between different factors and the U.S. National Home Price Index. The main findings include:

- Strong positive correlation with GDP, indicating a robust economy is associated with higher home prices.
- Positive correlation with population, showing that as the population increases, home prices tend to rise.
- Weak negative correlation with mortgage rates, suggesting that higher mortgage rates may lead to slightly lower home prices.
- Negative correlation with the unemployment rate, indicating that as unemployment rates increase, there is a tendency for home prices to decrease.
- Strong positive correlation with the median sales price of houses sold, reflecting market dynamics.

## Model Selection and Evaluation

The project explores various regression models to predict home prices. It uses grid search and cross-validation to select the best model. The selected model, based on the highest score, is the RandomForest Regressor. This model provides the best fit for the dataset, achieving a score of 0.9905.

## Conclusion

The analysis provides valuable insights into the factors influencing U.S. home prices. Key takeaways include the impact of GDP, population, mortgage rates, and unemployment on home prices. These findings have significant implications for various stakeholders in the real estate industry, such as homebuyers, sellers, developers, and policymakers.

By understanding these relationships, informed decisions can be made regarding investments, sales strategies, and economic policies in the real estate market.

## Acknowledgments

- Data sourced from [fred.stlouisfed.org](https://fred.stlouisfed.org/).
- Python libraries used for analysis: Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn.


