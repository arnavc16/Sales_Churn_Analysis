Sales Churn Analysis Project
This project involves analyzing customer churn data to identify patterns and factors contributing to customer attrition in a sales context. By utilizing data analysis, machine learning, and data visualization techniques, the project aims to develop insights that can help improve customer retention strategies.

Project Overview
Objective: Predict customer churn and identify key factors influencing it to aid in developing effective retention strategies.
Data: Customer data including demographics, account information, service usage, and churn status.
Tools and Technologies:
Data Analysis and Modeling: Python, Pandas, NumPy, Scikit-learn
Data Visualization: Matplotlib, Seaborn, Power BI
Notebooks: Jupyter Notebook
Dashboard: Power BI Desktop
Project Structure
kotlin
Copy code
sales_churn_analysis/
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebook/
│   └── churn_analysis.ipynb
├── visuals/
│   ├── churn_dashboard.pbix
│   └── churn_dashboard.pdf
├── output/
│   ├── customer_churn_predictions.csv
│   └── feature_importances.csv
├── README.md
├── requirements.txt
└── LICENSE
data/: Contains the dataset used for the analysis.
notebook/: Jupyter Notebook with code for data preprocessing, exploratory data analysis, modeling, and evaluation.
visuals/: Power BI dashboard file and exported PDF version.
output/: Contains output files such as predictions and feature importance scores.
README.md: Project description and instructions.
requirements.txt: Python dependencies required to run the project.
LICENSE: License information for the project.
Features
Data Preprocessing:
Handling missing values and correcting data types.
Encoding categorical variables using One-Hot Encoding.
Feature scaling of numerical variables.
Exploratory Data Analysis (EDA):
Visualization of churn distribution and correlations.
Analysis of churn by customer demographics and services.
Predictive Modeling:
Training models using Logistic Regression, Decision Trees, and Random Forest Classifiers.
Evaluating models using accuracy, precision, recall, F1-score, and ROC AUC.
Identifying the most important features influencing churn.
Data Visualization with Power BI:
Interactive dashboard displaying key insights.
Visualizations include churn rates, feature importances, and customer segmentation.
Filters and slicers for interactivity (e.g., by contract type, payment method).
Results and Insights
Key Factors Affecting Churn:
Contract type, tenure, monthly charges, and payment methods are significant predictors.
Model Performance:
Random Forest model achieved the highest accuracy and provided valuable feature importance insights.
Business Recommendations:
Strategies to reduce churn by targeting high-risk customer segments.
Suggestions for service improvements and personalized offers.
How to Use
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/sales_churn_analysis.git
Install Dependencies:
bash
Copy code
pip install -r requirements.txt
Data Setup:
Place the dataset CSV file in the data/ folder if not already present.
Run the Jupyter Notebook:
Navigate to the notebook/ folder.
Open churn_analysis.ipynb using Jupyter Notebook or JupyterLab.
Run the cells to reproduce the analysis.
View the Power BI Dashboard:
Open visuals/churn_dashboard.pbix using Power BI Desktop.
Alternatively, view the exported PDF visuals/churn_dashboard.pdf.
Dependencies
Python 3.x
Packages listed in requirements.txt:
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
Power BI Desktop (for viewing the dashboard)
License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Dataset Source: Telco Customer Churn Dataset from Kaggle.
Inspiration: Project inspired by real-world business challenges in customer retention and sales analysis.
