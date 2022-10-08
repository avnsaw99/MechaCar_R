# MechaCar_R

# Objective

Using R Script and R Studio to derive summary statitcs and perform t-tests to analyze the performance of AutosRUs' MechaCar, since AutosRUs has been having production issues

# Results

## Multiple Linear Regression Model for predicting MPG (Miles Per Gallon)



<img width="924" alt="MechaCar Summary Stats" src="https://user-images.githubusercontent.com/15044088/194679778-7c9a636f-1a1a-4820-afbc-c5b1b4e096d9.png">

## Summary Statics on Suspension Coils

<img width="885" alt="Total Summary Stats" src="https://user-images.githubusercontent.com/15044088/194679818-c5b9f7de-8342-4763-8a9c-9d05cbf1910b.png">

<img width="1185" alt="Lot Summary Stats" src="https://user-images.githubusercontent.com/15044088/194679823-b8ceebd1-dea5-4093-919b-65aac3370564.png">

## Study Design: MechaCar vs Competition

Assuming I could be an end consumer of a car, what are the factors other than MPG I would be looking for in a car:

I guess factors such as how many seconds does the car go 0-60 mph, the horsepower, whether it has applecarplay or not, autonomous driving, max speed of the car, safety features, etc. However one thing that can be evaluated further in my opinion can be how fast a car can go from 0-60 mph

### What metric or metrics are you going to test?
The two metrics are simple:
  * MechaCar's time for going 0-60 mph
  * Direct competitors of the MechaCar's time for going 0-60 mph
  
### What is the null hypothesis or alternative hypothesis?
H0: MechaCar prototypes' average time for going 0-60 mph is similar to the direct competitors vehicles Ha: MechaCar prototypes' average time to go 0-60 mph is statistically above or below that of the direct competitors vehicles.

### What statistical test would you use to test the hypothesis? And why?
Two-sample t-test would be the best to test this hypothesis, since if our null hypothesis is proven to be false we can establish that there is a statistically significant difference here that must be analyzed, and therefore could help AutosRUs to know that they should then move forward and see if their car is faster or not then the direct competition.

### What data is needed to run the statistical test?
We would need to take the vehicles and clock the time the car touches 60 mph to help with the analysis and to be able to run a statitical test
