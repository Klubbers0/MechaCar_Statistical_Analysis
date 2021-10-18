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


**All Lots**
The results of the T-test for the suspension coils for all manufacturing lots showed that they are not statistically different from the population mean of 1500 PSI. P-value = 0.0603. Assuming the significance level of 0.05%, it can be stated that there was **not sufficient evidence** to reject our null hypothesis.
![pic4](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/369ec59483d1154dd08a8c5a295458002a3ee211/image4.PNG)

**Lot 1**
The results of the T-test for the suspension coils for Lot 1 showed that they are not statistically different from the population mean of 1500 PSI. P-value = 1 . A p-value generally is not found to be 1; however, when values on both groups are the same, the p-value becomes 1 (0.99). Assuming the significance level of 0.05%, it can be stated that there was **not sufficient evidence** to reject our null hypothesis.

![pic6](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/369ec59483d1154dd08a8c5a295458002a3ee211/image%206.PNG)

**Lot 2**
The results of the T-test for the suspension coils for Lot 2 showed that they are not statistically different from the population mean of 1500 PSI. P-value = 0.6072  Assuming the significance level of 0.05%, it can be stated that there was **not sufficient evidence** to reject our null hypothesis.

![pic5](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/892f488892d1c08fc64b565ab0f33e4b34cb9a24/image5.PNG)

**Lot3** The results of the T-test for the suspension coils for Lot 3 showed that there is a slight statistical difference from the population mean of 1500 PSI. P-value = 0.04168. Assuming the significance level of 0.05%, it can be stated that there was **not sufficient evidence** to reject our null hypothesis.

![pic7](https://github.com/Klubbers0/MechaCar_Statistical_Analysis/blob/892f488892d1c08fc64b565ab0f33e4b34cb9a24/image7.PNG)

## Study Design: MechaCar vs Competition
 *A statistical study that can quantify how the MechaCar performs against the competition* 

 *What metric or metrics are you going to test?* 

The focus of our test would be to evaluate MechaCar's city and highway fuel efficiency in comparison to various competitors' vehicles.

 *What is the null hypothesis or alternative hypothesis?*
H0 (Null Hypothesis): Mechacar prototypes' city and highway fuel efficiency is similar to the competitor's vehicle in the same class.

Ha (Alternative Hypothesis) : MechaCar prototypes' average city and highway fuel efficiency is statistically above or below the competitor's vehicles.
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?* *
