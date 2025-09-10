# Notebook Overview
This notebook addresses a multi-class classification task on geographical data represented as irregular polygons with categorical, temporal, and neighborhood features. The workflow follows a standard ML pipeline:

## Preprocessing
Cleaning and converting categorical and polygon-based data into usable numerical representations.

## Feature Engineering
Creating new features such as polygon area/perimeter, one-hot encoding of categorical values, neighborhood descriptors, and time intervals between observation dates

## Modeling
The final algorithm chosen is a XGBoost Classifier. It has been finetuned manually. Other models have been tested such as SVM, random forest, logistic regressions.

## Evaluation
Models are assessed with appropriate multi-class metrics to compare performance and generalization ability.


