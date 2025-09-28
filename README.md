# Kaiburr-Task5
Consumer Complaint Text Classification

Overview

This project performs multi-class classification on consumer complaint texts.
The complaints are mapped into four categories:

0 → Credit Reporting

1 → Debt Collection

2 → Consumer Loan

3 → Mortgage


The workflow includes text cleaning, vectorization, model training, evaluation, and predictions.


---

📂 Dataset

Input Feature: Consumer complaint narrative (text)

Target Label: Product (mapped into 4 categories)

Source: output_random.csv (pre-cleaned dataset)

---

Steps Performed

1. Data Cleaning

Lowercasing

Removing digits, punctuation, and extra spaces



2. Vectorization

Bag of Words (CountVectorizer)

Limited to top 4000 features



3. Model Training

Random Forest

Linear SVM

Gradient Boosting



4. Model Evaluation

Accuracy

Classification Report (Precision, Recall, F1)

Confusion Matrix



5. Sample Predictions

Random complaints checked with predicted vs true labels

---

📊 Results

Model	Accuracy

Random Forest	~0.93
Linear SVM	~0.92
Gradient Boosting	~0.90


✅ Best Model: Random Forest


---

📈 Confusion Matrix (Best Model)

The confusion matrix shows model performance across the four complaint categories.

(Generated using Seaborn heatmap in code)

---

Submission Notes

Code in: Text_Classification.ipynb

Includes: Cleaning → Vectorization → Training → Evaluation → Predictions

Libraries used: pandas, sklearn, seaborn, matplotlib 
