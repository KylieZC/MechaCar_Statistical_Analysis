# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
### Deliverable 1

1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
![1p](screenshots/1p.png)
In the summary output, each Pr(>|t|) value represents the probability that each coefficient contributes a random amount of variance to the linear model. Based on the Pr(>|t|) value, **ground clearance** and **vehicle length** are statistically likely to provide non-random amounts of variance to the linear model. In other words the vehicle length and clearance have a litter impact on miles per gallon MechaCar prototype. On contrast, **vehicle weight, spoiler angle** and **All Wheel Drive (AWD)** are statistically unlikely to provide random amounts of variance to the linear model.

2. Is the slope of the linear model considered to be zero? Why or why not?
![2lm](screenshots/2lm.png)
No, the slope of the multiple linear regression model is not equal to zero. Because the p-value is 5.35e-11, which is much smaller than the presumed significance level of 0.05. Therefore, we should **reject the null hypothesis** of the slope being zero.

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The R-squared of the linear model is 0.7149, indicating that approximately 71% of the mpg prediction can be explained by this model. For that reason, linear model **does predict** mpg of MechaCar prototypes effectively.

### Deliverable 2
