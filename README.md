# MechaCar_Statistical-Analysis

## Project Overview

The purpose of this project is to use statistics and hypothesis testing to review the production data in the automotive industry to give insights that can help AutosRUs with the manufacturing team with its production troubles with their newest protoype, the MechaCar.

## Linear Regression to Predict MPG

1. Based on the Pr, the vehicle length and vehicle ground clerance are statistically likely to provide non-random amounts of variance to the model.  

2. The p-Value for this model, p-Value: 5.35e-11, is much smaller than the assumed significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis, which further indcates that the slope of this linear model is not zero.

3. This linear model has an r-squared value of 0.7149, which means that approximately 71% of all mpg predictions will be determined by this model. Relatively speaking, this multiple regression model does predict mpg of MechaCar prototypes effectively.

## Summary Statistics on suspension Coils


![image](https://user-images.githubusercontent.com/78937719/122661580-79be4180-d151-11eb-8509-f99f19ffcd7b.png)


![image](https://user-images.githubusercontent.com/78937719/122661576-6dd27f80-d151-11eb-9599-22ccaf427978.png)

- When looking at the entire population of the production lot, the variance of the coils is 62.29 PSI, which is well within the 100 PSI variant requirement.  

- Lots 1 and 2 are significantly more consistent and well within the 100 PSI variance requirement with variances of .98 and 7.47 respectively 

- Lot 3 shows a much larger variance in performance and consistency with a variance of 170.29 PSI which is well outside the requirement of 100 PSI

## t-Tests on Suspension Coils

### Summary of t-Tests Across All Manufacturing Lots

![image](https://user-images.githubusercontent.com/78937719/122661841-21d50a00-d154-11eb-895d-af535695cf84.png)

- true mean of the sample is 1498.78 and p-Value is 0.06, which is higher than the common significance level of 0.05 so there is not enough evidence to support rejecting the null hypothesis.

### Summary of Lot 1
![image](https://user-images.githubusercontent.com/78937719/122661844-2d283580-d154-11eb-8b1d-c710c2f454ee.png)
- the Lot 1 sample has the true sample mean of 1500 with a p-Value of 6.529e-07 so we cannot reject the null hypotehsis that there is no statistical difference between the observed sample mean and the presumed population mean.

### Summary of Lot 2
![image](https://user-images.githubusercontent.com/78937719/122661851-3a452480-d154-11eb-8884-859b072ac9e9.png)
- the Lot 2 sample has the true sample mean of 1499.52 with a p-Value of 0.117 so we cannot reject the null hypotehsis that there is no statistical difference between the observed sample mean and the presumed population mean.

### Summary of Lot 3
![image](https://user-images.githubusercontent.com/78937719/122661854-4335f600-d154-11eb-91b6-87c34f7e898f.png)
- the Lot 3 sample has the true sample mean of 1496.92 with a p-Value of 0.5859 so we cannot reject the null hypotehsis that there is no statistical difference between the observed sample mean and the presumed population mean.

## Study Design: MechaCar vs Competition

A statistical study that compares the performance of the MechaCar vehicles versus the performance of vehicles from other manufacturers would involve collecting data on MechaCar and its comparable models across several different manufacturers over the last 3 years.  Some of this Data would include:

- What are the competitions' comparable models, 
- Which cars will MechaCar be competing with head-to-head? which cars will be included in the study?
- Which factors will look at the study to determine the relevant to selling price?
 

#### Metrics
Collecting data for comparable models across all major manufacturers for past 3 years for the following metrics:

- Safety Feature Rating: **Independent Variable**
- Current Price (Selling): **Dependent Variable**
- Drive Package : **Independent Variable**
-  Engine (Electric, Hybrid, Gasoline / Conventional): **Independent Variable**
-  Resale Value: **Independent Variable**
-  Average Annual Cost of ownership (Maintenance): **Independent Variable**
-  MPG (Gasoline Efficiency): **Independent Variable**


#### Hypothesis: Null and Alternative
After determining which factors are key for the MechaCar's genre:

 - Null Hypothesis (Ho): MechaCar is priced correctly based on its performance of key factors for its genre.
 - Alternative Hypothesis (Ha): MechaCar is NOT priced correctly based on performance of key factors for its genre.
 
#### Statistical Tests
A **multiple linear regression** would be used to determine the factors that have the highest correlation/predictability with the list selling price (dependent variable); which combination has the greatest impact on price.
