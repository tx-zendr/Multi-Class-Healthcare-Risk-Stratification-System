# Multi-Class-Healthcare-Risk-Stratification-System
This project implements an end-to-end supervised machine learning system to predict a patient’s clinical risk level (Normal, Low, Medium, High) based on vital signs and clinical observations.
🏥 Multi-Class Healthcare Risk Stratification System
📌 Project Overview

This project implements an end-to-end supervised machine learning system to predict a patient’s clinical risk level (Normal, Low, Medium, High) based on vital signs and clinical observations.

The goal is to support early risk identification by accurately classifying patients into appropriate risk categories while prioritizing the detection of high-risk cases, where false negatives can have serious consequences.

🎯 Problem Statement

Healthcare datasets often involve imbalanced, structured clinical data where misclassification of severe cases is costly.
This project addresses that challenge by:

Framing the problem as a multi-class classification task

Preserving clinical severity ordering using ordinal encoding

Comparing classical ML, ensemble methods, and deep learning

Focusing on recall and F1-score, not just accuracy

Explaining model decisions using model interpretability techniques

🧠 Key Features

Multi-class risk prediction: Normal / Low / Medium / High

Clinically meaningful ordinal encoding

End-to-end ML pipeline (preprocessing → modeling → evaluation)

Comparison of multiple supervised algorithms

Deep learning model with regularization

Emphasis on healthcare-appropriate evaluation metrics

Explainability for transparent decision-making

🛠️ Tech Stack

Programming Language: Python

Libraries:

NumPy, Pandas

Scikit-learn

XGBoost

TensorFlow / Keras

SHAP (Explainable AI)

Visualization: Matplotlib, Seaborn

📊 Algorithms Implemented

Multinomial Logistic Regression (baseline, interpretable)

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

Artificial Neural Network (ANN)

Each model is evaluated and compared using clinically relevant metrics.

📈 Evaluation Strategy

Rather than relying solely on accuracy, this project emphasizes:

Recall (especially for High-Risk patients)

Macro F1-Score

Confusion Matrix

Model comparison across multiple metrics

This approach aligns with real-world healthcare decision-making, where minimizing false negatives is critical.

🔍 Model Interpretability

To improve transparency and trust:

Feature importance and SHAP values are used to explain predictions

Key clinical factors influencing risk classification are analyzed

Enables answering “why” a prediction was made, not just “what”

📂 Project Structure
healthcare-risk-stratification/
│── data/
│── notebooks/
│── src/
│   ├── preprocessing.py
│   ├── train_ml.py
│   ├── train_dl.py
│   ├── evaluate.py
│── models/
│── README.md

🚀 Key Learnings

Importance of domain-aware feature encoding

Trade-offs between interpretability and performance

Handling class imbalance in healthcare data

Comparing classical ML vs deep learning on tabular data

Applying explainable AI in sensitive domains

📌 Future Improvements

Bias and fairness analysis across demographic groups

Calibration of predicted risk probabilities

Deployment as a lightweight web application

Integration with real-time clinical monitoring systems

👨‍💻 Author

Developed as a resume-defining machine learning project focused on real-world healthcare challenges and industry-level ML practices.
