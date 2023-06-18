This project focuses on analyzing the data of two well-known cryptocurrencies, Bitcoin and Ethereum, using the powerful data manipulation library, pandas. By applying data wrangling skills, we aim to gain insights and answer questions related to these cryptocurrencies.
Dataset
To begin our analysis, we import the datasets from Kaggle, which can be found here. These datasets provide comprehensive price information for Bitcoin and Ethereum, spanning from their inception to 2023.

Project Overview
Here's an outline of the analysis steps performed in this project:

Data Overview: Before diving into the analysis, we start by obtaining an overview of the data using methods such as head, tail, and info. This step helps us familiarize ourselves with the structure and contents of the DataFrames.

Highest Closing Prices: Next, we identify the three highest closing prices for both Bitcoin and Ethereum. By utilizing the sort_values function, we sort the DataFrames based on the closing prices to determine the highest values.

Average Volume in 2020: We calculate the average trading volume for both cryptocurrencies specifically for the year 2020. This allows us to gauge the overall trading activity during that period.

Cryptocurrency Comparison: To compare Bitcoin and Ethereum, we merge the two dataframes based on the date. We create a new column representing the difference in closing prices between the two cryptocurrencies. Additionally, we calculate the average, minimum, and maximum differences.

Relative Increase in Closing Prices: We construct a new DataFrame that showcases the relative increase in closing prices over time. This enables us to track the percentage of days on which the prices of Bitcoin and Ethereum either increased or decreased.

Comparing BTC and ETH Price Changes: Finally, we address the question of how frequently the change in Bitcoin's price exceeds that of Ethereum's. By analyzing the data, we find that Bitcoin's price change exceeds Ethereum's in approximately 52.43% of days.
