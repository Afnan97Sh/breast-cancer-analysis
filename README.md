Homework – Breast Cancer Wisconsin Dataset Analysis
📌 Objective
This assignment analyzes the Breast Cancer Wisconsin dataset with two main goals:
Data preprocessing and dimensionality reduction
Machine learning model training and evaluation
📂 Project Files
data.csv – Dataset used for analysis
HW1.ipynb – Jupyter Notebook with preprocessing and ML models
README.md – Documentation and instructions
⚙️ Workflow
Part 1: Data Preprocessing
Load the Dataset
Read data.csv using pandas.
Check & Handle Missing Values
Detect missing entries and preprocess accordingly.
Normalize the Data
Apply Min-Max scaling (manual implementation if needed).
Dimensionality Reduction (PCA)
Reduce features while retaining ~95% variance.
Visualization
Scatter plots of PCA components
Correlation heatmaps
Part 2: Machine Learning Models
Implemented from scratch (without scikit-learn or tensorflow):
K-Nearest Neighbors (KNN)
Artificial Neural Network (ANN)
Random Forest
Decision Tree
Naïve Bayes
Evaluation Metrics:
Accuracy
Confusion Matrix
Comparative analysis of all models
📊 Results
Dataset cleaned, normalized, and reduced with PCA.
Multiple ML models implemented and tested.
Performance comparison highlights the most effective model for breast cancer classification.
🚀 Requirements
To run the notebook, install the following Python libraries:
pip install pandas numpy matplotlib seaborn
📜 Submission
Final deliverables:
data.csv (dataset)
HW1.ipynb (notebook with preprocessing + ML models)
README.md (this file)