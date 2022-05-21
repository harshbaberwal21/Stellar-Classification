# Stellar
Stellar Classification using SDSS17 Dataset
 
Today, machine learning is widely used in scientific community, helping advance the systems and theories in place. The same pertains to machine learning in astronomy. In this project, I tried to predict the stellar object type by looking at the values of various filters (red, infrared, UV etc.) in the telescope photometric system.

## Process Overview:

### EDA and Data Pre-Processing
- Visual and numerical
- Outlier treatment
- Data Range Constraints etc.

### Data Processing
- Feature Selection and Engineering
- Handling multi-collinearity using PCA

### Modeling
##### Preliminary Model using 5 modeling techniques, out of which logistic regression and KNN classifier were taken forward.
- Target class encoding
- Class Balancing using SMOTE and random Undersampler
- Polynimial Features addition
- Building a pipeline object for a small preliminary grid search for optimal parameters.

### Evaluation
Using the model accuracy for cross-validation, training and testing sets. Also looked at idividual class F1 scores to assess the errors.

### Conclusion
Currently the model is neither too biased nor overfit but in future work to increase the model accuracy, adding new features might help.

### Citations
fedesoriano. (January 2022). Stellar Classification Dataset - SDSS17. Retrieved January 15th, 2022 from https://www.kaggle.com/fedesoriano/stellar-classification-dataset-sdss17.
