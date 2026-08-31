ML-Task-5
🤖 ML Task 5 – Customer Churn Prediction
This repository contains Machine Learning Task 5, focused on analyzing customer data and building machine learning models for customer churn prediction.

The project uses the Churn Modelling dataset and includes data analysis, preprocessing, feature selection, model implementation, and evaluation using Python and popular machine learning libraries.


📌 Project Overview
Customer churn prediction is a machine learning problem where we try to identify customers who are likely to leave a company based on their demographic and account-related information.

The main objective of this project is to:

Understand and explore the customer dataset
Perform data preprocessing
Select relevant features
Train machine learning models
Evaluate model performance
Predict whether a customer is likely to churn


📂 Repository Structure
ML-Task-5/
│
├── Churn_Modelling (MAM) - Churn_Modelling (3).csv
│
├── ML_Task_5(dc).ipynb
│
├── ML_Task_5(fs).ipynb
│
└── README.md


📄 Files
File	Description
Churn_Modelling (MAM) - Churn_Modelling (3).csv	Dataset used for the machine learning task
ML_Task_5(dc).ipynb	Jupyter Notebook containing the main data analysis/modeling work
ML_Task_5(fs).ipynb	Jupyter Notebook containing feature-selection related work
README.md	Project documentation



📊 Dataset
The project uses the Churn Modelling dataset, which contains customer information and a target variable indicating whether a customer has exited/churned.

Important Features
Some of the important columns include:

CreditScore
Geography
Gender
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary
Target Variable


Target Variable
Exited
Exited indicates whether the customer has left the company.

0 → Customer did not churn
1 → Customer churned


🛠️ Technologies Used
🐍 Python
📓 Jupyter Notebook
🧮 NumPy
🐼 Pandas
📊 Matplotlib
📈 Seaborn
🤖 Scikit-learn


🔄 Machine Learning Workflow
The project follows a basic machine learning workflow:

Dataset
   ↓
Data Loading
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Churn Prediction


🔍 Data Preprocessing
The dataset is prepared before training the machine learning model.

The preprocessing steps include:

Loading the dataset using Pandas
Checking missing values
Understanding data types
Removing unnecessary columns
Encoding categorical variables
Selecting useful features
Splitting the dataset into training and testing sets


🎯 Feature Selection
Feature selection is used to identify the most useful features for predicting customer churn.

The project includes a separate notebook:

ML_Task_5(fs).ipynb
This notebook focuses on feature-selection-related analysis.

🤖 Machine Learning Model
The selected features are used to train a machine learning classification model.

The model learns patterns from existing customer data and attempts to predict whether a new customer is likely to churn.

Prediction
Input Customer Data
        ↓
Machine Learning Model
        ↓
Churn Prediction
        ↓
0 → No Churn
1 → Churn

📈 Model Evaluation
The model can be evaluated using common classification metrics such as:

Accuracy
Precision
Recall
F1-Score
Confusion Matrix
These metrics help determine how effectively the model identifies customers who are likely to churn.



🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/Rabinson-20/ML-Task-5.git
2. Open the project
cd ML-Task-5
3. Install required libraries
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
4. Start Jupyter Notebook
jupyter notebook
5. Open the notebooks
Run:

ML_Task_5(dc).ipynb
or

ML_Task_5(fs).ipynb


💡 Key Learning Outcomes
Through this project, I learned how to:

Work with real-world datasets
Perform exploratory data analysis
Preprocess machine learning data
Handle categorical features
Select important features
Build classification models
Evaluate machine learning models
Understand customer churn prediction
