# Metachar_Statistical_Analysis

AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on data analytics team to review the production data for insights that may help the manufacturing team.

# Objective:
1. Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
2. Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
3. Run t-tests to determine if the manufacturing lots are statistically different from the mean population
4. Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

# Deliverable 1 :Linear Regression to Predict MPG - Written Summary:

To get the the linear regression, R Script was applied to get coefficients below as shown per  below screenshot.  
![Linear Regression Summary](https://user-images.githubusercontent.com/92903447/153779722-51e9d164-80ce-4d75-812e-2f57fb84729c.png)


  1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
    The 2 statiscally significant variables and coefficient result showing 0 < .05 are **vehicle length**: 0 < .05 and **ground clearance** variables which  represent non-random amounts of variance as applied to the mpg valuess. Coefficients for  vehicle weight, spoiler angle, AWD are not statistically significant, and has random amout of variance 

  2. Is the slope of the linear model considered to be zero? Why or why not?
    All of the slopes of the variables are shown to be non-zero even though some are close to zero
 
  3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  Even though the datasets R-squared shows a strong correlationn 0.71 There could be other variables not included in the dataset contributing to the variation in the mpg.


# Deliverable 2 :Summary Statistics on Suspension Coils - Written Summary:

**Below is the Table created from datasets read from Suspension_Coil.csv file**

![Suspension_Coil Dataframe](https://user-images.githubusercontent.com/92903447/154816760-0e0dcb14-45d8-4510-93ca-ebe4b5e4bbbb.png)


**PSI metrics for each lot: mean, median, variance, and standard deviation**

**Below low table shows the summary statistics of all of the manufacturing lots**

![Total_summary(suspension_coil](https://user-images.githubusercontent.com/92903447/154816758-de3c35a5-d5f6-445b-89c1-a10f852a3adc.png)


Below table shows the shows the summary of summary Suspension coils by manufacturing lot number.
The means of the lot number are similar to population mean.

![Lot_summary(suspension_coil)](https://user-images.githubusercontent.com/92903447/154816782-bef203ff-3f4d-419f-8fdd-cf51c93ac3af.png)

**The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**
The design specifications for the Mechacar should have a variance of suspension coils less than or equal to 100/sq inch.  Lot 1 and 2 shows  avariance of 1 and 7, which is at acceptable threshold while lot 3, shows over the acceptable threshold of 100, which is 170.28.


# Deliverable 3 :T-Tests on Suspension Coils  - Written Summary:

**T-test for all manufacturing lots**
Below T-test run for suspension coils for all manufacturing lot shows that they are not statistically different from popular mean and the means fails withing the 9
5 percent confidence interval. 
![Samplte t_test for all manufacturing lots](https://user-images.githubusercontent.com/92903447/154818640-5ea286b8-6a3b-4aeb-b659-3c84d47a9540.png)

**T-test for lot1**
 T-test for the suspension coils for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough (1) for us to reject the null hypothesis
![Lot1_t_test](https://user-images.githubusercontent.com/92903447/154818642-4a6e0d2d-b753-4429-b11d-03bdd7963f6d.png)

**T-test for lot2**
T-test for the suspension coils for Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough (0.6072) for us to reject the null hypothesis
![lot_2_t_test](https://user-images.githubusercontent.com/92903447/154818641-511b71cb-e572-41b5-bef5-d726be32f5d2.png)

**T-test for lot3**
T-test for the suspension coils for Lot 3 shows that they are slightly statistically different from the population mean, and the p-value is just low enough (0.0417) for us to reject the null hypothesis. This lot need to be evaluated further.
![lot3_t_test](https://user-images.githubusercontent.com/92903447/154818643-8d1500f4-edbc-4a58-98ff-634d236af8b2.png)


# Deliverable 4 :Study Comparing the MechaCar to the Competition
