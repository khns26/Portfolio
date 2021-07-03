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

# [Project 3 : Customer Churn Prediction](https://github.com/khns26/Customer_Churn_Prediction)
This project aims to help Telecommunication company to predict its customer churn. I did these three steps in this project:
1. Exploratory Data Analysis
2. Data Pre-Processing
3. Machine Learning Modeling using Random Forest Classifier

Exploratory Data Analysis helped me to understand the data that is being used, we will know the distribution of the data, the frequency, correlation, etc. In general, EDA will cover these steps:
- Univariat Analysis : descriptive analysis with 1 variable.
- Bivariat Analysis : relations analysis with 2 variables.
- Multivariat Analysis : analysis with more than 2 variables.

In this case, we'll be covering the distribution of :
- Percentage of distribution of churn/not churn from all the data
- Distribution of predictor variables over the label

<p align="center">
  <img src="https://github.com/khns26/Customer_Churn_Prediction/blob/main/custchurn.png" alt="EDA"/>
</p>

From the graph above we know that the less the monthly charges, the less the possibilities to do churn. For the total charges, the data is not significant. And for tenure, we see that the longer customer subscribe the company, the less their possibilities to churn. 

Then, i did preprocessing to the data and model it using Random Forest Classifier. 
<p align="center">
  <img src="https://github.com/khns26/Customer_Churn_Prediction/blob/main/Accuracy%20of%20training%20data.png?raw=true" alt="EDA"/>
</p>

<p align="center">
  <img src="https://github.com/khns26/Customer_Churn_Prediction/blob/main/Accuracy%20of%20testing%20data.png?raw=true" alt="EDA"/>
</p>

From the training data above, the model could predict data with accuracy 100%. From the testing data, model could predict 78% accuracy. This shows that our model is over fitting. So, for the next session we can try the other model and choose the best model.

# [Project 4 : Indonesia COVID-19 Data Analysis](https://github.com/khns26/Indonesia-COVID-19-Analysis-using-Python)
In this project, i analyzed COVID-19 data in Indonesia using API provided in covid19.go.id. The first thing that i did in this project is cleaning the data. After that i tried to visualize the daily positive COVID-19 cases in West Java, one of the provinces in Indonesia. 
<p align="center">
  <img src="https://github.com/khns26/Indonesia-COVID-19-Analysis-using-Python/blob/main/dailypositivewestjava.png?raw=true"/>
</p>

Then, i had a question in my mind, what happened in July 2020? Why there was a significant increasing cases? I googled it and it was because of Secapa AD cluster. And there was also spike on March 2021 untill July 2021. Based on what i searched, it was because many people feel safe after got vaccinated so they ignored the health protocol. 

What about the recovered cases? The data has already been provided in API. I visualized them to see what the data looked like.

<p align="center">
  <img src="https://github.com/khns26/Indonesia-COVID-19-Analysis-using-Python/blob/main/recovered.png?raw=true"/>
</p>

And the death cases?

<p align="center">
  <img src="https://github.com/khns26/Indonesia-COVID-19-Analysis-using-Python/blob/main/death.png?raw=true"/>
</p>

And for last thing i wanted to visualize the accumulative of active cases, recovered cases, and death cases in the same axes.

<p align="center">
  <img src="https://github.com/khns26/Indonesia-COVID-19-Analysis-using-Python/blob/main/dinamika.png?raw=true"/>
</p>

We can see that the recovered cases keep increasing but the death also the active cases show no significant numbers. Even so, we must remain careful and still obey the health protocols. And don't be afraid to get vaccinated. Stay safe everyone!
