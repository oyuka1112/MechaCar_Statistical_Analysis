# MechaCar_Statistical_Analysis
- R
## Linear Regression to Predict MPG
The below picture shows the multiple linear regression to predict the mpg by vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD.
![](https://user-images.githubusercontent.com/64121596/152512163-d83ab0d5-044d-401b-970e-8a04c466dfb8.png)
1. In the summary output, if we look at Pr(>|t|), each value represents the probability that each coefficient contributes a random amount of variance to the linear model. In the result, vehicle length and ground clearance (as well as intercept) are statistically unlikely to provide random amounts of variance to the linear model. In other words the vehicle length and ground clearance have a significant impact on mpg. 
2. If we look at the p value of our multiple linear model, it's 5.35e-11. It's a sufficient to reject our null hypothesis that the slope is 0. Therefore, our slope is not 0.
3. According to the summary output, the r-squared value in the multiple linear regression model is 0.71 while the p-value remained significant.Therefore, this model predicts the mpg of MechaCar prototypes effectively. 




