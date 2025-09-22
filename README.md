Boston Housing Price Prediction: Random Forest vs Linear Regression

This project explores the Boston Housing dataset to predict median home values. It compares the performance of Linear Regression and Random Forest Regression while showcasing essential data preprocessing, exploratory analysis, and outlier handling.

📂 Project Structure

Data Loading: Reads the dataset and applies meaningful column names.
Exploratory Data Analysis (EDA): Summary statistics, correlation heatmaps, and distribution plots.
Outlier Handling: Removes or caps extreme values using the IQR method and visualizes with boxplots.
Data Preprocessing: Feature scaling and encoding for model readiness.

Modeling:

Linear Regression (baseline model)
Random Forest Regressor (ensemble approach)
Evaluation: Compares models using R², MAE, and RMSE.

📊 Results

Linear Regression: Provides baseline interpretability but limited accuracy.
Random Forest: Handles non-linearities and achieves stronger predictive performance.

🔮 Future Work

Hyperparameter tuning with GridSearchCV
Feature engineering to capture more predictive patterns
Cross-validation for robust evaluation

🏷️ License

This project is released under the MIT License.
