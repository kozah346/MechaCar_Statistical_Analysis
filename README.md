# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

After running the relevant code to determine the linear regression to predict MPG, the screenshots below show the obtained results:

<img width="752" alt="Linear Regression to Predict MPG" src="https://user-images.githubusercontent.com/101376325/176708560-c3c02ac0-8ff7-4b71-91cc-1f8ca1da31cf.png">



<img width="637" alt="Linear Regression to Predict MPG2" src="https://user-images.githubusercontent.com/101376325/176708651-59775f21-9bd4-4240-906d-233df9732f4d.png">


From the illustration above, the following is noted:

 * Vehicle length and ground clearance most likely provide a non-random amount of variance to the mpg values in the dataset. This conclusion is reached by looking at the respective values of Pr(>|t|) which are less than 0.05.
 * Having a p-value that is less than 0.05, the slope of this linear model is not zero. This is because such a small p-value shows sufficient evident to reject the null hypothesis.
 * With a r-squared value of 0.71, and with background knowledge on a value greater than 0.7 being a good model, it can be concluded that this model does predict MechaCar prototypes quite effectively.


## Summary Statistics on Suspension Coils

The following results are obtained after executing code to get the summary statistics on suspension coils:

<img width="670" alt="Total Summary" src="https://user-images.githubusercontent.com/101376325/176718460-3e3168dd-6921-4005-a1e0-965f07ec650b.png">

<img width="648" alt="Lot Summary" src="https://user-images.githubusercontent.com/101376325/176718525-69e5e767-eb61-4668-b253-31b8b4266203.png">

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The average from the 3 lots is 62.29 which lies within the required specifications. However, when viewed individually lot 3 has a staggering 170.29 while lot 1 and lot 2 has averages of 0.98 and 7.47 respectively which contributed in bringing down the mean to 62.29. Therefore, lot 1 and lot 2 meet the design specifications while lot 3 does not.

## T-Tests on Suspension Coils

After running code to find T-Tests on suspenstion coils, the following was observed:

<img width="645" alt="All Lots t test" src="https://user-images.githubusercontent.com/101376325/176725609-5c75dfdd-0085-4d75-96b5-6003da967a79.png">


<img width="590" alt="Individual t tests" src="https://user-images.githubusercontent.com/101376325/176725653-d9bbfc98-a5f1-4ce8-b040-d593dfa6e6f2.png">

From the above illustrations, the following is noted:

* For all the lots in MechaCar, with a p-value of which is 0.06 that is higher than 0.05, we fail to reject since there is not enough evidence to support rejecting the null hypothesis. 
* Lot 1 and lot 2 have a p-value of of 1 and 0.6 respectively which are higher than 0.05. As a result, we fail to reject since there is not enough evidence to support rejecting the null hypothesis. 
* Lot 3 has a p-value of 0.04 which is less than 0.05. This suggests that we can reject the null hypothesis because there is enough evidence to do so. 

## Study Design: MechaCar vs Competition

Another statistical design can be conducted to compare vehicle perfomance of the MechaCar vehicles against vehicles from other manufacturers. 

Points of interest that can be included in the study to make the findings important and effective are: 
  * Cost
  * City/highway fuel efficiency
  * Horse power
  * Maintainance cost
  * Safety rating

In this study design, the hypothesis can be as follows:

  * Null Hypothesis - MechaCar cars are underpriced.
  * Alternative Hypothesis - MechaCar cars are not underpriced.


After conducting a statistical analysis, a p-value of less than 0.05 is needed so the null hypothesis is rejected which will work in favor of MechaCar. The data needed in this test should contain all the metrics covered above. 
