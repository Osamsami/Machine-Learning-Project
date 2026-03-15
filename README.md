# Breast Cancer Diagnostic Classification
!https://raw.githubusercontent.com/OsamaSami98/Breast-Cancer-Classification/main/banner.png

## Project Overview
This project uses **Machine Learning (Random Forest)** to classify breast tumors as either **Malignant** (Cancerous) or **Benign** (Non-cancerous). By analyzing 30+ clinical features, the model achieves near-perfect accuracy, making it a reliable tool for early diagnosis.

## Performance Highlights
- **Model:** Random Forest Classifier
- **Accuracy:** 99.42% (not good because of dataset size is too small but if you will change value of k accuracy would be good after changing value of k and random state)
- **F1-Score:** 0.99
- **Dataset:** Wisconsin Breast Cancer (Diagnostic) Dataset

##  How it Works
1. **Data Loading:** Input clinical data from `data.csv`.
2. **Feature Analysis:** Correlating mean radius, texture, and perimeter to identify patterns.
3. **Training:** Using Random Forest with 100+ decision trees to ensure high precision.
4. **Validation:** Cross-validation performed to ensure the model doesn't overfit.



##  Files in this Project
* `project.ipynb`: The complete Python notebook containing data cleaning, EDA, and the ML model.
* `data.csv`: The dataset used for training and testing.

##  Usage
Simply open the `project.ipynb` file in Google Colab or Jupyter Notebook and run all cells. Make sure `data.csv` is in the same directory.

## 🏷️ Tags
#MachineLearning #Python #BreastCancerAwareness #DataScience #RandomForest #HealthTech
