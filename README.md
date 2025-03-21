# Linear Regression - Medical Charges Prediction  

## 📝 Problem Statement  
ACME Insurance Inc. offers affordable health insurance to thousands of customers across the United States.  
As the lead data scientist, your task is to develop an automated system that can estimate the annual medical expenditure for new customers.  

The system will use key customer information, such as:  
- Age  
- Sex  
- BMI (Body Mass Index)  
- Number of children  
- Smoking habits  
- Region of residence  

These predictions will help determine the annual insurance premium (monthly payment) offered to each customer.  

## 📜 Regulatory Requirement  
The model must be explainable, meaning that the predictions should be interpretable and justifiable to ensure transparency in pricing.  

## 📂 Dataset Overview  
The dataset consists of **1,338 records** with the following features:  

| Feature  | Description |
|----------|------------|
| `age`  | Age of the customer (in years) |
| `sex`  | Gender (`male`, `female`) |
| `bmi`  | Body Mass Index (BMI) |
| `children`  | Number of dependent children |
| `smoker`  | Smoking status (`yes`/`no`) |
| `region`  | Residential region (`southwest`, `southeast`, `northwest`, `northeast`) |
| `charges`  | Actual medical expenses (Target variable) |

Dataset Source: [GitHub - Machine Learning with R Datasets](https://github.com/stedy/Machine-Learning-with-R-datasets)  

## 🚀 Project Workflow  
1. **Exploratory Data Analysis (EDA)**  
   - Understanding data distribution  
   - Handling missing values (if any)  
   - Detecting outliers (e.g., extreme BMI values)  
2. **Feature Engineering**  
   - Encoding categorical variables (`sex`, `smoker`, `region`)  
   - Normalization of continuous features (`age`, `bmi`)  
3. **Model Selection & Training**  
   - Applying regression models  
   - Evaluating performance using RMSE, R², etc.  
4. **Interpretability & Explainability**  
   - Understanding feature importance  
   - Ensuring regulatory compliance  

## 🛠 How to Run the Project  

### 🔧 Requirements  
Ensure you have the following installed:  

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
