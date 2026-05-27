## Overview

This project demonstrates a simple Human Gait Recognition System using machine learning and data visualization techniques. The system analyzes walking characteristics such as step length, stride width, walking speed, and body angle to identify different individuals.

**Features**
Data analysis using Pandas
Data visualization using Matplotlib and Seaborn
Correlation heatmap generation
Machine learning model using Random Forest Classifier
Accuracy evaluation and confusion matrix
Prediction for new gait data
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Installation

Install the required libraries using the following command:

pip install pandas numpy matplotlib seaborn scikit-learn
Dataset

**The dataset contains the following attributes:**

Step Length
Stride Width
Walking Speed
Body Angle
Person ID
How It Works
Load and preprocess gait data
Visualize data using graphs and heatmaps
Train the Random Forest model
Test model performance
Predict person identity using new gait inputs
Output Visualizations
Walking Speed Distribution Histogram
Step Length vs Walking Speed Scatter Plot
Correlation Heatmap
Confusion Matrix
new_person = [[68, 24, 4.1, 14]]
prediction = model.predict(new_person)
**Example Prediction**
print("Predicted Person ID:", prediction[0])
