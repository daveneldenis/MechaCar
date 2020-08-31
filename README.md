# MechaCar Statistical Analysis

# MPG Multiple Linear Regression Analysis

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables/coefficients that provided a non-random amount of variance to the mpg values were both ground clearance (3.546) and vehicle length (6.267). Both were greater than 0.05
Is the slope of the linear model considered to be zero? Why or why not?
The slope of the linear model is non zero. The p-value is 5.35e-11 and significant because less than 0.05.
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
The multiple r-squared is 0.7149 whereby 1 would be perfect prediction and 0 not perfect. Therefore, the linear model prediction is 71% accurate. 

# Suspension Coil Summary Statistics

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per inch. Does the current manufacturing data meet this design specification? Why or why not?
Based on the Manufacturing Lot data Lot 1 and Lot 2 meet the 100 PSI criteria at variance 1.146 and 10.131 respectively. However, Lot 3 at 220.010 did not meet 100 PSI criteria.

# Suspension Coil T-Test

Interpretration and findings for the t-test results
The p-values for Lot 1, 2, 3 are 0.9048, 0.3451, and 0.637 respectively. Since the p-values are all above 0.05 we can not reject the null hypothesis and the sample mean is not statistically signig=ficant. Therefore, all lots meet specifications due to the t-test not being statistically significant.

# Performance Comparison of the MechaCar Prototype Vehicle to Comparable Vehicles on the Market

Study Design:
Think critically about what metrics you would think would be of interest to a consumer (cost, fuel efficiency, color options, etc.).
The metrics that would be of interest to the consumer would be fuel efficiency and speed (0-60mph).
Determine what question we would ask, what the null and alternative hypothesis would be to answer that question, and what statistical test could be used to test this hypothesis.
Null Hypothesis: Fuel effieciency determines vehicle purchase
Alternative Hypothesis: Consumers prefer to buy fuel efficient vehicles over speed (0-60mph)
Knowing what test should be used, what data should be collected? The data that needs to be collected for both the MechaCar prototype vehicle and the comparable vehicles would be fuel efficiency data, vehicle purchase history, and speed of the vehicles. since there are more than two variables we would perform a multiple linear regression analysis.