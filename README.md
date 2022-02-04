# MechaCar_Statistical_Analysis
- R
## Linear Regression to Predict MPG
The below picture shows the multiple linear regression to predict the mpg by vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD.
![](https://user-images.githubusercontent.com/64121596/152512163-d83ab0d5-044d-401b-970e-8a04c466dfb8.png)
1. In the summary output, if we look at Pr(>|t|), each value represents the probability that each coefficient contributes a random amount of variance to the linear model. In the result, vehicle length and ground clearance (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. In other words the vehicle length and ground clearance have a significant impact on mpg. 
2. If we look at the p value of our multiple linear model, it's 5.35e-11. It's a sufficient to reject our null hypothesis that the slope is 0. Therefore, our slope is not 0.
3. According to the summary output, the r-squared value in the multiple linear regression model is 0.71 while the p-value remained significant.Therefore, this model predicts the mpg of MechaCar prototypes effectively. 

## Summary Statistics on Suspension Coils
![](https://user-images.githubusercontent.com/64121596/152516284-a301be53-d09f-4224-bfba-565cb388ab49.png)
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? 
- All over the manufacturing process, it satisfies the requirement that suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Because the variance overall is 62,3.
- However, in Lot 1, the variance is 98. It barely before the requirement. 
- In Lot 2, the variance is 7.47, which is very low and good.
- But in Lot 3, the variance is 170, which doesn't satify the requirement.
## T-Tests on Suspension Coils




## Study Design: MechaCar vs Competition
In my study design, the success metrics that would be of interest to a consumer could be safety rating. If the success metric is numerical and the sample size is large, we use a two-sample t-test. The null hypothesis is that there is no real effect behind the data your test has produced. We would use a data that has historical data of vehicle weight, vehicle length, and other variables. Because we want to measure if a slight change in one of these variables could change the safety rating.



