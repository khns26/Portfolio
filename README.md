# Khansa's Portfolio
Data science portfolio

# [Project 1 : Time Series Analysis](https://github.com/khns26/mini_project/blob/90b98cbf188f9724876d4e5c2ede3dac06de1cfd/Time%20Series%20Forecasting.R)
- Time Series is a series of data that are assembled over even intervals in time and ordered chronologically
- In this project, i analyzed monthly stocks price in 5 years using Box-Jenkins iteration model
- I used UNVR stocks price data from 2016-2020, then i plotted the data like this
<p align="center">
<img src="https://github.com/khns26/mini_project/blob/main/plot%20df_ts.jpg?raw=true"/>
  </p>
  
- The data must be stationary to be modeled. But unfortunately, based on the graphic above our data is not stationary. So i must do differencing process and the result was like this
<p align="center">
<img src="https://github.com/khns26/mini_project/blob/main/plot%20df%20diff.jpg?raw=true"/>
  </p>

- Then i modeled the data using ARIMA(0,1,1) model with MLE as method
- I predicted one month ahead (January 21st, 2021) stocks price using the model
<p align="center">
<img src="https://github.com/khns26/mini_project/blob/main/plot%20ramal%20jan%2021.jpg?raw=true"/>
  </p>
  
- I also plotted the training data and the predicted data
<p align="center">
<img src="https://github.com/khns26/mini_project/blob/main/asli%20vs%20taksiran.jpg?raw=true"/>
  </p>

# [Project 2 : Modeling CO2 Emission and Engine Size Using Linear Regression](https://github.com/khns26/mini_project/blob/90b98cbf188f9724876d4e5c2ede3dac06de1cfd/Modeling_CO2_Emission_and_Engine_Size.ipynb)
- I analyzed data of fuel consumption of vehicles
- And then i scatterplotted the data of CO2 Emission and Engine Size to know the relationship
<p align="center">
<img src="https://github.com/khns26/mini_project/blob/main/scatterplot%20co2%20and%20engine%20size.png?raw=true" alt="Scatterplot of CO2 Emission and Engine Size"/>
  </p>
  
- It told us that the larger engine size, the higher its CO2 Emisson
- Then i modeled the data using Linear Regression and plotted with train data
<p align="center">
  <img src="https://github.com/khns26/Portfolio/blob/main/linreg.png?raw=true" alt="Plot the fitting model"/>
</p>


# [Project 3 : Modeling and Predicting House Prices using Linear Regression](https://github.com/khns26/mini_project/blob/d66e6626afd4e3788a2f4ede62d67a879a9c4dfc/LinearRegression-House%20Price%20Modeling.ipynb)
- I made a model to predict house prices using array of numbers
- This only uses 1 feature which is number of bedrooms

# [Project 4 : Customer Churn Prediction]
This project aims to help Telecommunication company to predict its customer churn. I did these four steps in this project:
1. Exploratory Data Analysis
2. Data Pre-Processing
3. Machine Learning Modeling
4. Determining the best model



