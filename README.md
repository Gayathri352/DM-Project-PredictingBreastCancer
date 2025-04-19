# Breast Cancer Detection Using Machine Learning

This project applies supervised machine learning techniques to accurately classify tumors as benign or malignant using the Breast Cancer Wisconsin dataset.

---

## Objective

To build, evaluate, and compare multiple classification algorithms on medical diagnostic data and identify the best model for predicting breast cancer.

---

## Dataset

- Source: `sklearn.datasets.load_breast_cancer()`
- Samples: 569
- Features: 30 numeric attributes (mean, standard error, worst of various cell properties)
- Target: 0 = Malignant, 1 = Benign

---

## Techniques Used

- Data Preprocessing with `StandardScaler`
- Dimensionality Reduction with `PCA`
- Class Imbalance Handling with `SMOTE`
- Classification Algorithms:
  - Decision Tree
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Neural Network (MLPClassifier)
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, AUC

---

## Project Structure

DM-Project-PredictingBreastCancer/ ├── Predicting_breasts_cancer.ipynb # Main notebook ├── Predicting_breasts_cancer_report.docx # Report with analysis and results ├── viz_images/ # Visualization images └── README.md # Project overview


---

## How to Run

1. Clone this repository or download as ZIP
2. Open `Predicting_breasts_cancer.ipynb` in:
   - Jupyter Notebook, OR  
   - [Google Colab](https://colab.research.google.com)
3. Run cells sequentially to:
   - Preprocess data
   - Train & evaluate models
   - Visualize performance

---

## Result Summary (Example)

| Model         | Accuracy | Precision | Recall | F1-Score | AUC   |
|---------------|----------|-----------|--------|----------|--------|
| Decision Tree | 94.7%    | 94.3%     | 95.2%  | 94.7%    | 0.97   |
| SVM           | 97.3%    | 97.5%     | 97.1%  | 97.3%    | 0.99   |
| KNN           | 96.5%    | 96.8%     | 96.2%  | 96.5%    | 0.98   |
| MLP           | 98.2%    | 98.1%     | 98.3%  | 98.2%    | 0.99   |

> *(Replace these with your actual results if different)*

---

## Technologies

- Python 3
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- imbalanced-learn (SMOTE)

---

## Author

**Sai Gayathri Makineni**  
Graduate Student – M.S. Computer Science  
University of North Texas  
📧 saigayathri18@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/sai-gayathri-makineni)

---

## Disclaimer

This project is for educational purposes only and is **not intended for real-world medical diagnosis**.

---
