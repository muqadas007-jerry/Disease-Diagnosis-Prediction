

# 🩺 Disease Diagnosis Prediction - Heart Disease Classifier

This project is a machine learning solution for **early diagnosis of heart disease** based on patient medical data. It includes exploratory data analysis, feature selection, model training, evaluation, and actionable insights for healthcare professionals.

---

## 📁 Dataset

- **Source**: Heart Disease Dataset (`heart.csv`)
- **Target Variable**: `target` (1 = presence of disease, 0 = absence)

---

## 🧠 Objectives

- Explore and visualize relationships between medical features and heart disease.
- Build and compare predictive models: Gradient Boosting, SVM, and Neural Network.
- Evaluate models using F1 Score and AUC-ROC curves.
- Provide insights for healthcare professionals to support early intervention.

---

## ⚙️ Step-by-Step Workflow

1. **Load & Explore Data**
   - Visualized feature correlation using heatmaps
2. **Feature Selection & Scaling**
   - Selected top 10 features using `SelectKBest`
   - Applied `StandardScaler` for normalization
3. **Model Training**
   - Trained 3 classifiers:
     - Gradient Boosting
     - Support Vector Machine (SVM)
     - Neural Network (MLPClassifier)
4. **Evaluation**
   - Assessed performance using:
     - F1 Score
     - AUC-ROC Curve
   - Plotted ROC curves for visual comparison
5. **Outcome**
   - Neural Network performed best with ~96% accuracy
   - Model helps identify high-risk patients for early diagnosis

---

## 📊 ROC Curve Sample

![ROC Curve](insert-your-roc-image-here.png)

*(Replace with actual image if needed)*

---

## ✅ Results Summary

| Model              | F1 Score | AUC-ROC | Accuracy |
|-------------------|----------|---------|----------|
| Gradient Boosting | ~0.94    | ~0.96   | 93.7%    |
| SVM               | ~0.88    | ~0.91   | 87.8%    |
| Neural Network    | ~0.96    | ~0.98   | 96.1%    |

---



Let me know if you want help uploading an image or linking to a notebook version!
