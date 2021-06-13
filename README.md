# MechaCar_Statistical_Analysis

## Overview 
 Upper management had approached Jeremy about a special project. The Manufacturing Team of AutosRUs' newest prototype, the MechaCar, was experiencing production problems. Upper management at AutosRUs had asked Jeremy and his team to review the production data and find insights that will aid the manufacturing team.

In this challenge, we helped Jeremy and the data analytics team do the following:

- Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
- Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
- Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
- Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.


## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/78935551/121794826-6eab6480-cbd9-11eb-92fb-52e5a9d52755.png)

- In this study, the spoiler_weight, vehicle_angle, and AWD all contributed to non-random variances. In terms of random variance, two variables are most significant: ground_clearance and vehicle_length.

- By looking at the p-value, which is less than 0.05, we can tell that our slope is not zero.

- As measured by the R-square of 0.71, 71% of mpg variations can be attributed to variations in the vehicle length, vehicle weight, the spoiler angle, the drivetrain, and the ground clearance. This linear model is capable of predicting the mpg of MechaCar prototypes fairly well.


## Summary Statistics on Suspension Coils

### Total Summary 

![image](https://user-images.githubusercontent.com/78935551/121795097-6bb17380-cbdb-11eb-8aa3-b873a1ce0590.png)

### Lot Summary 
![image](https://user-images.githubusercontent.com/78935551/121795111-7f5cda00-cbdb-11eb-9718-b110740cf848.png)

- MechaCar's suspension coils are designed to have a variance of no more than 100 pounds per square inch.The design specs are respected across all manufacturing lots with a global variance of 62.3 psi.Lot 1 and Lot 2 are in specs with respectively a variance of 0.98 and 7.5 psi. With a variance of 170.3 psi, Lot 3 is out of specs.


## T-Tests on Suspension Coils

### All Lot Summary
![image](https://user-images.githubusercontent.com/78935551/121795525-a9180000-cbdf-11eb-832c-c3ee97ee0890.png)

- Using the common significance level of 0.05 percent, our p-value of 0.45 is above the significance level. Due to the lack of sufficient evidence to reject the null hypothesis, we can conclude that the PSI across all manufacturing lots is statistically similar to the population mean.


### Lot 1
![image](https://user-images.githubusercontent.com/78935551/121795472-4a528680-cbdf-11eb-965e-3a038fe6e0c0.png)

- We reject the null hypothesis here since p-value falls below the significance threshold of 0.05 percent. The PSI for Lot 1 therefore differs from that of the population.



### Lot 2
![image](https://user-images.githubusercontent.com/78935551/121795539-c64cce80-cbdf-11eb-9f11-ee588c471952.png)


### Lot 3 
![image](https://user-images.githubusercontent.com/78935551/121795543-d2389080-cbdf-11eb-9268-106fbc77f040.png)








