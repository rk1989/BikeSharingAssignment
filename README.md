# Project Name
> Bike Sharing Assignment

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Background
- A US bike-sharing provider BoomBikes is a bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
- It is finding it very difficult to sustain in the current market scenario becuase of ongoing Corona pandemic.
- It aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19
- They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Business Goal
- To model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. - Provide general information about your project here.

Dataset
- Bike sharing dataset "day.csv" is used for the model building and analysis


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Final regression equation built by the model is

  cnt = 0.1807 + 0.2302*yr - 0.0785*holiday + 0.0479*weekday + 0.5947*temp - 0.1393*hum - 0.1934*windspeed - 0.2392*Light_rain_snow - 0.0542*Mist + 0.1367*Fall_Winter + 0.0769*Summer
  
  - Model fits good with the feature set : year, holiday, weekday, temp, hum, windspeed, Weathersit dummies - Light_Rain_Snow, Mist, Season dummies - Fall_Winter and Summer.
  
  - Top 3 features that contribute significantly towards explaining the demand of the shared bikes are – 
    Temperature – With other variables held constant, demand of the shared bikes increases by a factor of 0.5947 (almost 60%) with temperature.
    Year – With other variables held constant, demand of the shared bikes increases by a factor of 0.2303 (almost 23%). This means the demand increased specifically in the year 2019.
    Humidity – With other variables held constant, demand of the shared bikes increases by a factor of 0.1392 (almost 14%) with humidity. 

- The model fits with a R-squared value of 0.828. The R-squared value of the predicted values over test set is 0.79

- The residual analysis confirms a good fit by checking the distribution of the error terms both with the help of a distplot and Q-Q plot


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - version 1.5.3
- matplotlib - version 3.7.1
- seaborn - version 0.12.2
- scikit-learn - version 1.2.2
- numpy - version 1.24.3
- statsmodels - version 0.13.5


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
References
- https://pandas.pydata.org/docs/index.htmlGive 
- https://seaborn.pydata.org/
- https://www.statsmodels.org/stable/index.html
- https://scikit-learn.org/stable/


## Contact
Created by [@rk1989] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
