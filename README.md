# Bike Sharing Assignment by Irfan Khan Mohammed
This is project is developed using Multiple Linear Regression concept for UpGrad and IIITB course of Machine Learning & AI


## Table of Contents
* [General Info](#problem-statement)
* [Business Info](#business-objective)
* [Analysis Performed](#steps-used)
* [Conclusions](#conclusions)
* [Results](#analysed-details)
* [Final Statements](#business-goals)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## Business Objective
- Required to model the demand for shared bikes with the available independent variables.
- It will be used by the management to understand how exactly the demands vary with different features.
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.
- Further, the model will be a good way for management to understand the demand dynamics of a new market. some factors.


## Steps Used
- Step 1: Reading and Understanding the Data
- Step 2: Visualizing the Data
- Step 3: Data Preparation
- Step 4: Splitting the Data into Training and Testing Sets
- Step 5: Building a linear model
- Step 6: Residual Analysis of the train data
- Step 7: Making Predictions Using the Final Model
- Step 8: Model Evaluation
- Step 9: Conclusion


## Conclusions
- Train - $ R^2 $ = 0.835
- Train - Adjusted $ R^2 $ = 0.832
- Test - $ R^2 $ = 0.796
- Test - Adjusted $ R^2 $ = 0.773
- Difference in $ R^2$  between train and test = 3.9%
- Difference in adjusted $ R^2 $ between Train and test = 5.9%
- Since difference between $ R^2 $ and Adusted $ R^2 $ in test case is 2.3% that is less than 5% difference.
- We can conclude that this is the best model


## Analysed Details
- Rentals = $ 0.5499 X temp + 0.2331 X Year + 0.1307 X winter + 0.0974 X Sep + 0.0886 X summer + 0.0675 X Sat + 0.0561 X workingday + -0.08 X MistCloudy + -0.1552 X windspeed + -0.2871	LightSnow $
- We can see that temperature variable is having the highest coefficient 0.5499, which means if the temperature increases by one unit the number of bike rentals increases by 0.5499 units.
- We also see there are some variables with negative coefficients. A negative coefficient suggests that as the independent variable increases, the dependent variable tends to decrease.
- We have "Mist + cloudy = -0.08", "windspeed = -0.1552" , "light Snow = -0.2871" variables with negative coefficient.
- The negative coefficient value signifies how much of the dependent variable changes given a one-unit shift in the independent variable while holding other variables in the model constant.


## Business Goals
- Temperature could be a prime factor for making decision for the Organisation
- We can see demand for bikes was more in 2019 than 2018
- Working days as they have good influence on bike rentals. So it would be great to provide offers to the working individuals
  
## Technologies Used
Python libraries like:
- numpy
- pandas
- matplotlib.pyplot
- seaborn
- statsmodels.api
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@ikhan3rd] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
