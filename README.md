🏡 House Price Prediction using Regression Models
📌 Project Overview
This project predicts house prices using machine learning regression models trained on a cleaned and preprocessed dataset. It covers the entire ML pipeline: data analysis, feature engineering, model training, evaluation, and comparison.

📂 Dataset Information
Dataset Name: House Prices
Source: Kaggle
Format: CSV (house_prices.csv)
Target Variable: price (House price)

🚀 Tech Stack
Python
Libraries:
Data Handling: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Modeling: Scikit-Learn
Notebook Environment: Visual Studio Code

💡 Models Used
Linear Regression
Ridge Regression
Random Forest Regressor

📊 Evaluation Metrics
Each model was evaluated using:

Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score

📉 Visualizations comparing model performance and error distributions are included in the notebook.

📈 Insights & Observations
Random Forest achieved the best performance with an R² score ≈ 0.83.
Linear and Ridge Regression performed reasonably but underfit compared to ensemble methods.
Outliers and skewed features were identified using distribution and box plots.
Feature importance analysis revealed key predictors for house prices.

🛠️ How to Use
Clone the repository
Open house_price_prediction.ipynb in Jupyter

Run all cells to:
Load and explore the data
Perform preprocessing and feature engineering
Train and evaluate regression models
Visualize predictions and insights

📂 Repository Structure
📦 house-price-prediction-data  
├── 📜 README.md  
├── 📜 house_price_prediction.ipynb  
├── 📂 data  
│   └── house_prices.csv  

🔮 Future Improvements
Hyperparameter tuning using GridSearchCV
Add regularization variants like Lasso and ElasticNet
Build a deployment-ready app using Streamlit or Flask

📜 License
This project is licensed under the MIT License.

👩‍💻 Author
Apoorva Godishala
📧 apoorvagodishala77@gmail.com

