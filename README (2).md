# Assignment-1: Support Vector Machine on Breast Cancer Dataset  

This repository contains the implementation of **Support Vector Machine (SVM)** on the **Breast Cancer Wisconsin dataset**.  
The goal is to classify whether a tumor is **Malignant** (cancerous) or **Benign** (non-cancerous) using machine learning.  

---

## Problem Statement  
Breast cancer is one of the most common cancers worldwide.  
Accurate and early prediction can significantly help in treatment planning.  
In this project, we use the **Breast Cancer Wisconsin dataset** and train an **SVM classifier** to distinguish between malignant and benign tumors.  

---

## Dataset Details  
- **Source:** [Scikit-learn built-in dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset)  
- **Features:** 30 numeric features (mean, standard error, and "worst" values of cell nuclei in images)  
- **Target:**  
  - `0` → Malignant  
  - `1` → Benign  
- **Shape:**  
  - Samples: 569  
  - Features: 30  

---

## Steps Performed  
1. **Data Loading** – Loaded Breast Cancer dataset using `sklearn.datasets.load_breast_cancer`.  
2. **Exploration** – Viewed feature names, target distribution, and sample records.  
3. **Preprocessing** – Standardized the dataset using `StandardScaler`.  
4. **Visualization** –  
   - Histograms of features  
   - Pair plots for selected features  
   - Correlation heatmap  
   - Train vs Test accuracy comparison  
5. **Model Training** – Trained an **SVM classifier** with RBF kernel.  
6. **Evaluation** –  
   - Accuracy on training & test set  
   - Confusion Matrix  
   - Classification Report  

---

## Results  
<img width="657" height="345" alt="image" src="https://github.com/user-attachments/assets/9528b8ec-1648-4b85-b048-cef062691703" />

<img width="655" height="505" alt="image" src="https://github.com/user-attachments/assets/6493a89c-77eb-4782-b3a6-78b49e4cef40" />



---

## 🚀 Tech Stack  
- Python 🐍  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

