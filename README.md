
# Stock Price Analysis with Python

## Overview
This project aims to perform a comprehensive analysis of stock prices using Python and popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The analysis includes ETL (Extract, Transform, Load) operations, visualization of stock price trends, calculation of moving averages, and exploration of stock returns and correlations.

## Key Features
- **Data Extraction**: Multiple datasets containing stock price data for various companies are loaded simultaneously using the glob module.
- **Data Cleaning and Preparation**: The datasets are concatenated and cleaned to handle missing values and ensure consistency.
- **Exploratory Data Analysis (EDA)**: Various aspects of the stock price data are explored, including statistical summaries, identification of unique companies, and visualization of price trends over time.
- **Moving Average Calculation**: Moving averages with different window sizes are calculated to identify trends and smooth out price fluctuations.
- **Price Change Analysis**: The percentage change in stock prices, particularly for Apple stock, is calculated to understand volatility and trends.
- **Daily Returns Calculation**: Daily returns for Apple stock are computed to analyze the performance over time.
- **Sampling**: The stock price data for Apple is resampled at different frequencies (monthly, yearly, and daily) to observe aggregated trends.
- **Multivariate Analysis**: Correlation and covariance between the closing prices of different companies are explored through visualization techniques such as pair plots and heatmaps.


## Results
- **Graphs of Yearly and Closing Prices**: Visualizations depicting changes in stock prices over time for selected companies.
- **Moving Average Graphs**: Plots illustrating moving averages with window sizes of 10, 20, and 30 for each company.
- **Price Change and Daily Returns Graphs**: Graphs showcasing the percentage change in Apple stock prices and daily returns.
- **Sampling Results**: Plots displaying resampled data for Apple stock at different frequencies (monthly, yearly, and daily).
- **Multivariate Analysis Visualizations**: Pair plots and heatmaps showing correlations between closing prices of different companies.

## Conclusion
This project demonstrates how Python and its libraries can be utilized for in-depth analysis of stock price data. By leveraging ETL techniques, visualization tools, and statistical methods, valuable insights into stock market trends and correlations can be gained, aiding in investment decision-making processes.

## Figures
1. ![Yearly and Closing Prices Graphs](figures/1.png)
2. ![Moving Average Graphs](figures/2.png)
3. ![Price Change and Daily Returns Graph](figures/3.png)
4. ![Monthly Sampling Plot](figures/4.png)
5. ![Yearly Sampling Plot](figures/5.png)
6. ![Daily Sampling Plot](figures/6.png)
7. ![Pair Plot](figures/7.png)
8. ![Correlation Heatmap](figures/8.png)

**How to Use**
Clone the repository to your local machine.
Install the required Python libraries (pandas, numpy, matplotlib, seaborn) if not already installed.
Run the Python script in your preferred environment (e.g., Jupyter Notebook) to execute the analysis.
View the generated plots and analysis results to gain insights into the stock price data.
Future Enhancements
Include more companies' stock price data for a broader analysis.
Implement additional statistical analysis techniques to explore the data further.
Enhance the visualization by incorporating interactive plots or dashboards.
Contributors
Harshitha Varma Penumatsa.
License
This project is licensed under the MIT License.



