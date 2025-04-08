# Driver Prediction with Machine Learning

The integration of **advanced sensors** and **machine learning techniques** is revolutionizing vehicle automation and safety. This project focuses on **distinguishing driving behaviors** to support applications like **fleet management** and **safety monitoring**.

## Project Overview

Data from **nine scenarios** across **three drivers** and **vehicles** are processed through a **two-phase approach**:

1. **Feature Transformation & Reduction**:  
   The first phase involves using a **sliding window technique** for feature transformation and **Principal Component Analysis (PCA)** for feature reduction, addressing high dimensionality.

2. **Model Evaluation**:  
   The second phase implements and evaluates classification models, including:
   - **Logistic Regression**
   - **Random Forests**
   - **Support Vector Machines (SVM)**
   - **XGBoost**

   Among these, **Logistic Regression** and **SVM** deliver the best **accuracy** and **generalization** across unseen data.

The findings emphasize the significance of **feature engineering** and **evaluation strategies** in improving driver classification performance, with particular focus on **feature reduction** and **robust evaluation methods**.

## Report & Code Structure

- **Report**:  
   You can find the detailed report in the **"Report"** file.

- **Code**:  
   The code is located in the **"final_code"** folder:
   - **data_formatting.ipynb**: Data preprocessing notebook.
   - **hyperparameters_tuning.ipynb**: Implements standard cross-validation for hyperparameter tuning.
   - **hyperparameters_tuning_LOCO.ipynb**: Implements our personalized method for hyperparameter evaluation.
   - **training_testing.ipynb**: Final model training and testing on unseen data.
 
- **Dataset**:  
  All the data we used can be found in the **"archive"** folder, which contains data for each of the **nine Scenarios**.

