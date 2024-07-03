# Linear Regression Model- Boombike

> The **Bike-Sharing Demand Prediction Project** aims to develop a **predictive model** to estimate the **demand for shared bikes** in the **American market** for **BoomBikes**, a **bike-sharing provider** looking to **accelerate revenue** post the **Covid-19 pandemic**. The project involves **thorough data exploration** and **preprocessing**, followed by **variable selection techniques** to identify the most significant features affecting bike demand. **Linear regression models**  attempted and tuned using appropriate principles to optimize their performance. **Residual analysis**  performed to validate the model assumptions and ensure accuracy.

> By successfully building an accurate predictive model, BoomBikes will be better prepared to cater to the **demand dynamics** of the bike-sharing market and **stand out** as a **leading service provider**. The project aims to provide **valuable insights** for **business decision-making** and **strategy formulation** post the Covid-19 lockdown period.

## Table of Contents
* [**General Info**](#general-information)
* [**Technologies Used**](#technologies-used)
* [**Conclusions**](#conclusions)
* [**Acknowledgements**](#acknowledgements)
* [**Contact**](#contact)

## General Information
- It aims to model the demand for shared bikes in the American market for a bike-sharing provider, BoomBikes. Mention the goal of understanding the factors affecting bike demand and preparing a business plan to accelerate revenue after the Covid-19 pandemic.
-  Various regression models are  attempted and tuned using appropriate principles to optimize their performance. Residual analysis  performed to validate the model assumptions and ensure accuracy.
    - **Data Exploration and Preprocessing**: We have started by exploring the dataset to gain insights into the features and their relationships with the target variable (bike demand). Missing values, outliers, and data inconsistencies handled during preprocessing.

    - **Variable Selection Techniques**: We used appropriate variable selection techniques to identify the most significant features that contribute to the bike demand prediction.

    - **Model Building**: We have attempted various regression models, considering both linear and non-linear approaches, to predict bike demand. The models is tuned using correct principles to optimize their performance.

    - **Residual Analysis**: After model building, we performed residual analysis to validate the assumptions and ensure the models meet the required criteria for accuracy and reliability.

    - **Model Evaluation**: We used appropriate evaluation metrics to assess the performance of the models and choose the best one based on key performance indicators.

- The goal of the project is to build a predictive model that can accurately estimate the demand for shared bikes based on various independent variables such as weather conditions, people's behavior, and other factors. The model will be used to understand how different features affect the demand and help the management manipulate the business strategy accordingly.
- The dataset used in this project contains daily bike demand data across the American market, along with several independent variables that may influence the demand. The data includes information about meteorological surveys, people's routine, and other relevant factors.

## Conclusions
- The analysis of the bike rental data reveals several key insights that can aid in **decision-making** for our bike-sharing company. We observed a strong positive correlation between bike rentals and **temperature**, indicating higher rentals during warmer days. Additionally, **humidity**, which is directly linked to temperature, also influences bike rentals positively.

- Bike rentals are at their peak on **Sundays**, suggesting the importance of weekend promotions and marketing strategies. Moreover, bike rental popularity witnessed an increase in **2019**, potentially due to **Covid-19's impact on people's purchasing power**, making bike rentals a more preferred option.

- **Top four variables** significantly impacting bike rental counts are **Spring season**, **Temperature**, different **weather conditions** (e.g., Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist), and **Sunday**.

- The count of casual and registered users was higher in 2019 compared to 2018, and registered users outnumbered casual users in both years.

- The **number of bike registrations** was higher in **September 2019** compared to other months that year, whereas in **2018**, **June** witnessed the highest number of bike registrations.

## Technologies Used
- **numpy** - version 1.21.3
- **pandas** - version 1.5.3
- **matplotlib** - version 3.4.3
- **seaborn** - version 0.12.2
- **sklearn** - version 1.2.1
- **statsmodels** - version 0.13.5

## Acknowledgements
Give credit here.
- The training provided by **IIIT Bangalore** greatly contributed to the successful execution of this project.
- This project was based on [this tutorial](https://learn.upgrad.com/course/4617/segment/27465/225458/689472/3488520).


