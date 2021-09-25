# MechaCar_Statistical_Analysis

## Overview of Project & Analysis
A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

Below are the the analysis and data to assist the manufacturing team with insights on the troubles that AutosRUs has been experiencing.

## Deliverable 1:   
### Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle weight, spoiler_angle and AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance and vehicle_length.

![image](https://user-images.githubusercontent.com/85530690/134785431-cb19d222-ceac-4479-b593-8017d6d28f69.png)


Is the slope of the linear model considered to be zero? Why or why not?
- The p-Value for this model, p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis.  This information indicates that the linear model is zero.
- 
![image](https://user-images.githubusercontent.com/85530690/134786035-2a4cdd24-6bb2-4da4-a86a-e464d69da412.png)


Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- The multiple r-squared value is 0.7149 which is approximately 71% of the time the model will predict mpg values correctly. There are probably other factors that were not captured in the datasaet that contribute to the mpg variability of the MechaCar prototypes.


## Deliverable 2:
### Summary Statistics on Suspension Coils
(summary that addresses the design specification requirement for all the manufacturing lots and each lot individually)



## Deliverable 3:
### T-Tests on Suspension Coils
(summary of the t-test results across all manufacturing lots and for each lot)


## Deliverable 4:
### Study Design: MechaCar vs Competition
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
