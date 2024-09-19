# Customer Churn Analysis

This project aims to analyze customer churn data, build predictive models, and visualize key insights using Power BI. The project utilizes various machine learning techniques to predict customer churn and provide insights into factors that influence churn behavior.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Description](#dataset-description)
3. [Data Preprocessing](#data-preprocessing)
4. [Modeling](#modeling)
5. [Model Evaluation](#model-evaluation)
6. [Power BI Dashboard](#power-bi-dashboard)
7. [Installation](#installation)
8. [Usage](#usage)
9. [Results and Insights](#results-and-insights)
10. [References](#references)
11. [License](#license)

## Project Overview
Customer churn is a major problem for companies, especially in competitive industries such as telecom. This project provides an end-to-end analysis and predictive modeling to identify factors contributing to customer churn and predict which customers are likely to churn.

## Dataset Description
The dataset used for this project is the [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn). It contains information about:
- **Customer demographics**
- **Services subscribed to**
- **Account information**

### Key Columns:
- `tenure`: Number of months the customer has stayed with the company.
- `MonthlyCharges`: The amount charged to the customer monthly.
- `TotalCharges`: The total amount charged to the customer.
- `Churn`: Target variable indicating whether the customer has churned (Yes/No).

## Data Preprocessing
The dataset was preprocessed to handle missing values, encode categorical variables, and standardize numerical features. Key steps include:
1. Converting `TotalCharges` to numeric and handling missing values.
2. Dropping the `customerID` column.
3. Encoding categorical variables using Label Encoding and One-Hot Encoding.
4. Standardizing numerical features.

## Modeling
Three models were trained to predict customer churn:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**

## Model Evaluation
Models were evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC AUC Score**

Visualizations for model performance, including confusion matrices and ROC curves, were created to compare the models.

## Power BI Dashboard
The insights and predictions from the analysis were visualized in a Power BI dashboard. This dashboard provides a comprehensive view of customer demographics, service usage, and churn predictions.

### Power BI Files:
- **Power BI Dashboard:** [Download Power BI File](https://github.com/arnavc16/Sales_Churn_Analysis/blob/main/docs/churn_dashboard.pbix)
- **PDF Report:** [Download PDF Report](https://github.com/arnavc16/Sales_Churn_Analysis/blob/main/docs/churn_report.pdf)

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/arnavc16/Sales_Churn_Analysis.git

2. Install the required Python packages:
   pip install -r requirements.txt

3. Run the Jupyter notebook churn.ipynb in the notebooks/ directory.

## Usage
1. Open the churn.ipynb notebook and run the cells sequentially to reproduce the analysis.
2. View the Power BI dashboard using Power BI Desktop.
3. The dashboard and PDF reports can be found in the docs/ directory.

## Results and Insights
- The Random Forest model was the most accurate in predicting customer churn.
- Customers with short tenure, high monthly charges, and no contract are more likely to churn.
- The Power BI dashboard provides interactive insights into customer behavior and churn patterns.

## References
- Telco Customer Churn Dataset
- Scikit-learn Documentation
- Power BI Documentation

## License
This project is licensed under the MIT License - see the LICENSE file for details.
