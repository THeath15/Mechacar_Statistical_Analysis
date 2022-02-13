# Metachar_Statistical_Analysis

AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on data analytics team to review the production data for insights that may help the manufacturing team.

# Objective:
1. Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
2. Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
3. Run t-tests to determine if the manufacturing lots are statistically different from the mean population
4. Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

# Deliverable 1 :Linear Regression to Predict MPG - Written Summary:

To get the the linear regression, R Script was applied to get ![Linear Regression Summary](https://user-images.githubusercontent.com/92903447/153779638-499405a2-0a07-459c-87a5-18c09004776e.png)
coefficients below as shown o below screenshot.  



  1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
    The 2 statiscally significant variables and coefficient result showing 0 < .05 are **vehicle length**: 0 < .05 and **ground clearance** variables which  represent non-random amounts of variance as applied to the mpg values.
    
    Coefficients for  vehicle weight, spoiler angle, AWD are not statistically significant, and has random amout of variance 

  2. Is the slope of the linear model considered to be zero? Why or why not?
    All of the slopes of the variables are shown to be non-zero even though some are close to zero
 
  3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  Even though the datasets R-squared shows a strong correlationn o .71 There could be other variables not included in the dataset contributing to the variation in the mpg.


# Deliverable 2 :Summary Statistics on Suspension Coils - Written Summary:

The suspension coil’s PSI continuous variable across all manufacturing lots
The following PSI metrics for each lot: mean, median, variance, and standard deviation.

# Deliverable 3 :T-Tests on Suspension Coils  - Written Summary:

# Deliverable 4 :Study Comparing the MechaCar to the Competition
