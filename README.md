# Diabetes Prediction Model

Machine learning project to predict whether a patient has diabetes based on
diagnostic medical attributes, using the **Pima Indians Diabetes Dataset**.

## 📚 Dataset

- Source: [Pima Indians Diabetes Database (Kaggle)](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- Binary classification: `Outcome` = 1 (diabetic) / 0 (non-diabetic)

## 🔧 Project Workflow

1. **Data Loading & Exploration**
   - Load dataset with Pandas
   - Inspect shape, missing values, summary statistics
2. **Data Preprocessing**
   - Feature/target split (X, y)
   - Train/test split (80/20)
3. **Model Training**
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - Decision Tree
   - K-Nearest Neighbors (KNN)
4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1 Score, ROC-AUC
   - ROC Curve comparison across all models
5. **Best Model Selection**
   - Compare all models on evaluation metrics
   - Save the best-performing model with `joblib`

## 🗂 Repository Structure

diabetes-prediction-model/
├── diabetes_prediction.ipynb # Main Colab notebook
├── diabetes_model.pkl # Saved best model (joblib)
├── README.md
└── ...

## 📊 Results

_(Will be filled in after model evaluation — accuracy/F1/ROC-AUC table and best model choice.)_

## 🛠 Tech Stack

- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab

## ✅ Status

🚧 In progress — assignment for AI/ML Engineering Bootcamp (Ostad).
