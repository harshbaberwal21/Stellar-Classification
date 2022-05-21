# Stellar
Stellar Classification using SDSS17 Dataset
 
## Intention
Today, machine learning is widely used in scientific community, helping advance the systems and theories in place. The same pertains to machine learning in astronomy. In this project, I tried to predict the stellar object type by looking at the values of various filters (red, infrared, UV etc.) in the telescope photometric system.


## Files:


## Process Overview:

### EDA and Data Pre-Processing
- Visual and numerical
- Outlier treatment
- Data Range Constraints etc.

#### ![Target Classes Distibution](https://github.com/harshbaberwal21/Stellar-Classification/blob/d29dd2879b274ac51a61e7923aedce1ca60ed3cd/Class_Dist.png)

### Data Processing
- Feature Selection and Engineering
- Handling multi-collinearity using PCA

#### ![Selected features distribution](https://github.com/harshbaberwal21/Stellar-Classification/blob/d29dd2879b274ac51a61e7923aedce1ca60ed3cd/Features_BoxPlot.png)

### Modeling
##### Preliminary Model using 5 modeling techniques, out of which logistic regression and KNN classifier were taken forward.
- Target class encoding
- Class Balancing using SMOTE and random Undersampler
- Polynimial Features addition
- Building a pipeline object for a small preliminary grid search for optimal parameters.

### Evaluation
Using the model accuracy for cross-validation, training and testing sets. Also looked at idividual class F1 scores to assess the errors.

### Conclusion
Given the scope of this project I set out with, the model has fit nicely, neither too biased nor overfit. Although, to increase the model accuracy in future, adding new features might help.

### Citations
fedesoriano. (January 2022). Stellar Classification Dataset - SDSS17. Retrieved January 15th, 2022 from https://www.kaggle.com/fedesoriano/stellar-classification-dataset-sdss17.
