# Introduction
This is a data analysis project on the stock market and the S&P 500 (SPX). The S&P 500 is known as the Standard and Poor's 500 index, which is a stock market index that tracks the 500 publicly leading traded companies in the USA. 

This EDA involves libraries such as Pandas, Numpy, Matplotlib, and Seaborn to retrieve patterns and visualize data trends from the S&P 500 Historical Dataset. The dataset used can be found in the files above.

This EDA will cover: </br>
1. Finding missing values </br>
2. Exploring categorical features

# Importing the Libraries
These libraries are necessary for this analysis as they enable the opportunity to manipulate data, perform basic statistical calculations, and plot the data.
![Screenshot 2025-05-22 at 3 55 04 PM](https://github.com/user-attachments/assets/985f19cd-e73a-49e0-870a-6695f305ef8a)

# Loading the Dataset
The dataset is loaded onto the notebook using the read_csv() module from the pandas library, which converts comma-separated values into a pandas DataFrame. 

# Exploring the Dataset
In the image below, the first 5 rows of the S&P 500 DataFrame is displayed. This is performed by using the head() module from the pandas library. 

The info() module displays the information of the DataFrame such as the index dtypes, columns, non-null values, and the memory usage. The information of the S&P 500 DataFrame is displayed below.

The describe() module describes the numerical values of the DataFrame. 
