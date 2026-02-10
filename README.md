# Accident_predection_model
Binary classification model using Logistic Regression to predict accident survival based on demographic and safety factors.
🚦 Road Accident Survival Prediction using Machine Learning

This project uses Machine Learning to predict whether a person survives a road accident based on various factors such as age, gender, speed of impact, helmet usage, and seatbelt usage.

📌 Project Overview

Road accidents are one of the leading causes of fatalities worldwide. This project aims to analyze accident-related data and build a binary classification model to predict survival outcomes using Logistic Regression.

🧠 Machine Learning Details

Algorithm: Logistic Regression

Problem Type: Binary Classification

Target Variable: Survived (0 = Not Survived, 1 = Survived)

📊 Dataset Features
Feature	Description
Age	Age of the person
Gender	Male / Female
Speed_of_Impact	Speed during the accident
Helmet_Used	Whether helmet was used
Seatbelt_Used	Whether seatbelt was used
Survived	Target variable
⚙️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

🔍 Data Preprocessing

Handled missing values using median and mode

Encoded categorical features using Label Encoding

Applied StandardScaler for feature normalization

Split dataset into training and testing sets (80:20)

📈 Exploratory Data Analysis (EDA)

The following visualizations were used:

Survival count distribution

Speed of impact vs survival (Box Plot)

Confusion Matrix heatmap

These plots help in understanding patterns and relationships within the data.

✅ Model Evaluation

The model performance was evaluated using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)
