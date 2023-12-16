# Bike Sharing Assignment
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-   A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. 
-   A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. To come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

- What is the background of your project?
    -   A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- What is the business probem that your project is trying to solve?
    -   Model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
- What is the dataset that is being used?
    -   Bike Sharing historic database ok year 2018 and 2019

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1:
    - F-Statistic
        - Train R-squared:  0.795
        - Train Adjusted R-squared: 0.789
        - Test R-squared: 0.781
        - Test Adjusted R-squared: 0.768
        - The model is Good based on the R-squared and Adj. R-squared metrics.
- Conclusion 2:
    - Equation of Best-Fit Line:

       cnt=0.4559+0.2480*yr+0.0535*workingday-0.1717*windspeed-0.2321*spring-0.0355*winter-0.0973*weathersit_2-0.3098*weathersit_3+0.1041*month_10+0.0521*month_3+0.0762*month_5+0.0988*month_6+0.0988*month_8+0.1429*month_9+0.0615*sunday
- Conclusion 3:
    - Top 3 predictor variables on which influence the bike booking:
        - **year**
        - **month_9(september)**
        - **month_10(october)**
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 
- Numpy 
- Pandas
- Matplotlib 
- Seaborn 
- sklearn 
- statsmodels 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad's Linear Regression Assignment


## Contact
Created by [@AnkushKudungu]


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->