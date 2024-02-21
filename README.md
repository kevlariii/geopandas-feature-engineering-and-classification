# Classification of Six Construction Projects Using Geographic Data

# Overview

This repository documents the classification of six construction projects using geographic data. The project was undertaken as part of a Kaggle competition organized by CentraleSupélec. Unfortunately, due to confidentiality reasons, the dataset cannot be uploaded to GitHub.

# Feature Engineering

The dataset primarily comprises raw geographical coordinates and statistics such as the mean and standard deviation of the RGB channels of images captured by satellites. To enhance model performance, extensive feature engineering was conducted. This involved deriving additional features such as area, perimeter, shape, and project advancement. Principal Component Analysis (PCA) was employed to effectively reduce the dimensionality of the feature space.

# Packages Used

The following packages were utilized in the implementation:
* **GeoPandas:** Utilized for working with geospatial data.
* **Pandas:** Employed for data manipulation and analysis.
* **Scikit-learn:** Utilized for machine learning tasks, including feature engineering and model building.
* **Plotly Express:** Used for creating interactive visualizations.

# Metric

The competition employed the F1 score as the evaluation metric due to label imbalance. For further details and visualizations regarding the dataset and metric selection, please refer to the notebook.

# Results

The model achieved a score of 0.89391 on the test set, securing a fourth-place position in the competition.

# Note

Feel free to explore the notebook for more detailed insights into the data preprocessing, feature engineering, model building, and evaluation.
