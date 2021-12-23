# Credit_Risk_Analysis
## Overview
This project includes using machine learning techniques to determine credit card risk. This will be done with Python using imbalanced-learn and scikit-learn libraries. Techniques employeed will be RandomOverSampler, SMOTE, ClusterCentriods, SMOTEEN, BalancedRandomForestClassifier and EasyEnsembleClassifier. The six machine learning models will be compared to create a recommendation for which model would be best to use for this analytic need. 

## Results

### RandomOverSampler
* ![image](https://user-images.githubusercontent.com/89048287/147279090-edfaddde-a03d-4062-8167-1c9247127f18.png)
* Balanced Accuracy Score: .642
* This model has a precision score of .99 and a sensitivity score of .58. This is combined into an F1 score of .73. Overall, this could be a relatively successful model. 

### SMOTE
* ![image](https://user-images.githubusercontent.com/89048287/147280817-26b731e0-c80b-46e0-8f04-8faeab14a581.png)
* Balanced Accuracy Score:.657 
* This model has a precision score of .99 and a sensitivity score of .67. The F1 score of .80 which suggests that this is a good fit for the data. 

### ClusterCentroids
* ![image](https://user-images.githubusercontent.com/89048287/147279128-2f0bec14-365b-4b9b-96e7-6033b9929a97.png)
* Balanced Accuracy Score: .544
* This model has a precision score of .99 and a sensitivity score of .41. The F1 score of .57 suggests that this is not a good choice for the data. 

### SMOTEEN
* ![image](https://user-images.githubusercontent.com/89048287/147279160-b7a3f7be-079c-4fa7-94b5-624c6cbf3d13.png)
* Balanced Accuracy Score: .544

### BalancedRandomForestClassifier
* ![image](https://user-images.githubusercontent.com/89048287/147279238-08dcea75-b3d2-473f-a772-9c8ebdd9be5e.png)
* ![image](https://user-images.githubusercontent.com/89048287/147279274-9928283c-b7cf-4b04-a9bc-9c3ba4563710.png)
* Balanced Accuracy Score: .712

### EasyEnsembleClassifier
* ![image](https://user-images.githubusercontent.com/89048287/147279320-faa182f2-3fcc-41c7-ab8b-f9cb86020c66.png)
* Balanced Accuracy Score: .723
## Summary 
