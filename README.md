💳 Credit Card Fraud Detection
🧠 Machine Learning Model to Detect Fraudulent Transactions
This project uses machine learning techniques to build a robust model that detects fraudulent credit card transactions using the popular Kaggle dataset.

⚠️ Dataset Not Included
-----------------------
The dataset `creditcard.csv` (143MB) is too large to be uploaded to GitHub.

Please download it manually from Kaggle:  
🔗 [Kaggle Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

Place it in the root directory of this project after cloning.

📁 Source

🛠️ Technologies Used
Python

Jupyter Notebook

pandas, numpy, matplotlib, seaborn

scikit-learn

imbalanced-learn (SMOTE)

joblib (for model saving)

🚀 How It Works
1. Preprocessing
Removed irrelevant features (Time)

Scaled Amount using StandardScaler

Handled duplicates

Addressed class imbalance using:

Undersampling

Oversampling with SMOTE

2. Model Training
Trained three models:

Logistic Regression

Decision Tree

Random Forest (best performing)

3. Evaluation Metrics
Accuracy

Precision

Recall

F1 Score

Bar plot comparison for model performance

4. Prediction
Final model saved using joblib

Accepts user input for new transaction data

Outputs: "Fraudulent" or "Not Fraudulent"

📊 Results
Random Forest gave the best performance:

✅ High precision (fewer false positives)

✅ High recall (catches most frauds)

