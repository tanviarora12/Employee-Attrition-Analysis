# Employee-Attrition-Analysis
Employee attrition analysis and prediction using Python(EDA, ML Models)
📊 Employee Attrition Analysis

📌 Business Problem

Employee attrition (voluntary or involuntary exits) is a major challenge for organizations. High attrition rates lead to increased recruitment costs, knowledge gaps, and lower productivity.
This project analyzes HR data to identify key factors contributing to employee attrition and builds a predictive model to estimate the likelihood of attrition.

🎯 Goal

Perform exploratory data analysis (EDA) on HR dataset.
Identify patterns and factors influencing employee attrition.
Build predictive models to classify employees as “likely to leave” or "liekly to stay".

🛠 Tech Stack
🐍 Python
📈 Pandas, NumPy
📊 Matplotlib, Seaborn
🤖 Scikit-learn (Logistic Regression, Random Forest, Decision Tree)
📝 Jupyter Notebook


📊 Process

- *Data Understanding & Cleaning*
  - Checked missing values and data types
  - Removed duplicates and outliers
- *Exploratory Data Analysis (EDA)*
  - Visualized attrition distribution by age, department, job role, salary, and work-life balance
  - Created correlation heatmaps and charts
- *Feature Engineering*
  - Encoded categorical variables
  - Scaled numerical features
- *Model Building*
  - Logistic Regression
  - Decision Tree
  - Random Forest
- *Model Evaluation*
  - Compared models using Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC Curve.

 ✅ Results & Insights
- Key factors influencing attrition:
  - Job Role
  - OverTime
  - Monthly Income
  - Job Satisfaction
  - Years at Company
- Random Forest achieved the best performance (~85% accuracy)
- Employees with *high overtime* and *low job satisfaction* are most likely to leave.

📎 Dataset  
This project uses the *IBM HR Analytics Attrition Dataset* from Kaggle.  
[Download here](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)



