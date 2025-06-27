# AI-Assignment-Week-5

🏥 Hospital Readmission Risk Predictor
This project leverages machine learning to predict whether a patient will be readmitted within 30 days of discharge. By simulating patient data and applying logistic regression, the goal is to help healthcare providers identify at-risk patients early and intervene proactively.

🎯 Project Objectives
Predict 30-day hospital readmissions using structured patient data

Improve care decision-making with model-backed risk insights

Demonstrate end-to-end AI model development using ethical, interpretable methods

🧰 Tools, Libraries & Frameworks Used
📊 Data Handling & Visualization
Pandas – For dataframes and preprocessing

NumPy – For numerical operations and randomization

Matplotlib – For performance visualization and plotting

Seaborn – For styled charts and heatmaps

🤖 Machine Learning
Scikit-learn

LogisticRegression – Core algorithm used for binary classification

train_test_split – To split data into train, validation and test sets

StandardScaler – For feature normalization

confusion_matrix, precision_score, recall_score, accuracy_score – For model evaluation

💻 Development Environment
Google Colab – For interactive, shareable development

(Optional) Streamlit – Can be used for creating a simple clinical dashboard (not yet implemented)

🔄 Workflow Overview
text
1. Problem Definition
2. Data Simulation (synthetic patient records)
3. Data Preprocessing (encoding, scaling, splitting)
4. Model Training (Logistic Regression with class weights)
5. Evaluation (Confusion Matrix, Accuracy, Precision, Recall)
6. Visualization (Heatmaps + Bar Charts)
7. Ethical Review (bias, privacy, fairness)
📈 Results Summary
Initial model failed to identify readmitted patients (high accuracy but recall = 0)

After handling class imbalance with class_weight='balanced', recall increased to 71%, catching most readmission cases

Visualizations showed clear improvements in the confusion matrix and score distribution

✅ Key Takeaways
Class imbalance can mislead accuracy; recall is crucial in healthcare risk modeling

Logistic regression offers interpretability and speed, making it a solid choice for clinical scenarios

Ethical considerations, especially fairness and transparency, are as important as technical performance
