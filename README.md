#  Titanic Dataset — Data Cleaning and Preprocessing

This notebook, `titanic-dataset-data-cleaning-and-preprocessing.ipynb`, implements a full **professional data cleaning pipeline** on the Titanic dataset, transforming messy raw data into a machine-learning-ready format.

---

##  Table of Contents

- [Introduction](#introduction)
- [Tech Stack](#tech-stack)
- [Notebook Workflow](#notebook-workflow)
- [Key Techniques Used](#key-techniques-used)
- [How to Run](#how-to-run)
- [Dataset Source](#dataset-source)
- [Before vs After Cleaning](#before-vs-after-cleaning)
- [License](#license)

---

##  Introduction

Cleaning and preprocessing are crucial first steps in any data science or machine learning project.  
This notebook demonstrates **real-world**, **professional-grade** techniques to:

- Identify and handle missing data
- Encode categorical variables correctly
- Scale numerical features
- Detect and remove outliers
- Perform feature correlation analysis
- Save and compare cleaned vs raw datasets

---

##  Tech Stack

- **Python 3.11+**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

---

##  Notebook Workflow

| Step | Description |
|:---|:---|
| 1. Load Data | Import Titanic dataset and explore basic structure |
| 2. Visualize Missing Data | Use heatmaps to identify missing values |
| 3. Clean the Data | Impute missing values, drop high-missing columns |
| 4. Encode Categorical Variables | Label Encoding and One-Hot Encoding |
| 5. Scale Features | Apply RobustScaler to numerical features |
| 6. Outlier Detection | Use Isolation Forest to remove outliers |
| 7. Save Cleaned Dataset | Export final dataset |
| 8. Compare Raw vs Cleaned | Showcase improvements |
| 9. Correlation Analysis | Plot feature correlation matrix |

---

##  Key Techniques Used

- **Missing Value Handling**  
  - Median imputation for numerical columns
  - Mode imputation for categorical columns

- **Feature Encoding**  
  - Label Encoding for binary categories (e.g., "Sex")
  - One-Hot Encoding for nominal categories (e.g., "Embarked")

- **Feature Scaling**  
  - RobustScaler to handle outliers during scaling

- **Outlier Detection**  
  - Isolation Forest algorithm to detect and remove extreme outliers

- **Feature Correlation Analysis**  
  - Only numerical features considered for correlation matrix

---

