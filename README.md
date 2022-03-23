# Stellar
Stellar Classification using SDSS17 Dataset
 
Today, machine learning is widely used in scientific community, helping advance the systems and theories in place. The same pertains to machine learning in astronomy. In this project, I tried to predict the stellar object type by looking at the values of various filters (red, infrared, UV etc.) in the photometric system.

## Process Overview:
### EDA
- Visual EDA
- Univariate Statistical Analysis
- Multivariate statistical analysis

### Data Processing
- Data Cleaning
- Feature Selection

### Modeling
##### Preliminary Model using 5 modeling techniques, out of which moved forward to logistic regression and gradient boosting classifier.
- Target class labeling
- Class Balancing using SMOTE and random Undersampler
- Polynimial Features addition
- Building a pipeline object for a small preliminary grid search for optimal parameters.

### Evaluation
Using the model accuracy for cross-validation, training and testing sets. Also looked at idividual class F1 scores to assess the errors.

### Final Model
Reached an accuracy of 97.4% with a very simple model (the evaluation metrics were all very close to ascertain no overfitting)

### Conclusion
The error mainly persisits around QSOs, whcih has the least F1 score out of the 3 classes. Currently the model is slightly biased but could be improved with the addition of new informative features.

### Citations
fedesoriano. (January 2022). Stellar Classification Dataset - SDSS17. Retrieved January 15th, 2022 from https://www.kaggle.com/fedesoriano/stellar-classification-dataset-sdss17.
