# Ride-Forecast-ML

# Linear Regression Assignment
- Tool: `Google Colab`
## Introduction
- With the increasing number of people using services like Uber and Careem for their daily commute, we aim to improve the user experience by introducing machine learning to the service. Our goal is to predict the region in the city with the least gap between demand and supply.

## Implementation
- Data Collection
We use order data files and a cluster map file from the training data folder. Order data files contain order id, driver id, time, price, and region details. The cluster map file contains 66 distinct region hashes and their IDs. We store all this data in respective CSV files and then map these region hashes with the hashes in the order data CSV file to produce another CSV file that contains the supply-demand gap along with timestamps and region IDs.

- Linear Regression
We apply Linear Regression using the sklearn library. After training the model, we calculate the Mean Absolute Error and use it to predict the values for each timestamp of each region. A graph is also plotted to provide a visual representation of the Linear Regression analysis and its performance on the provided dataset. The graph is plotted using matplotlib.


## Training Data
[training_data](https://drive.google.com/drive/folders/1WldT3iLe9p9Yd1byN6RC_N9iiD3gtRiS?usp=drive_link)