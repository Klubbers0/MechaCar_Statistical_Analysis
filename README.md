# MechaCar Statistical Analysis

## Linear Regression to Predict MPG
![pic1](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/f6587d1c56c9e643939f8af34379b304daa4ed1a/image1.png)

*Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables ground_clearance and vehicle_length (as well as the intercept) are statistically unlikely to provide random amounts of variance to the linear model, these variables have a significant impact on the miles per gallon on the MechaCar prototype* *

*Is the slope of the linear model considered to be zero? Why or why not?*

The **p-value: 5.35e-11** is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject null hypothesis and the slope of the linear model is not zero.

*Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?*

This linear model has **R-squared: 0.7149**, which means that approximately 71% of all mpg predictions will be determined by this model. This model predict mpg of MechaCar prototypes effectively.


## Summary Statistics on Suspension Coils
*The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?*

The variance for entire manufacturing lot is 62.293 which meets the current manufacturing design specification. The variance for Lot1 is 0.9795 and Lot2 is 7.4693 and these two lots also meet the design specification. However variance for Lot3 is 170.286 which exceeds the limit of 100 pounds per square inch and therefore Lot3 of suspension coils may not be accepted.
**Total Manufacturing Lot**

![pic2](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/e5c4a385fbfc5851497c5078ccb0a6403e2a0628/image%202.PNG)

**Individual manufacturing lot**

![pic3](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/e5c4a385fbfc5851497c5078ccb0a6403e2a0628/image3.PNG)
## T-Tests on Suspension Coils
Lot 1 and Lot 3 the PSI values are not different from the population mean. However lot 2 the p-value is .347 which means there is evidence that the suspension coil is different from the population mean. Images of all T-tests are attached below. 

![pic4](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/55691f7061e18422647e677febbe837b8c716a92/image4.PNG)
![pic5](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/55691f7061e18422647e677febbe837b8c716a92/image5.PNG)

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
