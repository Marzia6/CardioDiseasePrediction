# Cardio Disease Prediction

This project predicts cardiovascular disease using machine learning classification models.

## Dataset
- Features: Age, height, weight, blood pressure, cholesterol, glucose, etc.
- Target: `cardio` (0 = no disease, 1 = disease)

## Data Processing
- Removed missing values.
- Converted categorical features (`cholesterol`, `gluc`) to numeric.
- Converted age from days to years.
- Scaled numeric features using StandardScaler.

## Models Used
- Logistic Regression
- Gaussian Naive Bayes
- Random Forest
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- Confusion Matrix

## Usage
1. Install required libraries:  
   `pip install pandas numpy scikit-learn matplotlib seaborn statsmodels`  
2. Place dataset CSV file in project folder.  
3. Run the Python script or Jupyter notebook.
