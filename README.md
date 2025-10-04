# 🩺 Breast Cancer Prediction and Analysis (ML Pipeline)

This project builds a **machine learning pipeline** for breast cancer detection.  
It uses **Logistic Regression, SVM (RBF), and RandomForest** to classify tumors as:
- **M = Malignant (cancerous)**
- **B = Benign (non-cancerous)**

The pipeline also provides **visual analysis** of tumor features, making it easier for doctors, researchers, and students to understand the data.

---

## ✨ Features
- 📊 **Data support:** JSON, Excel (XLS/XLSX), CSV
- 🔍 **Feature analysis:**
  - Boxplots (Benign vs Malignant)
  - Histograms
  - Scatterplots
  - Correlation heatmap
  - RandomForest feature importance
- 🤖 **Models trained:**
  - Logistic Regression
  - SVM (RBF kernel)
  - RandomForest
- 📈 **Evaluation metrics:**
  - ROC, AUC
  - Confusion Matrix
  - Recall, Precision, F1
- 🧪 **Prediction mode:**
  - Predict on new patient files
  - Output includes probability of malignancy

---

## 📂 Repository Structure
- `notebooks/` → Jupyter/Colab notebook for interactive use
- `scripts/` → Core pipeline (`train_op`, `predict_op`)
- `sample_data/` → Example datasets for testing
- `artifacts/` → Auto-generated folder for models + plots
- `requirements.txt` → Dependencies

---

## 🚀 Quickstart (Colab)

1. Open the notebook:
   ```python
   from google.colab import files
   uploaded = files.upload()
