# MechaCar Statistical Analysis

## Overview of Project & Analysis
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

Below are the the analysis and data to assist the manufacturing team with insights on the troubles that AutosRUs has been experiencing.

## Deliverable 1:   
### Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle weight, spoiler_angle and AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance and vehicle_length.

![image](https://user-images.githubusercontent.com/85530690/134785431-cb19d222-ceac-4479-b593-8017d6d28f69.png)


Is the slope of the linear model considered to be zero? Why or why not?
- The p-Value for this model is: 5.35e-11, which is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis.  This information indicates that the linear model is zero.

![image](https://user-images.githubusercontent.com/85530690/134786035-2a4cdd24-6bb2-4da4-a86a-e464d69da412.png)


Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- The multiple r-squared value is 0.7149 which is approximately 71% of the time the model will predict mpg values correctly. There are probably other factors that were not captured in the datasaet that contribute to the mpg variability of the MechaCar prototypes.


## Deliverable 2:
### Summary Statistics on Suspension Coils




## Deliverable 3:
### T-Tests on Suspension Coils
Suspension Coils Cumulative T-test restuls below:

![image](https://user-images.githubusercontent.com/85530690/134790078-92fedc0f-8227-40b9-a6d4-e235f9ae0846.png)


![image](https://user-images.githubusercontent.com/85530690/134790087-600036b6-5a5a-4a30-879d-9c2bbf4809ae.png)


![image](https://user-images.githubusercontent.com/85530690/134790102-1297afc8-ecb6-4189-9d7f-92a7c6a6daf8.png)




## Deliverable 4:
### Study Design: MechaCar vs Competition
What metric or metrics are you going to test?
 -  Using a linear model, perform a statistical study to determine the maintenance cost for the vehicle.   
 
What is the null hypothesis or alternative hypothesis?
- The null hypothesis is that the slope of the linear model is zero.
- The alternative hypothesis is that the slope of the linear model is not zero.

What statistical test would you use to test the hypothesis? And why?
-  I would use simple linear regression to test the hypothesis since this is the most popular for future observations and measures, this would also be beneificial for consumer reports to customers as they make decisions for purchasing cars.

What data is needed to run the statistical test?
- The data that is needed to run this statistical test would be cost of the maintenance based on model of car and past years for reference.


