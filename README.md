# Water Potability Classification Analysis

This repository contains a comprehensive comparative analysis of water potability classification, encompassing various stages from Exploratory Data Analysis (EDA) to experimentation with machine learning and deep learning algorithms. The analysis follows a structured approach:

## 1. Exploratory Data Analysis (EDA)
In this section, I conduct a thorough analysis to understand some key caracteristics of the data including
- Examining the distribution related to water quality and potability.
- Visualizing class and features distribution together with  features boxplots to idendify the potential class imabalance, outliers existance and choose the appropriate metric to tackle the modeling approach.
- Visualizing features inter-correleation and removing highly correlated values

## 2. Data Cleaning
- Handling address missing values, outliers, and fixing data inconsistency ,
- Preprocessed the dataset and split it to prepare it for model training and evaluation.

## 3. Experimentation with Classification Algorithms
The repository includes experimentation with three different classification algorithms:

### c. LASSO
- Employed LASSO (Least Absolute Shrinkage and Selection Operator) regression for classification and most importantly for feature selection (zeroing out features coefficients)
- Utilized regularization to remove the features that don't contribute modeling process. This helps reduce the noise while training, reduce the footprint on memory usuage and faster more accurate convergence.
- 
- ![image](https://github.com/00VALAK00/Water-potabitity/assets/117487025/fd743bf1-d4ad-4c25-b5bf-c4f8c5c65f0b)

 
### b. XGBoost
- Utilized XGBoost, a gradient boosting algorithm, for classification tasks.
- Conducted parameter tuning and optimization to enhance model effectiveness.
- Assessed model performance using appropriate evaluation metrics.

### a. Convolutional Neural Networks (CNNs)
- Implemented CNN models for water potability classification.
- Tuned hyperparameters and architecture to improve model performance.
- Evaluated model accuracy, precision, recall, and F1 score.
- 
- ![image](https://github.com/00VALAK00/Water-potabitity/assets/117487025/cf2f74e4-fb6c-40d5-9f5e-70323c076b05)




## Conclusion
The winner algorithm of this analysis is 1d-CNNs scooring an f1-score of nearly 95% on both validation and training. So powerfull indeed even class imbalance did not stop it. This analysis showcases that cleaning your data well and removing the noise present within the data is crucial and will help your model generalize well.
