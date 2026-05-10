🌸 Task 1 – Iris Flower Classification
📌 Overview

This task focuses on performing Exploratory Data Analysis (EDA) and building a classification model using the Iris dataset. The objective is to analyze feature relationships and develop a predictive model capable of classifying iris flowers into their respective species.

The implementation follows a structured data science workflow, covering data preparation, visualization, model training, and performance evaluation.

🎯 Objective
Perform exploratory data analysis on the Iris dataset
Visualize feature distributions and relationships
Train a Random Forest classification model
Evaluate model performance using standard metrics
📊 Dataset Used

File: iris.csv

The dataset contains:

150 observations
4 numerical features:
Sepal Length
Sepal Width
Petal Length
Petal Width
1 target variable:
Species (Setosa, Versicolor, Virginica)
🛠 Implementation

Main Script: iris flower classification.py

The workflow includes:

Loading the dataset
Converting data into a structured format
Performing data visualization using Seaborn pairplots
Splitting data into training (80%) and testing (20%) sets
Training a Random Forest Classifier
Evaluating model performance using:
Accuracy Score
Classification Report
Confusion Matrix
▶️ How to Run
✅ On Google Colab
Open Google Colab
Upload:
iris flower classification.py
iris.csv
Install required libraries (if needed):
!pip install pandas numpy matplotlib seaborn scikit-learn
Run the script:
!python "iris flower classification.py"
✅ Locally
Install dependencies:
pip install numpy pandas matplotlib seaborn scikit-learn
Make sure iris.csv is in the same folder as the script.
Run:
python "iris flower classification.py"
📈 Expected Output
Dataset preview
Feature visualization plots
Model training results
Accuracy score
Classification report
Confusion matrix
