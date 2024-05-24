# Heart Attack Predictor using Shiny App (R Programming)
###  Overview
This project aims to predict the likelihood of heart disease based on patient data using a logistic regression model. The prediction is based on several health parameters, and the app provides an easy-to-use interface for users to input data and get real-time predictions.

### Features
User-friendly Interface: Enter patient details through a straightforward sidebar.

Automated Model Training: The logistic regression model is pre-trained and ready to use.

Data Visualization: Visualize the distribution of the target variable and other summary statistics.

Interactive Predictions: Get immediate predictions based on the input data.

Comprehensive Evaluation:The app provides detailed metrics to evaluate model performance.


### Motivation
Heart disease is a leading cause of death globally. Early detection and intervention are crucial for improving patient outcomes and saving lives. This Shiny app aims to aid healthcare professionals and researchers by providing a tool to predict heart disease risk based on commonly available clinical data.

### Usage Instructions
#### Step 1: Load and Preprocess the Data
The app begins by loading the dataset heart.csv. It preprocesses the data by converting categorical variables into factors and normalizing the features for model training. This step ensures the data is in the correct format for the model to process.

#### Step 2: Data Visualization
The app provides various plots to visualize the data, including:
Distribution of the Target Variable:   Shows the frequency of patients with and without heart disease.
Age Distribution:                      Visualizes the age distribution of patients with and without heart disease.
Gender vs Heart Disease:               Illustrates the relationship between gender and heart disease incidence.

#### Step 3: Model Training
The logistic regression model is trained using the preprocessed data. The data is split into training and testing sets, normalized, and then the model is trained. This step includes:

Data Splitting: Divides the data into training and testing subsets.
Normalization: Ensures features are on a similar scale for better model performance.
Model Training: Fits the logistic regression model to the training data.

#### Step 4: Model Evaluation
The app evaluates the model using various metrics such as accuracy, confusion matrix, sensitivity, and specificity. It provides a summary of the model’s performance, helping users understand how well the model predicts heart disease.

#### Step 5: Making Predictions
Users can input patient details into the sidebar. Upon clicking the "Predict" button, the app will:

Normalize Input Data: Ensures the new input data is in the same format as the training data.
Generate Predictions: Uses the trained model to predict the likelihood of heart disease.
Display Results: Shows a clear message indicating whether there is a significant chance of a heart attack.

#### Step 6: Viewing Results
The prediction result will be displayed with a clear message:

High Risk: "There is a chance of Heart attack as per the inputs provided. Please consult a cardiologist as soon as possible."
Low Risk: "There is no significant chance of heart attack."




### Contribution
Contributions are welcome! Here are ways you can contribute:

Fork the Repository: Make a copy of the repository on your GitHub account.
Create a Branch: Make a new branch for your feature or bug fix.
Make Changes: Implement your changes to the codebase.
Submit a Pull Request: Submit your changes for review.
Feel free to improve the app, fix bugs, add new features, or enhance existing functionalities. Your contributions will help make this tool better for everyone.

