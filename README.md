# Credit Risk Analysis

## Overview of the analysis

The purpose of this analysis was to use different machine learning models to predict credit card risk. This challenge was created to determine if any of these machine learning models is useful for determining credit card risk.

## Results

### Naive Random Oversampling
![image1](Resources/noversampling1.png)
![image2](Resources/noversampling2.png)

### SMOTE Oversampling
![image3](Resources/smote1.png)
![image4](Resources/smote2.png)

### Undersampling
![image5](Resources/undersampling1.png)
![image6](Resources/undersampling2.png)

### Combination (Over and Under) Sampling
![image7](Resources/combo1.png)
![image8](Resources/combo2.png)

### Balanced Random Forest Classifier
![image9](Resources/forest1.png)
![image10](Resources/forest2.png)

### Easy Ensemble AdaBoost Classifier
![image11](Resources/easy1.png)
![image12](Resources/easy2.png)


## Summary

After exploring the data for the six models used in this analysis, the Easy Ensemble AdaBoost Classifier model had the most accurate results. If determining a model to use for this analysis, I would go with this one (although generally, there may be more accurate models to use, and the errors that could be created with the use of this one may be too large and risky for the best kind of analysis). It showed a 93.16% accuracy rate and a 9% precision rate for high risk credit cards, along with a recall score of 94% and an f1 score of 16%. Of all models, these were the highest stats recorded. Specific to accuracy, this model was over 10% more accurate than all others. 
