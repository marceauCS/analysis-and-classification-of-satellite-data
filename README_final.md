# Multi-Class Classification on Geographical Polygons

## Overview

This project tackles a **multi-class classification** task on geographical data\
The dataset combines:\
- **Geometric features** (polygon shapes)\
- **Categorical variables** (zone types, associated classes)\
- **Temporal information** (observation dates)\
- **Neighborhood descriptors** (spatial relationships between polygons)

The goal is to predict the correct class for each polygon by following a complete machine learning workflow.

------------------------------------------------------------------------

## Workflow

### 1. **Data Preprocessing**

-   Cleaned and converted categorical variables into numerical representations.\
-   Extracted usable geometric descriptors from polygons (area, perimeter).

### 2. **Feature Engineering**

-   Created new features such as:
    -   Polygon area and perimeter\
    -   One-hot encoding for categorical variables\
    -   Time intervals between observations

### 3. **Modeling**

-   Final model: **XGBoost Classifier**
    -   Hyperparameters were manually fine-tuned\
-   Other models tested:
    -   **SVM**\
    -   **Random Forest**\
    -   **Logistic Regression**\
    -   Performance comparison was performed to select the final model

### 4. **Evaluation**

-   Evaluated models using appropriate multi-class metrics:
    -   **F1-score (macro and micro)**\
    -   **Accuracy**\
    -   **Confusion Matrix**\
-   Final model achieved a **mean F1-score ~ 0.87** on the test dataset submitted for ranking

------------------------------------------------------------------------

## Competition Result

-   Participated in a Kaggle competition (see https://www.kaggle.com/competitions/2el1730-machine-learning-project-january-2024/leaderboard "marceau" on the leaderboard).\
-   Achieved a **middle-of-the-leaderboard ranking** with a mean
    F1-score of **≈ 0.87**.\
-   For reference:
    -   **Top scores:** ≈ 0.90\
    -   **Lowest scores:** ≈ 0.79

------------------------------------------------------------------------

## Tech Stack

-   **Python** (pandas, numpy, shapely, geopandas)\
-   **Machine Learning**: scikit-learn, XGBoost\
-   **Visualization**: matplotlib, seaborn\
-   **Geometric data handling**: shapely, geopandas