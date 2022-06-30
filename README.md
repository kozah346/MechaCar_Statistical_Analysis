# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

After running the relevant code to determine the linear regression to predict MPG, the screenshots below show the obtained results:

<img width="752" alt="Linear Regression to Predict MPG" src="https://user-images.githubusercontent.com/101376325/176708560-c3c02ac0-8ff7-4b71-91cc-1f8ca1da31cf.png">



<img width="637" alt="Linear Regression to Predict MPG2" src="https://user-images.githubusercontent.com/101376325/176708651-59775f21-9bd4-4240-906d-233df9732f4d.png">


From the illustration above, the following is noted:

 * Vehicle length and ground clearance most likely provide a non-random amount of variance to the mpg values in the dataset. This conclusion is reached by looking at the respective values of Pr(>|t|) which are less than 0.05.
 * Having a p-value that is less than 0.05, the slope of this linear model is not zero. This is because such a small p-value shows sufficient evident to reject the null hypothesis.
 * With a r-squared value of 0.71, and with background knowledge on a value greater than 0.7 being a good model, it can be concluded that this model does predict MechaCar prototypes quite effectively.