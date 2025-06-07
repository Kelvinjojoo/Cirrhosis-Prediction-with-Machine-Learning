# 🧬 Cirrhosis Prediction with Machine Learning

This project uses machine learning to predict the **status of liver cirrhosis** in patients based on clinical data. Using Python and Jupyter Notebook, we explore preprocessing, training, and evaluating classification models on a real-world medical dataset.

---

## 📁 Dataset

The dataset used (`1A.tsv`) contains anonymized patient data including age, bilirubin levels, albumin, and more. The target variable is **`Stage`**, which indicates the progression stage of cirrhosis:

---

## 🧪 Features Used

Some of the key features in the dataset include:

- `Age`
- `Bilirubin`
- `Albumin`
- `Prothrombin`
- `Stage`
- `Sex`
- `Edema`
- ...and more

---

## 🛠️ Methods

We applied several machine learning steps:

1. **Data Cleaning & Preprocessing**
   - Delete identifier
   - Change data type 
   - Handling missing values
   - Handling Anomalies
   - Encoding categorical variables
   - Oversampling
   - Feature scaling

3. **Model Training**  
   - Random Forest
   - XGBoost

4. **Evaluation Metrics**  
   - Accuracy
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-Score)
   - Feature Importance

---

## 📈 Results

Our models were trained and evaluated, with the Tuning **Random Forest classifier** showing strong performance in classifying cirrhosis progression status.
