# Diabetes Prediction Using Machine Learning

##  Project Overview

This project uses machine learning to predict the presence of diabetes based on patient health data. It focuses on data preprocessing, exploratory data analysis (EDA), and developing an Artificial Neural Network (ANN) model to classify patients as diabetic or non-diabetic. The project also addresses class imbalance and evaluates the model using several performance metrics.

##  Objectives

- Analyze and understand the diabetes prediction dataset.
- Perform data cleaning and preprocessing.
- Explore relationships between patient characteristics and diabetes.
- Identify important features related to diabetes prediction.
- Develop an Artificial Neural Network (ANN) model.
- Address class imbalance using class weights.
- Evaluate model performance using different evaluation metrics.
- Visualize training performance and prediction results.

##  Technologies Used

- **Python** – Main programming language
- **Pandas & NumPy** – Data manipulation and numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Data preprocessing, class weighting, and model evaluation
- **TensorFlow & Keras** – Artificial Neural Network development and training
- **Jupyter Notebook** – Development and experimentation

##  Machine Learning Model

This project uses an Artificial Neural Network (ANN) for binary classification.

The model includes:

- **Input Layer** – Receives eight patient health features.
- **Hidden Layer 1** – 64 neurons with ReLU activation.
- **Hidden Layer 2** – 32 neurons with ReLU activation.
- **Batch Normalization** – Helps stabilize training.
- **Dropout** – Reduces overfitting.
- **Output Layer** – One neuron with sigmoid activation to predict diabetes probability.

The model uses the Adam optimizer and binary cross-entropy loss function. Class weights are applied to address the imbalance between diabetic and non-diabetic cases. Early stopping and learning rate reduction are also used during training.

##  Project Workflow

1. Load and inspect the diabetes prediction dataset.
2. Perform exploratory data analysis (EDA).
3. Check for missing values and duplicate records.
4. Remove duplicate records and handle selected categorical values.
5. Consolidate smoking history categories.
6. Detect and cap BMI outliers using the Interquartile Range (IQR) method.
7. Encode categorical features and scale numerical features.
8. Split the dataset into training, validation, and testing sets (70%, 15%, and 15%).
9. Train the ANN model using TensorFlow and Keras.
10. Apply class weights to address class imbalance.
11. Monitor training performance using early stopping and learning rate reduction.
12. Evaluate the model using accuracy, precision, recall, F1-score, and ROC-AUC.
13. Visualize training curves and the confusion matrix.

##  Project Structure

```text
Diabetes-Prediction-Using-Machine-Learning/
├── diabetes_prediction_dataset.csv
├── diabetes_preprocessing_eda.ipynb
├── model_training_2.ipynb
├── requirements.txt
├── X_train.csv
├── X_val.csv
├── X_test.csv
├── y_train.csv
├── y_val.csv
└── y_test.csv
```


