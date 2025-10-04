# Homework – Breast Cancer Wisconsin Dataset Analysis

## 📌 Objective
Analyze the **Breast Cancer Wisconsin dataset** with two main goals:
1. **Data preprocessing & dimensionality reduction**
2. **Machine learning model training & evaluation**

---

## 📂 Project Files
- `data.csv` — Dataset used for analysis  
- `HW1.ipynb` — Jupyter Notebook with preprocessing and ML models  
- `README.md` — Documentation and instructions  

---

## ⚙️ Workflow

### Part 1: Data Preprocessing
- **Load the dataset:** read `data.csv` using `pandas`.
- **Check & handle missing values:** detect missing entries and preprocess accordingly.
- **Normalize the data:** apply **Min–Max scaling** (manual implementation; no scikit-learn).
- **Dimensionality reduction (PCA):** reduce features while retaining ~**95%** variance.
- **Visualization:**
  - Scatter plots of PCA components
  - Correlation heatmaps

### Part 2: Machine Learning Models
Implemented **from scratch** (no `scikit-learn`, no `tensorflow`):

- **K-Nearest Neighbors (KNN)**
- **Artificial Neural Network (ANN)**
- **Random Forest**
- **Decision Tree**
- **Naïve Bayes**

**Evaluation metrics:**
- Accuracy  
- Confusion Matrix  
- Comparative analysis across models  

---

## 📊 Results
- Dataset cleaned, normalized, and reduced with PCA.  
- Multiple ML models implemented and tested.  
- Performance comparison highlights the most effective model for breast cancer classification.  

---

## 🚀 Requirements
Install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn

▶️ How to Run
Open the notebook:
jupyter notebook HW1.ipynb
Run cells in order:
Preprocessing → PCA → Models → Evaluation
📜 Submission
data.csv — dataset
HW1.ipynb — notebook with preprocessing + ML models
README.md — this file




















```bash
pip install pandas numpy matplotlib seaborn
