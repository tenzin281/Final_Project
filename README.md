# Final_Project
Predicting Airplane Delays due to Weather
The priorities of the project play a major role in selecting one of the two approaches. The linear model works well for monitoring that is explainable or occurs in real time. Notwithstanding its greater resource requirements, XGBoost provides more powerful capabilities for in-depth, predictive analytics to find patterns and correlations in wy
ater quality.

Forecasting Weather-Related Aircraft Delays
The goal of this research is to forecast weather-related delays on domestic flights in the United States. This technique helps to give clients useful information about the possibility of delays when booking flights by creating machine learning models.

Overview of the Project
This project consists of:

For delay prediction, data processing and exploratory data analysis (EDA) are used.
constructing both basic and sophisticated machine learning models (XGBoost and logistic regression).
examination of the models' relative performances.
The dataset
The Bureau of Transportation Statistics provides the dataset, which includes information on domestic flights in the United States from 2014 to 2018.



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

Upload the given notebook to a Jupyter Notebook instance.
Change the notebook's file paths to point to your local folders.
Make sure that the data loading, preprocessing, and model training processes are finished by running each cell one after the other.
Training and Assessing Models:

As a baseline, the notebook initially trains a logistic regression model.
It then creates an ensemble model for comparison performance using XGBoost.
Look for model performance indicators like accuracy, precision, recall, and F1-score in the notebook cells.
Deploying the Model:

The trained models should be hosted on SageMaker endpoints if the system is using SageMaker.
To assess model performance on the hosted instance, run batch transformations on the test data.
Model Comparison:

Examine the model outputs to determine how the XGBoost and linear models differ in terms of performance metrics.
Executing the Code on Various Computers
Establish Relative Paths:
Every path used to store data files and models should be relative (data/combined_csv_v1.csv, for example).
Configuring the Environment: If working with huge datasets, make sure the code runs in an environment with at least 25 GB of memory.

