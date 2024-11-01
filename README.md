# Final_Project
Predicting Airplane Delays due to Weather
This project aims to predict delays in domestic U.S. flights due to weather conditions. By building machine learning models, this tool assists in providing valuable insights to customers during flight bookings on the likelihood of delays.

Project Overview
This project includes:

Data processing and exploratory data analysis (EDA) for delay prediction.
Building baseline and advanced machine learning models (logistic regression and XGBoost).
Comparative performance analysis between the models.
Dataset
The dataset contains U.S. domestic flight details between 2014 and 2018, provided by the Bureau of Transportation Statistics.

Installation and Setup
Prerequisites
Python: Install Python (3.7 or above).
Libraries:
Install necessary libraries by running the following command:
bash
Copy code
pip install pandas scikit-learn xgboost
Amazon SageMaker (Optional): If running on AWS, set up an Amazon SageMaker environment.
Step-by-Step Guide
Data Preparation:

Download the dataset from the provided links and extract all compressed files.
Place the downloaded data files in the data/ folder within your project directory.
Running the Notebook:

Open a Jupyter Notebook instance and upload the provided notebook.
Update the file paths in the notebook to reference your local directories.
Run each cell sequentially, ensuring that data loading, preprocessing, and model training steps complete successfully.
Model Training and Evaluation:

The notebook first trains a logistic regression model as a baseline.
Then, using XGBoost, it builds an ensemble model for comparative performance.
Check the output in the notebook cells for model performance metrics such as accuracy, precision, recall, and F1-score.
Deploying the Model:

If running on SageMaker, host the trained models on SageMaker endpoints.
Perform batch transformations on the test data to evaluate model performance on the hosted instance.
Comparison of Models:

Analyze the model outputs to understand differences in the performance metrics between the linear and XGBoost models.
Running the Code on Different Machines
Set Relative Paths:
All paths for data files and model storage should be relative (e.g., data/combined_csv_v1.csv).
Environment Configuration:
Ensure the code is executed in an environment with at least 25 GB of memory if working on large datasets.
