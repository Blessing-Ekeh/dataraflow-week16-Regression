# Week 16 - Datasets Dictionary

Information on all the datasets required for completing the Week 16 assignments on Advanced Regression & Classification Techniques (Random Forest Regression, Model Performance Evaluation, and Logistic Regression).

## Folder Structure

```
Week-16 (Regression-3)/
│
├── Task-Datasets/
│   ├── task1_random_forest_data.csv
│   ├── task2_model_evaluation_data.csv
│   └── task3_classification_data.csv
│
├── Assignment-Dataset/
│   ├── assignment1_house_prices.csv
│   ├── assignment2_marketing_campaign.csv
│   └── assignment3_credit_risk.csv
│
└── Assessment-Dataset/
    └── customer_churn_prediction.csv
```


## Task Datasets

### 1. task1_random_forest_data.csv
**Purpose**: Practice implementing Random Forest Regression and comparing with other regression models

**Columns**:
- `Feature` (numeric): Independent variable (1-20)
- `Target` (numeric): Dependent variable with non-linear pattern (100-5000)

**Records**: 20 rows  
**Pattern**: Complex non-linear relationship ideal for ensemble methods

### 2. task2_model_evaluation_data.csv
**Purpose**: Practice comprehensive model evaluation metrics for regression

**Columns**:
- `Experience` (numeric): Years of experience (0-15)
- `Training_Hours` (numeric): Training hours completed (10-200)
- `Previous_Projects` (numeric): Number of previous projects (0-20)
- `Salary` (numeric): Annual salary in thousands ($30-$150)

**Records**: 50 rows

### 3. task3_classification_data.csv
**Purpose**: Implement Logistic Regression for binary classification

**Columns**:
- `Customer_ID` (string): Unique identifier
- `Age` (numeric): Customer age (18-65)
- `Income` (numeric): Annual income ($15,000-$150,000)
- `Purchased` (binary): Whether customer purchased (0=No, 1=Yes)

**Records**: 100 rows
**Pattern**: Binary classification with age and income as predictors

## Assignment Datasets

### 1. assignment1_house_prices.csv
**Purpose**: Compare multiple regression models and evaluate performance comprehensively

**Columns**:
- `Square_Feet` (numeric): House size in square feet (800-5000)
- `Bedrooms` (numeric): Number of bedrooms (1-6)
- `Bathrooms` (numeric): Number of bathrooms (1-5)
- `Age` (numeric): House age in years (0-50)
- `Distance_to_City` (numeric): Distance to city center in miles (1-30)
- `Garage` (binary): Has garage (0=No, 1=Yes)
- `Pool` (binary): Has pool (0=No, 1=Yes)
- `Price` (numeric): House price in thousands ($100-$900) - **Target variable**

**Records**: 150 rows

### 2. assignment2_marketing_campaign.csv
**Purpose**: Binary classification with comprehensive evaluation metrics

**Columns**:
- `Customer_ID` (string): Unique customer identifier
- `Age` (numeric): Customer age (20-70)
- `Income` (numeric): Annual income ($20,000-$200,000)
- `Spending_Score` (numeric): Spending score (1-100)
- `Membership_Years` (numeric): Years as member (0-15)
- `Previous_Purchases` (numeric): Number of previous purchases (0-50)
- `Email_Opens` (numeric): Number of marketing emails opened (0-30)
- `Website_Visits` (numeric): Monthly website visits (0-40)
- `Responded` (binary): Responded to campaign (0=No, 1=Yes) - **Target variable**

**Records**: 300 rows
**Class Balance**: Approximately 60% No, 40% Yes

### 3. assignment3_credit_risk.csv
**Purpose**: Multi-class classification with Random Forest and model comparison

**Columns**:
- `Application_ID` (string): Unique application identifier
- `Age` (numeric): Applicant age (21-65)
- `Income` (numeric): Annual income ($15,000-$250,000)
- `Employment_Years` (numeric): Years employed (0-40)
- `Credit_Score` (numeric): Credit score (300-850)
- `Loan_Amount` (numeric): Requested loan amount ($1,000-$100,000)
- `Debt_to_Income` (numeric): Debt-to-income ratio (0-1)
- `Previous_Defaults` (numeric): Number of previous defaults (0-5)
- `Credit_History_Length` (numeric): Length of credit history in years (0-30)
- `Risk_Category` (categorical): Low, Medium, High - **Target variable**

**Records**: 400 rows
**Class Distribution**: Low (40%), Medium (35%), High (25%)

## Assessment Dataset

### customer_churn_prediction.csv
**Purpose**: Comprehensive project integrating regression evaluation and classification techniques

**Columns**:
- `Customer_ID` (string): Unique customer identifier
- `Age` (numeric): Customer age (18-75)
- `Gender` (categorical): Male, Female
- `Tenure` (numeric): Months as customer (1-72)
- `Monthly_Charges` (numeric): Monthly charges ($20-$120)
- `Total_Charges` (numeric): Total charges to date ($20-$8500)
- `Contract_Type` (categorical): Month-to-Month, One Year, Two Year
- `Internet_Service` (categorical): DSL, Fiber Optic, No
- `Payment_Method` (categorical): Electronic Check, Mailed Check, Bank Transfer, Credit Card
- `Paperless_Billing` (binary): Yes=1, No=0
- `Tech_Support` (binary): Yes=1, No=0
- `Online_Security` (binary): Yes=1, No=0
- `Streaming_TV` (binary): Yes=1, No=0
- `Streaming_Movies` (binary): Yes=1, No=0
- `Phone_Service` (binary): Yes=1, No=0
- `Multiple_Lines` (binary): Yes=1, No=0
- `Customer_Satisfaction_Score` (numeric): Satisfaction score (1-5)
- `Support_Calls` (numeric): Number of support calls in last 3 months (0-15)
- `Churn` (binary): Churned=1, Stayed=0 - **Target variable**

**Records**: 500 rows
**Class Distribution**: Churned (30%), Stayed (70%)

**Pattern**: Real-world telecom customer churn with multiple features and imbalanced classes

**Complexity**: Advanced - requires integration of:
- Week 14: Data preprocessing (encoding, scaling)
- Week 15: Advanced regression techniques
- Week 16: Random Forest, Model Evaluation, Logistic Regression
- Business acumen for practical recommendations



## Data Quality Notes

- All datasets are synthetic but realistic
- Task datasets are clean (no missing values)
- Assignment and Assessment datasets may require preprocessing
- Classification datasets have realistic class distributions
- Features designed to demonstrate key concepts
- Ranges and scales appropriate for real-world scenarios


**Note**: Refer to this Data Dictionary when working on Week 16 assignments.