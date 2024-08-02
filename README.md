# Heart Disease Prediction

This project leverages machine learning algorithms to predict the likelihood of heart disease based on patient data such as age, cholesterol levels, blood pressure, and other health metrics. The goal is to provide a reliable tool for early diagnosis and preventive healthcare.

This project aims to predict the likelihood of heart disease in patients using various machine learning algorithms. By analyzing features such as age, cholesterol levels, blood pressure, and other health metrics, the model helps in early diagnosis and preventive healthcare.

# Project Overview
The project is structured to include data preprocessing, exploratory data analysis (EDA), model building, and evaluation. The final model can be used for predicting the presence of heart disease based on patient data.

# File Structure
* [Heart Disease Prediction.ipynb](https://github.com/shrek-28/heart-disease-prediction/blob/main/Heart%20Disease%20Prediction.ipynb): The main Jupyter Notebook that contains all steps of the project, including data cleaning, feature selection, model building, and evaluation.

# Prerequisites
To run this project, you need to have the following installed:
* Python 3.x
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

Install the required libraries using the following command:
```
pip install pandas numpy scikit-learn matplotlib seaborn
```

# Getting Started
* Clone the Repository:
```
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
```
*  Run the Jupyter Notebook
Open the [Heart Disease Prediction.ipynb](https://github.com/shrek-28/heart-disease-prediction/blob/main/Heart%20Disease%20Prediction.ipynb) notebook in Jupyter Notebook and run the cells to execute the full workflow.

# Project Workflow
* Data Preprocessing:
- Handle missing values and outliers.
- Encode categorical variables for model compatibility.
* Exploratory Data Analysis (EDA):
- Visualize the distribution of key variables.
- Analyze the relationships between features and the target variable (heart disease).
* Feature Selection: Identify and select the most relevant features for modeling.
* Modeling:
- Implement various classification models, such as Logistic Regression, Random Forest, and Support Vector Machines (SVM).
- Train models on the processed dataset.
* Model Evaluation:
- Evaluate model performance using metrics like accuracy, precision, recall, and AUC-ROC scores.
- Compare different models and select the best-performing one.

# Results
The final model provides accurate predictions of heart disease presence, which can be useful for medical professionals in early diagnosis and treatment planning.

# Future Improvements
* Incorporating additional health metrics or patient data for improved predictions.
* Implementing more advanced models like Gradient Boosting or Neural Networks.
* Deploying the model using Flask for real-time predictions.

Disclaimer: This was done as part of the project work for the Udemy Course [Python for Data Science and Machine Learning Masterclass](https://www.udemy.com/course-dashboard-redirect/?course_id=2769460)
