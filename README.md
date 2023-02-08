# NUWE_VuelyTONG_DataScienceProject
![my vion image](Vio.png)



# Can we predict the most popular destination for our next season!?!

This repository contains the files necessary to participate in the **Vueling tech hackaton** orginezed by **Nuwe**. 

It contains:
- ***Exploration_Data_Analysis.ipynb***: Exploratory Data Analysis (EDA) in a Jupyter notebook.
- ***Model_Evaluation_SLAClassification.ipynb***: Another Jupyter notebook with the pre-processing of the dat set, selection of best classification model, hyper-parameter tunning, and evaluation of the selected model results with the best parameters.
- ***Model_Prediction_SLAClassification.ipynb***: Finally, another Jupyter notebook, with where we take our best model and predict the target. 
- ***requirements.txt***: text file with the requirements needed to reproduce the models.

About the results: 
- The best model for our case was: **Random Forest Classifier**
- The best score of the model has been: **0.77**
 




## ✈️ Context

At the last Annual General Assembly of IATA, the zero net CO₂ emissions in 2050 (aviation sector) resolution finally got approved. That lets us be one step closer to the Paris Agreement of 2015, accomplishing not exceeding 1.5 ºC the Earth's temperature.

As a data science student from the ITAcademy the challenge has been accepted! 💪

Therefore, the main objective of this data science project with machine learning is to predict future most popular flight destination to allocate the most possible correct seats per kilometer and flight and reduce CO2 emissions! 💨✈️ 



## 🦾 About the challenge:

The information of the Datasets is from the history of air routes. 

***Datasets:***

- **Date**: Flight date. Year and Month.
- **Origin_Country** : Country of origin.
- **Origin_Continent** : Continent of origin.
- **Destination_Country**: Country of destination.
- **Destination_Continent**: Destination continent.
- **Total_flights**: Total number of flights.
- **Total_seats**: Total number of seats.
- **Total_ASKs**: (Available Seat Kilometer). Total seat numbers available by the total number of km these seats have flown.

Our TARGET is **Destination_Country**
## 🧾Archives:

- **train.csv** - This dataset contains both predictor variables and the target variable.
- **test.csv** - This dataset contains both predictor variables and the target variable.
## 👩‍💻 Let's get cracking coding!

***1. Exploratory data analysis (EDA) - Jupyter Notebook***

Here we present the dataset. 


1.1. Univariate Analysis:

- Start by exploring each variable one by one and generating summary statistics such as count, mean, median, standard deviation, etc.
- Create histograms to visualize the distribution of each numerical variable.
- Create bar plots to visualize the frequency of each category in categorical variables such as "Origin Country", "Origin Continent", "Destination Country", and "Destination Continent".

1.2. Bivariate Analysis:

- Compute pairwise correlations between the numerical variables to identify any relationships between them.
- Create scatter plots to visualize the relationship between each pair of numerical variables.
- Create bar plots to visualize the relationship between each pair of categorical variables.

1.3. Multivariate Analysis:
- Create a heatmap to visualize the correlations between all the variables.


1.4. Time Series Analysis:
- Create line plots to visualize the trends in "Total flights", "Total seats", and "Total ASKs" over time, aggregated by year and/or month.
- Check for seasonality and trend in the time series data.

1.5. Geographical Analysis:

- Create a choropleth map to visualize the distribution of flights based on "Origin Country" and "Destination Country".



***2. Model prediction Jupyter Notebook***

