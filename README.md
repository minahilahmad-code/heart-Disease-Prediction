Heart Disease Prediction Using Machine Learning
📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction and diagnosis can significantly reduce mortality rates.

This project uses Machine Learning techniques to predict whether a patient has heart disease based on medical attributes.

The model is trained using a structured heart disease dataset and evaluated using performance metrics such as Accuracy, Confusion Matrix, and ROC-AUC Score.

🎯 Objectives

To build a machine learning model that predicts heart disease.

To preprocess and clean real-world medical data.

To train a classification model using Random Forest.

To evaluate the model using classification metrics.

To visualize model performance using ROC Curve and Confusion Matrix.

📂 Dataset Description

The dataset contains medical attributes such as:

Age

Sex

Chest pain type

Resting blood pressure

Cholesterol level

Fasting blood sugar

Maximum heart rate achieved

Exercise-induced angina

ST depression

Number of major vessels

Thalassemia

Target (0 = No disease, 1 = Disease)

The target variable indicates whether the patient has heart disease.

⚙️ Technologies & Libraries Used

Python

Pandas (Data manipulation)

NumPy (Numerical operations)

Matplotlib (Data visualization)

Seaborn (Advanced visualization)

Scikit-learn (Machine Learning models)

Google Colab (Development environment)

🧠 Machine Learning Model Used
🌳 Random Forest Classifier

Random Forest is an ensemble learning method that:

Combines multiple decision trees

Reduces overfitting

Improves prediction accuracy

Works well with structured medical datasets

Model Parameters:

n_estimators = 200

random_state = 42

🔄 Methodology
1️⃣ Data Loading

Dataset uploaded in Google Colab.

Loaded using Pandas.

2️⃣ Data Preprocessing

Missing values handled using mean imputation.

Features separated from target variable.

Data split into training (80%) and testing (20%).

Feature scaling applied using StandardScaler.

3️⃣ Model Training

Random Forest model trained on scaled training data.

4️⃣ Model Evaluation

Performance evaluated using:

Accuracy Score

Confusion Matrix

ROC Curve

ROC-AUC Score

📊 Evaluation Metrics
✅ Accuracy

Measures the percentage of correct predictions.

📌 Confusion Matrix

Shows:

True Positives

True Negatives

False Positives

False Negatives

📈 ROC Curve

Shows trade-off between:

True Positive Rate

False Positive Rate

🔥 ROC-AUC Score

Measures overall model performance (closer to 1 = better model).

📷 Visual Outputs

The project generates:

Confusion Matrix Heatmap

ROC Curve Plot

These visualizations help in understanding model performance clearly.

🚀 How to Run the Project (Google Colab)

Open Google Colab.

Upload the notebook.

Run the code.

Upload heart.csv when prompted.

View model accuracy and visual results.

📌 Future Improvements

Compare multiple models (Logistic Regression, SVM, XGBoost).

Perform hyperparameter tuning.

Deploy model as a web app (Streamlit/Flask).

Use cross-validation.

Add feature importance visualization.

📈 Conclusion

The Random Forest classifier successfully predicts heart disease using medical parameters with strong performance metrics.

This project demonstrates how machine learning can assist in early detection of heart disease, potentially helping healthcare professionals make better decisions.
