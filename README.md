# Customer Purchase Prediction Using Classification Algorithms

This project predicts whether a customer will make a purchase based on demographic and behavioral data using supervised machine learning classification techniques. It follows a complete ML pipeline from data analysis to model evaluation.

## 🎯 Objective
To build and evaluate classification models that predict customer purchase behavior using structured customer data.

## 📂 Dataset
- **Source:** Kaggle  
  https://www.kaggle.com/datasets/rt4rtr/customer-purchase-prediction
- **Size:** 1500 rows, 9 columns
- **Target Variable:** `PurchaseStatus` (Binary)

All features were already encoded, and the dataset contained no missing values.

## 🧠 Project Workflow

### 1. Data Loading & Understanding
- Loaded dataset using pandas
- Inspected structure, data types, and target distribution

### 2. Data Preprocessing
- No missing value handling required
- All categorical variables were pre-encoded
- Numerical features scaled using **StandardScaler**
- Data split into training and testing sets

### 3. Exploratory Data Analysis (EDA)
- Feature distribution analysis
- Correlation analysis using heatmaps
- Identified patterns affecting purchase behavior  
  - **Age showed a negative correlation with PurchaseStatus**

### 4. Model Building
The following models were implemented:
- **Logistic Regression**
- **Random Forest Classifier**

Models were trained using default hyperparameters.

### 5. Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

**Random Forest** achieved the best performance with an accuracy of approximately **94%**.

## 🛠️ Tech Stack
- Python (latest version)
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Results Summary
- Random Forest outperformed Logistic Regression across all evaluation metrics
- Ensemble methods proved more effective for this dataset
- Age negatively influenced purchase likelihood

## 🎓 Learning Outcomes
- Practical experience with classification models
- End-to-end ML workflow execution
- Model evaluation and comparison
- Interpretation of real-world customer behavior patterns

## 📁 Project Structure
- Jupyter Notebook containing:
  - Data preprocessing
  - EDA visualizations
  - Model training and evaluation
  - Result interpretation

---

⭐ This project was completed independently based on provided instructions and is suitable for showcasing machine learning fundamentals in internship and entry-level roles.
