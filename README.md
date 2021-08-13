# Forecasting_Net_Prophet

This notebook utilizes the search trend data and the closing stock price of MercadoLibre to identify if there patterns in the data than consistently predict the future stock price based off the search trend data.  

Below are the steps that will be performed in this notebook.
1. Find unusual patterns in hourly Google search traffic
2. Mine the search traffic data for seasonality
3. Relate the search traffic to stock price patterns
4. Create a time series model with Prophet


## Technologies Require
* This project leverages python version 3.8.5
* Project will be accomplished in https://colab.research.google.com/


## Required Imports
* pandas - data manipulation and analysis
* pystan - platform for statistical modeling and high-performance statistical computation
* holoviews - designed to make data analysis and visualization seamless and simple
* fbprophet - powerful time series analysis package
* hvplot - powerful, modern, interactive plotting libraries
* datetime - supplies classes to work with date and time. 
* matplotlib - visualization library in Python for 2D plots of arrays
 

## Install Guide
* import pandas as pd
* import holoviews as hv
* from fbprophet import Prophet
* import hvplot.pandas
* import datetime as dt
* %matplotlib inline

## Usage
To use the notebook:
1. Clone the repo
2. Open a new chrome window and input the following address  https://colab.research.google.com/
3. Load the files into the environment 

### Contributors
Zach Zwiener

### Contact
Email - zachzwiener3@gmail.com

### License
MIT
