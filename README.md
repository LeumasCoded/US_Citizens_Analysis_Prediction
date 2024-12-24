# US_Citizens_Analysis_Prediction
This project contains Python scripts for analysing and predicting income levels of US citizens using the Census Income dataset. Includes EDA, data preprocessing, and machine learning with ensemble modeling

---

## Files in the Repository

### **1. US_Citizens_Analysis.py**
This script focuses on the **Exploratory Data Analysis (EDA)** of the dataset, including:
- **Visualizations**:
  - Scatter plots, box plots, and histograms for features like `age`, `workclass`, and `salary`.
  - Distribution comparisons by salary levels (`<=50K` and `>50K`).
- **Insights**:
  - Analysis of features like `age`, `capital gain`, and `hours per week` by salary level.
  - Relationship between demographic features and income levels.

#### **Key Features**
- Handles missing values and removes duplicate rows.
- Renames columns for consistency.
- Visualizes correlations and distributions.

### **2. Income_Prediction_Model.py**
This script focuses on building a **machine learning model** to predict income levels, including:
- **Data Preprocessing**:
  - Encoding categorical variables with `LabelEncoder`.
  - Scaling numerical features with `StandardScaler`.
- **Class Imbalance Handling**:
  - Balances the target classes (`salary`) using **SMOTE (Synthetic Minority Oversampling Technique)**.
- **Ensemble Modeling**:
  - Combines Logistic Regression, Random Forest, Gradient Boosting, Neural Network, and Decision Tree in a Voting Classifier.
- **Evaluation**:
  - Outputs metrics: Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
  - Displays a confusion matrix and feature importance.

---

## **How to Run the Project**

### **Prerequisites**
- Install Python 3.x and the following Python libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `imbalanced-learn`

### **Clone the Repository**
```bash
git clone https://github.com/your-username/US_Citizens_Analysis_and_Prediction.git
cd US_Citizens_Analysis_and_Prediction
