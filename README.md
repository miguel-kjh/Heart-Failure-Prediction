# Heart Failure Prediction ❤️

This work consists of the analysis of different estimators for the detection of cardiac insufficiency.


## Machine Learning Models

- Logistic regression
- A Bayesian network
- KNN
- SVM with a radial kernel
- Decision tree
- Random forest
- AdaBoost
- XGBoost

## Deep Learning Model

- Neuronal Network
   - Optimizer: Adam
   - Loss: Binary Crossentropy

## Transformations

- Standard scaler
- L2 normalization

## Dimensionality Reduction

- PCA
- Sequential Feature Selector
- Select K Best using Chi-square
- Feature classification with recursive feature elimination (RFE)

## Data visualization algorithms

- t-SNE

## Data aumentations algorithms

- SMOTE

## Metrics

- Accuracy
- ROC curve
- AUC

## Best model

The best results were obtained with a Random Forest using the SMOTE algorithm for data augmentation and the model was trained through k-flod cross validation with k = 5

<p align="center"> 
   <img src="img/results.png" alt="Results"></img>
   <p align="center">Figure 1: Results of the experiment</p>
</p>

## Reference

* [Sklearn](https://scikit-learn.org/) 🧮
* [kaggle Dataset](https://www.kaggle.com/andrewmvd/heart-failure-clinical-data)
