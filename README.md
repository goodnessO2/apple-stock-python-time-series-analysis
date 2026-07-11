# Apple Stock Market Analysis Using Python

## Project Overview

This project analyzes Apple Inc. (AAPL) historical stock market data over a 5-year period using Python. The goal of the analysis was to apply advanced Pandas techniques, perform time-series analysis, engineer useful features, and generate insights from stock market trends.

The dataset was obtained from Yahoo Finance and contains daily stock market records, including opening price, high price, low price, closing price, adjusted close price, and trading volume.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Yahoo Finance / yfinance
- Google Colab

## Dataset Features

The original dataset contained the following columns:

- Date
- Open
- High
- Low
- Close
- Adjusted Close
- Volume

The dataset contained 1,255 rows and 7 original columns, representing daily Apple stock trading records over a 5-year period.

## Data Cleaning and Transformation

The dataset was checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Date formatting issues
- Proper time-series ordering

No missing values or duplicate records were found. The Date column was already in datetime format, and the dataset was sorted from the oldest date to the newest date.

## Feature Engineering

Several new features were created to support deeper analysis:

- Year
- Month
- Month Name
- Daily Price Change
- Daily Percentage Change
- 7-Day Moving Average
- 30-Day Moving Average
- Trading Range
- 30-Day Rolling Volatility
- Monthly Return

These features helped reveal daily movement, monthly performance, price trends, and volatility patterns.

## Key Insights

- Apple’s closing price showed an overall upward trend across the 5-year period, despite short-term declines and fluctuations.
- The lowest average closing price occurred in January 2023, showing one of the weaker periods in the dataset.
- The highest average closing price occurred in July 2026, although this may represent partial-month data.
- December 2021 recorded the highest trading volume, indicating strong market activity.
- July 2022 had the strongest monthly return at about 18.86%.
- December 2022 had the weakest monthly return at about -12.23%.
- The moving average analysis showed that the 30-day moving average provided a smoother view of the broader stock trend.
- Volatility analysis showed periods of higher price fluctuation, especially around 2025.

## Recommendations

- Closing price trends should be analyzed together with moving averages to better understand long-term stock direction.
- Monthly returns should be reviewed to identify periods of strong and weak stock performance.
- Volatility should be considered when evaluating stock risk and uncertainty.
- Trading volume should be analyzed alongside price movement because volume spikes may indicate increased investor activity.
- Future analysis can compare Apple’s stock performance with other technology stocks or broader market indexes such as NASDAQ or S&P 500.

## Conclusion

This project demonstrated how Python and Pandas can be used to analyze historical stock market data. Through data cleaning, transformation, feature engineering, time-series analysis, and visualization, meaningful insights were extracted from Apple Inc. stock data.

The analysis showed that Apple’s stock had an overall upward trend over the 5-year period, while still experiencing periods of decline, volatility, and fluctuating monthly returns.

## Project Files

- `Apple_Stock_Advanced_Python_Analysis.ipynb` - Python notebook
- `Apple_Stock_Insight_Summary_Report.pdf` - Insight summary report
- `AAPL_cleaned_featured_data.csv` - Cleaned and featured dataset
- `AAPL_monthly_summary.csv` - Monthly summary analysis
- `images/` - Project visualization screenshots

## Hashtags

#Python #DataAnalysis #TimeSeriesAnalysis #Pandas #DataScience #Analytics #AnalystLabAfrica
