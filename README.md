Electric Vehicle Sales Analysis – India
This repository contains a data analytics and machine learning project focused on Electric Vehicle (EV) adoption trends across Indian states.
​
Using Python, exploratory data analysis (EDA), feature engineering, and predictive modeling (Random Forest), the project uncovers key patterns in EV sales and provides insights that can support business and policy decisions.
​

Project Overview
The goal of this project is to analyze EV sales across different Indian states and identify the factors that drive higher adoption.
​
The project covers the complete workflow from data loading and cleaning to model building and interpretation of results.
​

Main objectives:

Understand the distribution of EV sales across Indian states.
​

Identify trends over time and by category (if available, e.g., 2W/4W/Commercial).
​

Engineer meaningful features that capture demographic, policy, or regional effects (as available in the dataset).
​

Build a machine learning model (Random Forest) to predict EV sales and evaluate its performance.
​

Derive insights and recommendations for market strategy and policymaking.
​

Dataset
File: Electric Vehicle Sales by State in India.csv
​

This dataset contains EV sales information by Indian states.
​
Columns may include (you can update with the exact column names):

State / UT name

Year or time period

EV sales count

Vehicle category or segment (if present)

Any additional numerical or categorical features included in the data

You can find the dataset in the root of the repository.
​

Files in this Repository
Electric Vehicle Sales by State in India.csv – Main EV sales dataset used for analysis.
​

Electric_Vehicle_Sales_by_State_in_India___ML___FA___DA_projects.ipynb – Jupyter Notebook containing the full workflow: EDA, feature engineering, model building, and insights.
​

Electric Vehicle Sales by State in India _ ML _ FA _ DA projects.pdf – Exported report/summary of the analysis and results.
​

.gitignore – Git ignore configuration.
​

LICENSE – MIT License for this project.
​

README.md – Project documentation.
​

Methodology
1. Data Loading and Cleaning
Load the CSV dataset using Pandas.

Inspect data types, missing values, and basic statistics.

Handle missing or inconsistent values (e.g., imputation, removal, or transformation).

Standardize state names or categorical variables as needed.

2. Exploratory Data Analysis (EDA)
Typical EDA steps in the notebook:

Univariate analysis: distribution of EV sales overall and by state.

Bivariate analysis: EV sales vs other numerical features, correlations, and patterns.

Time-based analysis (if time dimension exists): trend of EV sales over the years.

Visualization of EV adoption across states using bar plots, line plots, and other charts.

3. Feature Engineering
Examples of feature engineering steps:

Creating aggregated metrics (e.g., total EV sales per state, average yearly growth).

Encoding categorical variables (e.g., state names, categories) using suitable encoding methods.

Normalizing or scaling numerical features if required by the model.

4. Machine Learning Model
Split the data into training and testing sets.

Train a Random Forest model to predict EV sales (or another target defined in the notebook).
​

Tune key hyperparameters (e.g., number of trees, max depth) for better performance.

Evaluate the model using metrics such as R², MAE, or RMSE, depending on the task (regression).

Analyze feature importance to understand which variables most strongly influence EV sales.
​

5. Insights and Recommendations
The notebook and PDF report include insights useful for:

Identifying high-potential states for EV market expansion.
​

Understanding which factors drive higher EV adoption.

Supporting strategy decisions for manufacturers, policymakers, and other stakeholders.
​

How to Run the Project
Prerequisites
Python 3.x

Jupyter Notebook or JupyterLab

Recommended libraries (you can adjust based on your actual imports in the notebook):

pandas

numpy

matplotlib

seaborn

scikit-learn

Setup Steps
Clone the repository:

bash
git clone https://github.com/nasir331786/Electric-Vehicle-Sales-Analysis-India.git
cd Electric-Vehicle-Sales-Analysis-India
(Optional) Create and activate a virtual environment:

bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install required libraries (create requirements.txt based on the notebook imports):

bash
pip install -r requirements.txt
Launch Jupyter Notebook:

bash
jupyter notebook
Open Electric_Vehicle_Sales_by_State_in_India___ML___FA___DA_projects.ipynb and run all cells.

Example Use Cases
Students and learners exploring an end-to-end data analytics and ML project on real-world EV data.
​

Data analysts looking for a reference project on regional sales analysis.

Businesses or researchers interested in understanding EV adoption patterns in India.
​

Future Improvements
Possible extensions for this project:

Integrate additional datasets (e.g., population, income, charging infrastructure, policy incentives) to enrich the analysis.

Experiment with other models (XGBoost, Gradient Boosting, etc.) and compare their performance with Random Forest.

Build an interactive dashboard (using Streamlit, Dash, or Power BI) to visualize EV adoption across states.

Add time series forecasting (e.g., Prophet, ARIMA) if more granular time data is available.
