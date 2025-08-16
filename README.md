This project involves analyzing a spatial dataset, performing feature engineering, and applying multiple machine learning algorithms to classify outcomes. The workflow includes data cleaning, exploratory data analysis (EDA), visualization, model training, and evaluation.



🛠️ Steps Performed

1.Cleaned and preprocessed dataset (dropped unnecessary columns, handled missing values).
2.Extracted geospatial features (area and other parameters) from the_geom using WKT and GeoPandas.
3.Performed Exploratory Data Analysis (EDA): correlation heatmap, feature distributions, and other visualizations.
4.Selected top features based on correlation and feature importance.
5.Split dataset into training and testing sets.
6.Applied multiple ML models:
Logistic Regression
Random Forest Classifier
Gradient Boosting
XGBoost Classifier
7.Evaluated models using accuracy, recall, precision, F1-score, and cross-validation.
8.Found Random Forest Classifier performed best (accuracy = 1.0) while Logistic Regression performed poorly.
9.Extracted feature importance from Random Forest.




📊 Results

Best Model: Random Forest Classifier (Accuracy: 1.0).
Top Features: Identified from both correlation analysis and Random Forest importance.
Visualized relationships between features and target using plots.




🧰 Tech Stack
Python
Pandas, NumPy for data processing
Matplotlib, Seaborn for visualization
GeoPandas, Shapely for geospatial processing
Scikit-learn for ML models & evaluation
XGBoost and Gradient Boosting for advanced models
