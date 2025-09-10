# Notebook Overview
This notebook addresses a multi-class classification task on geographical data represented as irregular polygons with categorical, temporal, and neighborhood features. The workflow follows a standard ML pipeline:

## Preprocessing
Cleaning and converting categorical and polygon-based data into usable numerical representations.

## Feature Engineering
Creating new features such as polygon area/perimeter, one-hot encoding of categorical values, neighborhood descriptors, and time intervals between observation dates. Dimensionality reduction and feature selection are also explored.

## Modeling
Starting from a k-NN baseline (~40% accuracy), several classification algorithms are tested (e.g., logistic regression, SVM, decision trees, neural networks), including the potential use of ensemble methods.

## Evaluation
Models are assessed with appropriate multi-class metrics to compare performance and generalization ability.

