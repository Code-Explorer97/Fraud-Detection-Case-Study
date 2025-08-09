# Fraud Detection Case Study

This project predicts fraudulent financial transactions using machine learning.  
The dataset is based on the PaySim simulation, which models mobile money transactions and labels them as legitimate or fraudulent.

## 📊 Project Overview
- **Goal**: Detect fraudulent transactions proactively.
- **Dataset**: ~6.3 million rows, 10 columns (transaction details, balances, labels).
- **Target Variable**: `isFraud` (1 = Fraud, 0 = Not Fraud)

## 🛠 Features of the Project
1. **Data Cleaning**
   - Handled missing values
   - Treated outliers
   - Checked and reduced multi-collinearity using correlation heatmap
2. **Feature Engineering**
   - Encoded categorical variables
   - Scaled numerical features
3. **Model Building**
   - Applied SMOTE to handle class imbalance
   - Trained a Random Forest Classifier
4. **Model Evaluation**
   - Precision, Recall, F1-score
   - ROC Curve and AUC Score
5. **Insights**
   - Key fraud indicators: transaction amount, unusual balances, transaction type.

## 📈 Results
- Strong recall on fraud detection (important for minimizing missed frauds)
- ROC AUC Score: ~0.94 (on sample dataset)

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- scikit-learn
- imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

## 📂 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/fraud-detection-case-study.git
