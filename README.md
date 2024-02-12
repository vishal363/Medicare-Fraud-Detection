# Medicare Fraud Detection Project

## Overview
This project aims to detect potential Medicare fraud using data analytics and machine learning models. By analyzing Medicare Part D Prescribers data alongside payment and LEIE exclusion data, we engineer features, scale data, and implement various classifiers to identify suspicious activities.

## Data Sources
- Medicare Part D Prescribers
- Payment Transactions
- LEIE (List of Excluded Individuals/Entities)

## Technologies Used
- Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Apache Spark: PySpark for large-scale data processing
- Jupyter Notebook: For interactive data analysis and visualization

## Features
- Data preprocessing with Spark, including cleaning and type conversion
- Feature engineering by aggregating cost, claims, and day supply data
- Data scaling with logarithmic transformations for model readiness
- Model evaluation using metrics like precision, recall, F1 score, and AUC

## Models Implemented
- Logistic Regression
- Gaussian Naive Bayes
- Random Forest Classifier
- Extra Trees Classifier
- Gradient Boosting Classifier

## Model Evaluation and Visualization
- Receiver Operating Characteristic (ROC) curve for model performance
- Feature importance analysis to understand predictive factors
- Confusion matrix heatmap to assess model classification accuracy

## Visualization
- Bar charts for top specialties by fraud count
- Heatmaps to visualize model confusion matrices

## How to Use
1. Clone the repository.
2. Ensure all dependencies are installed.
3. Run the Jupyter Notebook to process the datasets and train models.


