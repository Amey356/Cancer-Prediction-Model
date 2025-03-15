# **Cancer Prediction Model 🏥📊**  

## **Overview**  
This project builds a **Cancer Prediction Model** using different regression algorithms to estimate cancer probability. The goal is to help in early detection and analysis of cancer risk based on patient data.  

The following regression algorithms are used in this model:  
- **Linear Regression**  
- **Polynomial Regression**  
- **Lasso Regression**  
- **Ridge Regression**  
- **Elastic Net Regression**  
- **KNN Regression**  
- **Decision Tree Regression**  
- **Random Forest Regression**  
- **XGBoost Regression**  

## **Dataset**  
The dataset used is **"cancer_reg.csv"**, which contains various patient-related features that help in predicting cancer probability. The dataset undergoes preprocessing to handle missing values, normalize numerical features, and encode categorical variables where necessary.  

## **Project Workflow** 🚀  

### **1. Data Preprocessing**  
- Handling missing values to ensure data completeness.  
- Encoding categorical features where required.  
- Normalizing numerical features for better model performance.  

### **2. Exploratory Data Analysis (EDA)**  
- Understanding the key features that affect cancer probability.  
- Visualizing trends and relationships between variables.  

### **3. Feature Engineering**  
- Selecting the most important features for prediction.  
- Creating new features to improve model accuracy.  

### **4. Model Implementation**  
- Training and testing different regression models.  
- Comparing the models based on their performance.  

### **5. Model Evaluation**  
The models are evaluated using the following metrics:  
- **Mean Absolute Error (MAE)** – Measures the average absolute difference between actual and predicted values.  
- **Mean Squared Error (MSE)** – Measures the average squared difference between actual and predicted values.  
- **R² Score** – Measures how well the independent variables explain the variance in the dependent variable.  

## **Results & Key Insights** 🔍  
- **Polynomial Regression** captures non-linear patterns effectively.  
- **Regularization techniques (Lasso, Ridge, Elastic Net)** improve model generalization.  
- **Tree-based models (Decision Tree, Random Forest, XGBoost)** perform well in handling complex interactions.  
- **Random Forest Regression provides the best accuracy**, making it the most effective model for this dataset.  

## **Technologies Used**  

- **Python**  
- **Pandas** – Data manipulation and analysis.  
- **NumPy** – Numerical computations.  
- **Scikit-learn** – Machine learning algorithms.  
- **Matplotlib & Seaborn** – Data visualization.  

## **Contribution**  

Feel free to contribute by optimizing hyperparameters, testing new models, or improving feature selection! 😊  

## **License**  

This project is open-source under the **MIT License**.

