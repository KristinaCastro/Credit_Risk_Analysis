# Credit_Risk_Analysis

## Overview of Analysis:
Credit risk is an inherently unbalanced classification problem, good loans easily outnumber risky loans. We are tasked with employing different techniques to train and evalute models with unbalanced classes. Using the imbalanced-learn and scikit-learn libraries, we'll build models using resampling and evalute the performance of each model in predicting client credit risk.

## Results of Analysis:

### Logistic Regression: Naive Random Oversampling
  - Balanced accuracy score: 0.65
  - Precision score:
      - high risk: 0.01
      - low risk: 1.00
  - Recall (sensitivity) score:
      - high risk: 0.66
      - low risk: 0.62 

<!-- <p float="left">
<img width="497" alt="Screen Shot 2021-08-22 at 1 43 16 AM" src="https://user-images.githubusercontent.com/81998045/130343912-aebe4c94-43b2-4212-adf0-b9b3f1f7c5ba.png"> 
<img width="496" alt="Screen Shot 2021-08-22 at 1 43 56 AM" src="https://user-images.githubusercontent.com/81998045/130343933-b59fd367-f840-43b8-bb54-c0086602a4cd.png">
</p>
 -->

Balanced accuracy score           |  Confusion matrix
:-------------------------:|:-------------------------:
![Screen Shot 2021-08-22 at 1 43 16 AM](https://user-images.githubusercontent.com/81998045/130343912-aebe4c94-43b2-4212-adf0-b9b3f1f7c5ba.png)  |  ![Screen Shot 2021-08-22 at 1 43 56 AM](https://user-images.githubusercontent.com/81998045/130343933-b59fd367-f840-43b8-bb54-c0086602a4cd.png)

<p align="center">
<img width="724" alt="Screen Shot 2021-08-22 at 2 10 48 AM" src="https://user-images.githubusercontent.com/81998045/130344504-b15aebb9-5c17-4929-b1c9-3e8f7ae9a136.png">
</p>

<!-- <p align="center">
  <img width="460" height="300" src="http://www.fillmurray.com/460/300">
</p>
 -->
 
 ### Logistic Regression: SMOTE Oversampling
 
 - Balanced accuracy score: 0.65
  - Precision score:
      - high risk: 0.01
      - low risk: 1.00
  - Recall (sensitivity) score:
      - high risk: 0.61
      - low risk: 0.69 

Balanced accuracy score           |  Confusion matrix
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/81998045/130345114-ae1c2c9f-76bd-402d-8edc-6034c68ab0ec.png)  |  ![](https://user-images.githubusercontent.com/81998045/130345131-5b92b0c1-c111-4630-9c84-88df54bb9648.png)
<p align="center">
<img width="750" alt="Screen Shot 2021-08-22 at 2 38 12 AM" src="https://user-images.githubusercontent.com/81998045/130345150-c19f2d00-cbf0-49d9-8e43-b9e5006592b4.png">
</p>

### Logistic Regression: Cluster Centroids Undersampling

- Balanced accuracy score: 0.54
 - Precision score:
      - high risk: 0.01
      - low risk: 1.00
 - Recall (sensitivity) score:
      - high risk: 0.69
      - low risk: 0.40 

Balanced accuracy score           |  Confusion matrix
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/81998045/130345356-9915ca4b-5d7e-454f-a4bd-ee79e3813dd7.png)  |  ![](https://user-images.githubusercontent.com/81998045/130345327-859ad931-8534-411e-8ff3-f6bd90609d5b.png)
<p align="center">
<img width="722" alt="Screen Shot 2021-08-22 at 2 46 02 AM" src="https://user-images.githubusercontent.com/81998045/130345390-9c718f85-3c98-4cf7-a53d-887694e8b8b6.png">
</p>

### Logistic Regression: SMOTEENN (Over and Under) Sampling

- Balanced accuracy score: 0.65
 - Precision score:
      - high risk: 0.01
      - low risk: 1.00
 - Recall (sensitivity) score:
      - high risk: 0.75
      - low risk: 0.56 

Balanced accuracy score           |  Confusion matrix
:-------------------------:|:-------------------------:
![](https://user-images.githubusercontent.com/81998045/130345540-cb357632-7e28-4585-bd23-289e1c9e44dd.png)  |  ![](https://user-images.githubusercontent.com/81998045/130345547-d9253461-f40d-4bb0-992e-a601cafc4caa.png)
<p align="center">
<img width="732" alt="Screen Shot 2021-08-22 at 2 52 26 AM" src="https://user-images.githubusercontent.com/81998045/130345565-abec5f12-6aed-49bd-9ab4-38aa3bd4528a.png">
</p>



