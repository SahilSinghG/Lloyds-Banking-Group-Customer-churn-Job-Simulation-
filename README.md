# 📊 Customer Churn Prediction – Lloyds Banking Group Data Science Simulation

This project was completed as part of the **Lloyds Banking Group Data Science Job Simulation** on the **Forage platform**.

The goal of this project is to analyze customer data and build a machine learning model that predicts **customer churn**. Predicting churn helps financial institutions identify customers at risk of leaving and implement targeted retention strategies.

---

# 📌 Project Overview

Customer churn prediction is a critical problem in the banking industry. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project follows a **complete data science workflow**, including:

- Data collection and integration  
- Exploratory Data Analysis (EDA)  
- Data cleaning and preprocessing  
- Feature engineering  
- Machine learning model development  
- Model evaluation and interpretation  

The final model predicts whether a customer is **likely to churn** based on demographic, behavioral, and financial attributes.

---

# 🗂 Dataset Description

The dataset contains multiple tables representing different aspects of customer behavior.

### 👤 Customer Demographics
- Age  
- Gender  
- Marital Status  
- Income Level  

### 💳 Transaction History
- Transaction amounts  
- Spending behavior  

### 📞 Customer Service Interactions
- Customer complaints and service requests  

### 🌐 Online Activity
- Login frequency  
- Digital banking usage  

### 🚪 Churn Status
- Target variable indicating whether a customer left the bank  

All datasets were merged using the **CustomerID** field to create a unified dataset for analysis.

---

# 🔍 Task 1 – Data Gathering & Exploratory Data Analysis

The first phase of the project focused on understanding and preparing the data.

### Key Steps

- Integrating multiple datasets
- Performing Exploratory Data Analysis (EDA)
- Identifying missing values and outliers
- Encoding categorical variables
- Standardizing numerical features

### 📈 Visualizations Used

- Histograms

<img width="718" height="481" alt="image" src="https://github.com/user-attachments/assets/3c03b809-94bd-4dc6-982e-a8dafb7cebbe" />

- Boxplots

<img width="657" height="452" alt="image" src="https://github.com/user-attachments/assets/8a2c094a-dc21-4876-8b90-551db7311ec6" />

<img width="673" height="452" alt="image" src="https://github.com/user-attachments/assets/1c7d6971-5eab-4faf-98bd-fee371ba0e8c" />

- Count plots

<img width="598" height="468" alt="image" src="https://github.com/user-attachments/assets/e8e5a811-539c-4ab9-a8ea-fb27ac44d624" />

<img width="677" height="466" alt="image" src="https://github.com/user-attachments/assets/6f9a4ec8-19df-42bc-983d-5074fc12f797" />

<img width="731" height="435" alt="image" src="https://github.com/user-attachments/assets/438c8637-df70-4059-8e8b-b5281dbd6a04" />

<img width="658" height="448" alt="image" src="https://github.com/user-attachments/assets/f9418a1d-ca85-455a-a85d-15e72bb1b109" />

- Correlation heatmaps

<img width="768" height="507" alt="image" src="https://github.com/user-attachments/assets/2a70b716-e414-4ad5-b5bb-812b9737365c" />

The EDA revealed patterns related to customer churn, such as **lower login frequency and reduced transaction activity**.

---

# 🤖 Task 2 – Machine Learning Model Development

After preparing the dataset, a machine learning model was built to predict customer churn.

### ⚙ Algorithm Used

**Logistic Regression**

This algorithm was selected because it provides:

- High interpretability
- Efficient performance on structured data
- Probability-based predictions for churn risk

### 🧠 Model Training

- Dataset split into **80% training / 20% testing**
- Model trained using **Scikit-learn**

### 📊 Model Evaluation Metrics

<img width="771" height="542" alt="image" src="https://github.com/user-attachments/assets/e662f4a5-68ef-427c-8d5b-82b517c5b725" />

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC-AUC Score

<img width="446" height="158" alt="image" src="https://github.com/user-attachments/assets/a370f2d6-c085-4b2a-bd2f-0484775b453b" />

These metrics provide a comprehensive evaluation of model performance.

---

# 📌 Key Insights

The analysis identified several important factors influencing customer churn:

- Customers with **low login frequency** are more likely to churn.
- **Lower transaction activity** may indicate disengagement.
- Customers who rarely use **online banking services** show higher churn risk.
- **Income level and demographic factors** may influence customer retention.

These insights can help banks design **targeted retention strategies**.

---

# 🛠 Technologies Used

- 🐍 Python
- 📊 Pandas
- 🔢 NumPy
- 🤖 Scikit-learn
- 📉 Matplotlib
- 📈 Seaborn
- 📓 Jupyter Notebook

---

# 📁 Project Structure

Customer-Churn-Prediction
│
├── Task1_EDA_Notebook.ipynb
├── Task2_ML_Model.ipynb
├── Customer_Churn_Dataset.xlsx
├── Task1_Report.pdf
├── Task2_Report.pdf
└── README.md

# 💡 Business Impact

This churn prediction model enables financial institutions to:

- Identify high-risk customers early
- Implement targeted retention campaigns
- Improve customer engagement
- Reduce revenue loss due to churn

---

# 🚀 Future Improvements

Future enhancements may include:

- Testing advanced models such as **Random Forest or XGBoost**
- Handling class imbalance using **SMOTE**
- Building a **real-time churn prediction API**
- Deploying the model as a web application

---

# 📚 Conclusion

This project demonstrates how data science techniques can be used to solve real-world business problems. By combining exploratory data analysis with machine learning, the project provides actionable insights into customer behavior and churn prediction.
