# Healthcare-Provider-Fraud-Detection-Using-Machine-Learning

The proposed project focuses on developing a machine learning-based fraud detection system for Medicare providers. Healthcare fraud in Medicare involves billing for services not provided, submitting duplicate claims, misrepresenting services, charging for more expensive procedures than performed, and billing for non-covered services. This increases healthcare costs, impacts insurance companies, and raises premiums. Preventing fraud is vital for affordable and accessible healthcare.

The project aims to predict potentially fraudulent providers based on their filed claims and identify key variables that indicate fraudulent behavior. Additionally, it will analyze fraudulent patterns in provider claims to gain insights into future behavior.

## Dataset Used
Source:- https://www.kaggle.com/datasets/rohitrox/healthcare-provider-fraud-detection-analysis

#### Introduction to the Dataset
For the purpose of this project, we are considering Inpatient claims, Outpatient claims and Beneficiary details of each provider. Lets s see their details :

A) Inpatient Data

This data provides insights about the claims filed for those patients who are admitted in the hospitals. It also provides additional details like their admission and discharge dates and admit d diagnosis code.

B) Outpatient Data

This data provides details about the claims filed for those patients who visit hospitals and not admitted in it.

C) Beneficiary Details Data

This data contains beneficiary KYC details like health conditions,regioregion they belong to etc.

## Implementation Plan
1. Data Collection and Exploration
2. Data Analysis (understand the data distribution, missing values, and potential challenges) and 
Preprocessing (handling missing values, outliers, and data normalization)
3. Feature Engineering (Extract and engineer meaningful features from the datasets to enhance model performance)
4. Create New features (based on domain knowledge and data analysis to capture relevant information that can help identify fraudulent patterns)
5. Model Selection (Random Forest) and Training
6. Model Evaluation and Optimization
7. Fraudulent Pattern Analysis
   
## ML Formulation
Build a binary classification model based on the claims filed by the provider along with Inpatient data, Outpatient data, Beneficiary details to predict whether the provider is potentially fraudulent or not.

## IDE Used
Jupyter Notebook

## Programming Language Used
Python

## References
1. https://www.kaggle.com/code/rajesh2609/medicare-provider-fraud-detection/notebook
2. https://medium.com/analytics-vidhya/healthcare-provider-fraud-detection-analysis-using-machine-learning-81ebf09ed955
