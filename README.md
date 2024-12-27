**Renewable Energy Consumption Prediction**
**Project Overview:** This project aims to predict renewable energy consumption in the USA using machine learning models, specifically Random Forest (RF) and Support Vector Machine (SVM). The project involves data preprocessing, exploratory data analysis (EDA), and a model comparison to assess the performance of both algorithms.

**Table of Contents**

Project Setup 

Data Preprocessing

Exploratory Data Analysis (EDA)

Model Development

Model Comparison

Results

Technologies Used

**Project Setup**
Prerequisites:
Python 3.7 or higher
Install the required libraries using the following:

pip install -r requirements.txt
Running the Project:
Clone the repository:
git clone https://github.com/Alifida1/Traditional-ML-Modelling.git

**Navigate to the project directory:**

cd renewable-energy-consumption

**Run the Jupyter notebooks or Python scripts for the steps involved:**

comparative-analysis-on-renewable-energy-data.py 

**Data preprocessing**

**Handling Missing Data:** Applied imputation or removal techniques for missing values in the dataset.

**Feature Encoding:** Used one-hot encoding for categorical variables and label encoding for target variables like Sector.

**Feature Scaling:** Applied standardization to numerical features to ensure uniformity, especially for SVM.

**Data Splitting:** Divided the dataset into 80% training and 20% testing sets.

**Exploratory Data Analysis (EDA)**

**Data Summarization:** Analyzed basic statistics such as mean, median, and standard deviation.

**Correlation Analysis:** Visualized correlations between numerical features using heatmaps.

**Visualization:** Created plots (e.g., histograms, box plots) to explore data distribution and detect outliers.

**Seasonal and Sector Analysis:** Investigated energy consumption trends across different seasons and sectors.

**Model Development**

Random Forest (RF) Model

**Overview:** Used Random Forest (ensemble method) with 100 trees.

**Training:** Trained the model on the training set and evaluated using accuracy, precision, recall, and F1 score.

**Cross-validation:** Used 5-fold cross-validation to assess model performance.

**Support Vector Machine (SVM) Model**

**Overview:** Trained an SVM model with an RBF kernel to classify energy consumption sectors.

**Training:** Optimized hyperparameters like regularization and kernel type.

**Cross-validation:** Also applied 5-fold cross-validation for performance evaluation.

**Model Comparison**

Evaluation Metrics: Compared the Random Forest and SVM models based on:

Accuracy
Precision
Recall
F1 Score

**Visualization:** Generated radar charts and bar plots to visually compare model performance across different evaluation metrics.

**Results**

Random Forest showed better overall stability and performance, especially in terms of accuracy and recall.
SVM performed well with precision but had slightly lower performance on recall but overall SVM outperformed with higher accuracy.
The models were evaluated using cross-validation, ensuring robust performance metrics.
