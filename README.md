📊 Telco Customer Churn Prediction

A machine learning project that predicts whether a customer will churn (leave the service) based on demographic and service usage data. This project uses data preprocessing, feature encoding, and an XGBoost Classifier to achieve high prediction accuracy.

🚀 Project Overview

Customer churn is a critical problem in the telecom industry. Retaining existing customers is more cost-effective than acquiring new ones.

This project aims to:

Analyze customer behavior
Identify churn patterns
Build a predictive model to forecast churn
🧠 Machine Learning Workflow
1. Data Collection
Dataset: Telco Customer Churn Dataset
Loaded using pandas
2. Data Preprocessing
Removed unnecessary columns (customerID)
Handled missing values
Converted categorical data using Label Encoding
3. Feature Engineering
Encoded categorical features
Balanced dataset using SMOTE (Synthetic Minority Oversampling Technique)
4. Model Training
Algorithm: XGBoost Classifier
Train-test split applied
5. Model Evaluation
Accuracy Score
Confusion Matrix
Classification Report
6. Model Saving
Model saved using joblib
🛠️ Tech Stack
Python
NumPy
Pandas
Matplotlib & Seaborn
Scikit-learn
XGBoost
Imbalanced-learn (SMOTE)
Joblib
📂 Project Structure
├── Arnab_Halder.ipynb   # Main Jupyter Notebook
├── Telco-Customer-Churn.csv  # Dataset
├── model.pkl           # Saved trained model
└── README.md           # Project documentation
⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/your-username/telco-churn-prediction.git
cd telco-churn-prediction
2. Install dependencies
pip install numpy pandas matplotlib seaborn scikit-learn xgboost imbalanced-learn joblib
3. Run the notebook
jupyter notebook
📈 Model Performance
High accuracy achieved using XGBoost
Improved performance with SMOTE balancing
Effective classification of churn vs non-churn customers
📊 Key Insights
Contract type and tenure strongly influence churn
Customers with monthly contracts are more likely to churn
Higher monthly charges increase churn probability
🔮 Future Improvements
Hyperparameter tuning
Deploy model using Flask / Streamlit
Add real-time prediction UI
Use deep learning models
🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

📬 Contact

Arnab Halder
📧 Email:halderarnab29@gmail.com

