# DIABETES DISEASE PREDICTION USING RANDOM FOREST CLASSIFIER

## 1. PROJECT OVERVIEW

Diabetes Disease Prediction is a Machine Learning project developed to predict whether a person is likely to have diabetes based on selected health-related attributes.

The project uses the Random Forest Classification algorithm to analyze patient data and classify the diabetes outcome into two categories: Diabetic (1) and Non-Diabetic (0).

The main objective of this project is to demonstrate how machine learning techniques can be applied to healthcare-related data for predictive analysis and classification.

## 2. PROJECT OBJECTIVES

- To analyze patient health-related data.
- To perform data preprocessing and cleaning.
- To convert categorical data into numerical format.
- To train a Random Forest classification model.
- To predict diabetes outcomes using patient attributes.
- To evaluate model performance using standard classification metrics.
- To visualize dataset characteristics and model performance.

## 3. TECHNOLOGIES AND LIBRARIES USED

Programming Language:
- Python

Development Environment:
- Google Colab
- Jupyter Notebook

Python Libraries:
- Pandas – Data loading and manipulation.
- NumPy – Numerical computations.
- Matplotlib – Data visualization.
- Seaborn – Statistical visualization.
- Scikit-learn – Machine learning model development and evaluation.

## 4. DATASET DESCRIPTION

The project uses a diabetes dataset containing 500 patient records.

The dataset consists of the following attributes:

1. Patient_ID – Unique identification number for each patient.
2. Age – Age of the patient.
3. Gender – Gender of the patient.
4. BMI – Body Mass Index.
5. Glucose_Level – Glucose level of the patient.
6. Blood_Pressure – Blood pressure measurement.
7. Insulin – Insulin level.
8. Physical_Activity – Physical activity measurement.
9. Family_History – Indicates whether the patient has a family history of diabetes.
10. Diabetes_Outcome – Target variable indicating the diabetes prediction (0 or 1).

The Patient_ID column is removed during preprocessing because it is not required for prediction.

The remaining eight attributes are used as input features, and Diabetes_Outcome is used as the target variable.

## 5. DATA PREPROCESSING

The following preprocessing operations are performed:

- Loading the dataset using Pandas.
- Examining the dataset structure and data types.
- Checking for missing values.
- Checking for duplicate records.
- Converting categorical values into numerical representations.
- Removing the unnecessary Patient_ID column.
- Separating input features and target variables.

Categorical Encoding:
- Gender: Female = 0, Male = 1.
- Family_History: No = 0, Yes = 1.

## 6. MACHINE LEARNING ALGORITHM

### Random Forest Classifier

Random Forest is a supervised machine learning algorithm used for classification and regression tasks.

It works by creating multiple decision trees and combining their predictions to produce a final result.

In this project, the Random Forest Classifier is used to predict whether a patient belongs to the diabetic or non-diabetic category.

Model Configuration:
- Algorithm: Random Forest Classifier.
- Number of Estimators: 100.
- Training Data: 80%.
- Testing Data: 20%.

## 7. MODEL EVALUATION

The model performance is evaluated using the following metrics:

- Accuracy: Measures the overall correctness of predictions.
- Precision: Measures the proportion of positive predictions that are correct.
- Recall: Measures the proportion of actual positive cases correctly identified.
- F1-Score: Represents the harmonic mean of precision and recall.

Recorded Model Evaluation Results:

- Accuracy: 99.00%
- Precision: 98.18%
- Recall: 100.00%
- F1-Score: 99.08%

These are the evaluation results recorded in the project notebook.

## 8. DATA VISUALIZATIONS

The project includes the following visualizations:

1. Diabetes Outcome Distribution – Displays the distribution of diabetic and non-diabetic patients.
2. Correlation Heatmap – Shows the correlation between numerical features.
3. Random Forest Feature Importance – Identifies the relative importance of input features in the trained model.
4. ROC Curve – Evaluates the classification performance at different thresholds.
5. Actual vs Predicted Comparison – Compares actual outcomes with predicted outcomes.
6. Precision-Recall Curve – Illustrates the relationship between precision and recall.
7. Confusion Matrix – Displays correct and incorrect classification results.
8. Model Performance Graph – Compares the evaluation metrics of the model.

These visualizations help understand the dataset, model behavior, and prediction performance.

## 9. PROJECT FILE STRUCTURE

Disease-Prediction-Using-Random-Forest/

    |
    |-- Disease_Prediction_ML_Project_.ipynb
    |
    |-- diabetes_dataset.csv
    |
    |-- README.txt

### File Description

- Disease_Prediction_ML_Project_.ipynb: Contains the complete Python code, data preprocessing, model training, predictions, evaluation metrics, and visualizations.
- diabetes_dataset.csv: Contains the patient records used for model training and testing.
- README.txt: Provides project information, objectives, technologies, methodology, and execution instructions.

## 10. HOW TO RUN THE PROJECT

Step 1: Download the project notebook and dataset.

Step 2: Open Google Colab (https://colab.research.google.com/).

Step 3: Upload the Disease_Prediction_ML_Project_.ipynb notebook.

Step 4: Run the initial cell and upload diabetes_dataset.csv when prompted.

Step 5: Execute the notebook cells sequentially.

Step 6: Observe the data preprocessing results, model training, predictions, evaluation metrics, and visualizations.

## 11. EXPECTED OUTPUT

After executing the notebook, the project displays:

- Dataset information and preprocessing results.
- Training and testing dataset information.
- Random Forest model predictions.
- Model evaluation metrics.
- Confusion Matrix.
- Feature Importance Graph.
- Precision-Recall Curve.
- Actual vs Predicted Comparison.
  

## 12. CONCLUSION

The Diabetes Disease Prediction project demonstrates the application of supervised machine learning for healthcare-related classification.

The Random Forest Classifier is trained using patient health attributes to predict diabetes outcomes. The project also uses different evaluation metrics and visualizations to analyze the performance of the trained model.

This project provides practical experience in data preprocessing, machine learning model development, classification, performance evaluation, and data visualization using Python.

## 13. DISCLAIMER

This project is developed strictly for educational and academic purposes. The predictions generated by the model should not be considered medical advice or used as a substitute for professional medical diagnosis. The model has not been clinically validated.
