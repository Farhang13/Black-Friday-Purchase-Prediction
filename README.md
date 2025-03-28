# Black-Friday-Purchase-Prediction

## 🛍️ Black Friday Purchase Prediction – Optimized ML Pipeline

This project analyzes and builds a machine learning model to predict customer purchase behavior based on demographic and transactional data from a Black Friday retail dataset.

### 📁 Dataset
- `train.csv`: Historical customer data with purchase amounts.
- `test.csv`: Similar structure without the target variable (`Purchase`).

### 🔍 Features Engineered
- `Age_num`: Mapped age brackets to numerical scale.
- `Stay_In_Current_City_Years_num`: Converted duration to numeric.
- `Purchase_to_Occupation_Avg`: Ratio of individual purchase to average occupation-level spending.
- One-hot encoded city categories.

### 📊 Exploratory Data Analysis
- Heatmap of missing values.
- Distribution plot of purchase values.
- Correlation heatmap of numeric features.
- Boxplots comparing purchases by gender, marital status, and occupation.

### 🛠️ Modeling
- Model: `RandomForestRegressor` with `RandomizedSearchCV` for hyperparameter tuning.
- Scaling: StandardScaler used on numeric features.
- Split: 80/20 train-validation split.
- Metrics: RMSE and R² on validation set.

### 🚀 Results
- Outputs top feature importances.
- Generates predictions for the test dataset.

### 📦 Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn



