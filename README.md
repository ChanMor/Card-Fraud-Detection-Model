# Credit Card Fraud Detection Model

This project aims to build a machine learning model to detect fraudulent credit card transactions using a dataset of over 550,000 records. The model is developed in Python, leveraging several libraries to preprocess data, balance class distributions, and train predictive models.

### Key Features:
- **Data Preprocessing**: Preprocessed data by standardizing features using `StandardScaler`, and addressing class imbalance with SMOTE (Synthetic Minority Over-sampling Technique).
- **Machine Learning Models**:
  - **Logistic Regression**: A linear classifier used to predict fraudulent transactions.
  - **Random Forest**: An ensemble classifier that improves prediction accuracy by using multiple decision trees.
- **Model Evaluation**: Performance is evaluated using precision-recall curves and confusion matrices.
- **Metrics**:
  - **AUC-PR (Area Under the Precision-Recall Curve)**: Logistic Regression achieved an AUC-PR of 99.45%, while Random Forest achieved 99.99%.

### Technologies Used:
- **Python**
- **Pandas**: For data manipulation and preprocessing.
- **Scikit-Learn**: For building machine learning models and evaluating performance.
- **SMOTE**: To address class imbalance in the dataset.
- **Matplotlib & Seaborn**: For data visualization and confusion matrix plots.
