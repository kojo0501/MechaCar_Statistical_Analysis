# MechaCar

## Linear Regression
![image](https://user-images.githubusercontent.com/24308495/149039814-b80a560a-346e-4170-9f28-4b6570081927.png)

When evaluating factors that influece MPG, the Vehicle Length and Ground Clearance are both statistically signficant. They provide a non-random amount of variance.

The slope linear models are both very close to zero but they are not actually zero.

It can't be said that these variables are, alone, able to predict MPG. The linear model only indicates a correlation between MPG with Vehicle Length and Ground Clearance.

-
In your README, create a subheading, ## Linear Regression to Predict MPG, and write a short summary using a screenshot of the output from the linear regression, and address the following questions:

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Is the slope of the linear model considered to be zero? Why or why not?
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
-

## Summary Statistics
![image](https://user-images.githubusercontent.com/24308495/149040798-f18e9dbb-e2d7-49ee-afd4-947f618c20c3.png)

For all the lots in total, it appears they meet specifications. There is a PSI variance of ~62 which is less than 100.

![image](https://user-images.githubusercontent.com/24308495/149040609-ca16e9bf-2f00-48ac-968e-e3ecb440d6bc.png)

For each lot individually, Lot 3 does not meet the specification. There is a PSI variance of ~170 which exceeds 100.

-
The variance is too great in lot 3

In your README, create a subheading ## Summary Statistics on Suspension Coils, and write a short summary using screenshots from your total_summary and lot_summary dataframes, and address the following question:

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
-

## T-Tests on Suspension Coils
![image](https://user-images.githubusercontent.com/24308495/149041859-746845a6-e440-4fc0-afbf-ee1cfbfa5735.png)
For all lots combined, we must accept the alternative hypothesis becasue the p-value is ~0.602

![image](https://user-images.githubusercontent.com/24308495/149041077-d681c721-fd4c-4b5f-a4d2-a00f453f609e.png)
For Lot 1, we can accept the null hyptothesis. The mean of this lot matches the population mean of 1,500. 

![image](https://user-images.githubusercontent.com/24308495/149041270-3c9496ba-286a-4f2f-b966-fc1b6684c3d1.png)
For Lot 2, we must accept the alternative hypothesis because the p-value is ~0.607

![image](https://user-images.githubusercontent.com/24308495/149041661-26890f3a-394c-4cfd-ae92-f414499c7b71.png)
For Lot 3, we must accept the alternative hypothesis because the p-value is ~0.041

-
alternative hypothesis for all three?

In your README, create a subheading ## T-Tests on Suspension Coils, then briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
-

## Study Design: MechaCar vs Competition

Evaluation of cost could be done by using ANOVA to compare the brand new MechaCars vs other new vehicles on the market. The null hypothesis would be valid for vehicles that cost the same, whereas the alternative hyptothesis would be valid for cars with different costs. The reason I would use ANOVA is because I would be comparing the MechaCar versus numerous other cars; the number of different vehicle costs being tested is why I wouldn't use a one-sample or two-sample t-test. To run this test, the data required would be the average selling cost of a new MechaCar and the average selling cost of all other vehicles that compete in the same market.

-
Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
What metric or metrics are you going to test?
What is the null hypothesis or alternative hypothesis?
What statistical test would you use to test the hypothesis? And why?
What data is needed to run the statistical test?
-
