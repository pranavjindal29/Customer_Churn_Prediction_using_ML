# Customer Churn Prediction Using Machine Learning

This project leverages machine learning to predict customer churn using a Telco customer dataset. By applying data preprocessing, exploratory analysis, and various machine learning models, the project provides insights into key factors influencing customer retention.

## Features
- **Data Preprocessing**: Handled missing values, encoded categorical features, and addressed class imbalance using SMOTE.
- **Exploratory Data Analysis (EDA)**: Visualized patterns and correlations to understand customer behavior.
- **Model Development**: Implemented machine learning algorithms (Logistic Regression, Random Forest, XGBoost) to predict churn.
- **Evaluation**: Assessed model performance using metrics like accuracy, precision, recall, and F1-score.

## Dataset
The project uses the **Telco Customer Churn** dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`), which contains customer demographics, account information, and churn labels.

## Key Steps
1. Load and preprocess the dataset.
2. Perform EDA to explore feature distributions and relationships.
3. Train machine learning models and optimize them for better accuracy.
4. Evaluate model performance and save the best model using `pickle`.

## Libraries Used
- **Data Manipulation**: `numpy`, `pandas`
- **Visualization**: `matplotlib`, `seaborn`
- **Machine Learning**: `scikit-learn`, `xgboost`
- **Data Balancing**: `imbalanced-learn (SMOTE)`
- **Utilities**: `pickle` for saving the model


## How to Use
1. Clone the repository:
   git clone <repository-url>
2. Install dependencies:
   pip install -r requirements.txt
3. Run the Jupyter Notebook:
   jupyter notebook Customer_Churn_Prediction_using_ML.ipynb
   
## Results
- The trained models achieved high predictive accuracy, effectively identifying potential customer churn.
- Balanced datasets significantly improved performance for minority class predictions.
