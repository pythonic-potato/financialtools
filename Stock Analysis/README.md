The purpose of this tool is to help investors determine whether a stock or index has deviated from a long term trend.

TrendPlotter.py is a Python program that takes in a csv file with stock data and plots the data with long term trend lines representing a good, poor, and average case scenario. The average case (blue trend line) is adjustable by clicking on the y-axis at the last year of csv data. The algorithm for fitting the line finds the compound interest rate such that if applied to the first data point will end up at the average price over the last three years in the average case. Similarly, the green and red (good and poort) trend lines show this tendencey for the high and low points over the last three years, respectively.  

A sample csv file of the S&P 500 index data is included for reference, which was downloaded from Yahoo finance. Place your csv file in the same directory as TrendPlotter and update the data_filename in the second to last block of code from "data_filename = 'GSPC.csv'" to "data_filename = 'YOURFILENAME.csv'". Run the Trendplotter.py script and it will generate a plot similar to the one below.

![plot image](https://github.com/NuncObdurat/financialtools/blob/main/Stock%20Analysis/GSPCanalysis.png)

This project requires Python and the following dependencies:

- pandas
- numpy
- matplotlib

To install these dependencies, you can use `pip`. Run the following commands:

- pip install pandas
- pip install numpy
- pip install matplotlib

Note that a significant portion of this code was generated using ChatGPT.
