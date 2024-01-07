
# Diabetes Prediction with Logistic Regression

## Business Problem:

Can you develop a machine learning model that predicts whether individuals have diabetes or not based on specified features?

## Dataset:

The dataset is a part of a large dataset kept at the National Institute of Diabetes and Digestive and Kidney Diseases in the United States. It involves a study on Pima Indian women aged 21 and above in Phoenix, Arizona, the 5th largest city in the state. The dataset comprises 768 observations and 8 numerical independent variables. The target variable, "Outcome," indicates whether the person has diabetes (1) or not (0).

### Variables:
- Pregnancies: Number of pregnancies
- Glucose: Glucose level
- BloodPressure: Blood pressure
- SkinThickness: Skin thickness
- Insulin: Insulin level
- BMI: Body mass index
- DiabetesPedigreeFunction: Probability of having diabetes based on family history
- Age: Age in years
- Outcome: Whether the person has diabetes (1) or not (0)

## Steps:

1. **Exploratory Data Analysis**
    - Analyze the distribution of the target variable.
    - Visualize the histograms of the features.

2. **Data Preprocessing**
    - Check for missing values.
    - Handle outliers using the interquartile range.
    - Scale the features using RobustScaler.

3. **Model & Prediction**
    - Train a Logistic Regression model.
    - Predict the outcome for the entire dataset.

4. **Model Evaluation**
    - Plot the confusion matrix.
    - Print classification report including accuracy, precision, recall, and F1-score.
    - Calculate and display the ROC AUC score.

5. **Model Validation: Holdout**
    - Split the data into training and testing sets.
    - Train a Logistic Regression model on the training set.
    - Evaluate the model on the testing set.
    - Display the ROC Curve and calculate AUC.

6. **Model Validation: 10-Fold Cross Validation**
    - Perform a 10-fold cross-validation on the entire dataset.
    - Calculate and display mean accuracy, precision, recall, F1-score, and ROC AUC.

7. **Prediction for a New Observation**
    - Select a random user from the dataset.
    - Predict whether the individual has diabetes or not.

## Libraries Used:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## How to Run the Code:

1. Ensure you have the required libraries installed using `pip install -r requirements.txt`.
2. Run the code in a Python environment.

Feel free to explore and enhance the code further based on your learning journey!
