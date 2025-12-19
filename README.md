Flight Delay Prediction using Machine Learning

Project Overview
Flight delays significantly impact passenger experience and airline operations.  
This project aims to **predict flight delays before departure** using historical flight data from **2018–2024** and machine learning techniques.

The model uses **only pre-departure information**, ensuring realistic and leakage-free predictions suitable for real-world deployment.

---

Objectives
- Analyze historical flight delay patterns
- Perform data cleaning and preprocessing
- Engineer meaningful features for prediction
- Train and compare multiple machine learning models
- Tune hyperparameters for optimal performance
- Evaluate the final model using robust metrics
- Save the trained model for deployment

---

Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Pickle / Joblib
- Jupyter Notebook
- VS Code

---

Dataset
- Time period: **2018–2024**
- Real-world flight operation data
- Key features:
  - Airline
  - Origin & Destination
  - Distance
  - Departure time
  - Day, month, and route information

⚠️ Post-departure features were removed to avoid data leakage.

---

Project Workflow

Data Loading & Cleaning
- Removed columns with excessive missing values
- Dropped post-departure and leakage-prone features
- Standardized column formats
- Generated a clean dataset for analysis

Exploratory Data Analysis (EDA)
- Delay vs non-delay distribution
- Airline-wise and route-wise delay trends
- Time-based delay analysis (hour, day, month)
- Visualization of key insights

Feature Engineering
- Route and state-route creation
- Departure time bucketing (morning, afternoon, evening, night)
- Distance grouping
- Categorical and numerical feature preparation

Model Training
- Logistic Regression (baseline)
- Random Forest
- Gradient Boosting
- Pipeline-based preprocessing and training

Model Tuning
- Hyperparameter optimization
- F1-score focused evaluation (imbalanced data)
- Best model selection

Final Evaluation
- Confusion matrix
- Classification report
- ROC-AUC analysis
- Feature importance interpretation

---

Results
- Achieved strong predictive performance on imbalanced data
- Identified major factors contributing to flight delays
- Final trained model saved for deployment and inference

---

## 📁 Repository Structure
