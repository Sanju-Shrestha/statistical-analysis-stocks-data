## Stock Market Data Analysis using Python

This project focuses on analyzing historical stock data for insights into price patterns, outlier detection, traded volume, and dividend impact. We use Python's data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn to conduct this analysis.

### Objectives
  - Understand Price Distribution: Examine the central tendency and spread of the stock’s closing prices.
  - Identify Outliers: Detect and analyze outliers in closing prices to understand abnormal price behaviors.
  - Analyze Volume Patterns: Study traded volume trends to identify patterns and possible anomalies.
  - Impact of Dividends on Price: Explore how historical dividend announcements affected stock prices and volume.

### Steps Completed
1. Data Preparation
  - Loaded the stock data into a Pandas DataFrame. The data has been loaded from my private GitHub repository.
  - Extracted relevant columns: published_date, open, high, low, close, per_change, traded_quantity, traded_amount.

2. Descriptive Statistics
  - Mean, Median, Mode: Calculated central tendency metrics for the close price.
  - Skewness Analysis: Observed that mean > mode > median indicated a right-skewed distribution.

3. Data Visualization
  - Histogram and KDE Plot: Plotted closing prices to visualize skewness.
  - Box Plot: Used to detect and highlight outliers in the close prices.

4. Outlier Analysis
  - Identified periods with high close prices as outliers.
  - Investigated possible reasons for these spikes, including limited stocks in the sector and high dividend payouts.

5. Volume Analysis
  - Analyzed traded volume patterns and detected higher-than-average traded quantities around certain timeframes.

6. Dividend Impact Analysis
  - Reviewed historical dividend distribution data.
  - Analyzed the correlation between dividend announcements and stock price/volume changes.


Requirements
- Python Libraries: Pandas, NumPy, Matplotlib, Seaborn
- IDE: Jupyter Notebook or any Python-compatible IDE

How to Run
- Ensure all required libraries are installed.
- Load the data and follow the analysis steps outlined in the notebook.
