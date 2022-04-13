# Linear regression assignment:
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents:
* Business Goal:
* Analysis approach
* Insights
* Assignment-based Subjective Questions and General Subjective Questions

<!-- You can include any other section that is pertinent to your problem -->

## Business Goal:
- We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how 
exactly the demands vary with different features.
- They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
- Further, the model will be a good way for management to understand the 
demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Analysis approach:
◦ Performed EDA and analysis the basic variables
◦ Creating dummies and drop the unneeded rows
◦ Create the linear model and check for P values
◦ Drop column if P value is higher than limit
◦ Check for VIF and drop the column if VIF is higher.
◦ After multiple model building we found that model 11 is best fit.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Insights
➢ As per summary our model's R-squared model is 79.7 and adjusted R-squared model is 79.1
➢ Test R-squared is 77.5 and adjusted R-squared model is 77.4
➢ Best equation fits with respect to above summary for cnt= 0.246 X yr -0.0836 X holiday - 0.198 X Spring 
- 0.321 X Light snow - 0.089 X Mist+Cloudy +0.063 X 3 + 0.123 X 5 +0.151 X 6 +0.153 X 8 + 0.193 X 9 -
0.049 X Sun + 0.126 X 7 + 0.115 X 10
➢ Demand of bike can be say using below column values
➢ -yr ,holiday,Spring,Mist+Cloudy,Light Snow,3,5,6,7,8,9,10,sunday -Demands increases in the month of 
3,5,6,7,8,9,10 -Demand decreases if it is holiday, Spring,Light snow, Mist+cloudy, Sunday.
➢ -Demand is higher in month of 3, 5 , 6, 8, 9 ,7 and 10

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Assignment-based Subjective Questions and General Subjective Questions


## Contact
Created by [@Vigneshwar-97] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
