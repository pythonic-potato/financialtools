The purpose of this tool is to help investors determine whether a stock or index has deviated from a long term trend.

TrendPlotter.py is a Python program that takes in a csv file with stock data and plots the data with long term trend lines representing a good, poor, and average case scenario. The average case (blue trend line) is adjustable by clicking on the y-axis at the last year of csv data. The algorithm for fitting the line finds the compound interest rate such that if applied to the first data point will end up at the average price over the last three years in the average case. Similarly, the green and red (good and poort) trend lines show this tendencey for the high and low points over the last three years, respectively.  

A sample csv file of the S&P 500 index data is included for reference, which was downloaded from Yahoo finance. Running the program will open a browse window to select the csv file. In addition, the end of the average trend line computes the 10 year compounded interest from the end of the source (csv) data to the end of the trend line.  In other words, this is the expected rate of return for the ten years of the extended trendline. 

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
