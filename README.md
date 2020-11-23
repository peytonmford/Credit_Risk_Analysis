# Credit Risk Analysis
## Overview
The purpose of this analysis is to see if we can get the most accurate credit risk analysis. Using machine learning, we tried creating the most accurate and precise credit card risk analysis.
## Results
The results of this analysis is concusive. We have the following analyses:
- Naive Sampling
- SMOTE Over Sampling
- Undersampling
- SMOTEENN Sampling
- Balanced Random Forest Sampling
- Easy Ensemble Sampling

### Naive Sampling
The precision of the sampling of the high risk is a 0.01, meaning that it didn't caught almost all of the high risk credit. The low risk is at a 1 meaning that the precision of the low risk is greater. The sensitivity for the high risk is a 0.54 and a 0.67 for the low risk. This means that when actually running the test, how likely is it that they would have low or high risk.
![NaiveSampling](Resources/NaiveSampling.png)

### SMOTE Over Sampling
The precision is similar to the Naive sampling, with the same precision values. The sensitivity of the the SMOTE over sampling for the high risk is a 0.55 and for the low risk is a 0.69.
![SMOTE](Resources/SMOTE.png)

### Undersampling
The precision values are the same again, with the 0.01 with the high risk and the 1.00 for the low risk. The sensitivity for the undersampling for the high risk is a 0.56 and for the low risk is a 0.48.
![Undersampling](Resources/Undersampling.png)

### SMOTEENN Sampling
Once again, the precision is the same with the 0.01 for the high risk and 1.00 for the low risk. The sensitivity for the SMOTEENN sampling for the high risk is a 0.73 and for the low risk is a 0.55.
![SMOTEENN](Resources/SMOTEENN.png)

### Balanced Random Forest Sampling
The precision for the balanced random forest sampling is slightly different with a 0.02 for the high risk and a 1.00 for the low risk. The sensitivity for the balanced for the high risk is a 0.62 and for the low risk is a 0.88.
![Balanced](Resources/Balanced.png)

### Easy Ensemble Sampling
The precision for the balanced random forest sampling is slightly different with a 0.03 for the high risk and a 1.00 for the low risk. The sensitivity for the easy ensemble for the high risk is a 0.76 and for the low risk is a 0.89.
![EasyEnsemable](Resources/EasyEnsemable.png)
## Summary
My recommendation of using these, is that they are not the most accurate of testing. Some of them have higher accuracy and precision, but they still have okay percentages. 
