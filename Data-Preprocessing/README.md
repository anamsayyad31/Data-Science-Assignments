# 📁 Project Overview: Dataset Preprocessing Pipeline

This repository contains a complete preprocessing workflow for multiple real-world datasets, designed to support regression, classification, and clustering tasks.

## 📂 Folder Structure

- `Original_Datasets/`  
  Contains the original, unprocessed datasets in CSV & Excel format. These serve as the starting point for all preprocessing steps.

- `Preprocessing_Code/`  
  Includes Python scripts used to clean, transform, and encode the datasets. Each script is tailored to the specific structure and modeling goals of its corresponding dataset.

- `Preprocessed_Datasets/`  
  Stores the final, cleaned datasets after preprocessing. These files include standardized/normalized numeric features, encoded categorical variables, and engineered features ready for modeling.

## ⚙️ Preprocessing Highlights

- Outlier treatment using IQR-based Winsorization  
- Skewness correction via log or Box-Cox transformations  
- Feature scaling (Standardization or Normalization)  
- One-hot encoding for categorical variables  
- Removal of duplicates, missing values and zero-variance features  
- Dataset-specific feature engineering and target column handling

## 📌 Notes

- Target columns are preserved in original scale for regression tasks unless explicitly transformed.  
- Dummy variables are encoded as integers (0/1) for compatibility across ML frameworks.  
- All preprocessing decisions are documented within each script for reproducibility.

---

Feel free to explore each folder to understand the transformation logic and modeling readiness of each dataset.
