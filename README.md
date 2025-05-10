# ML_Trained_Model_for_Diabetes

# 🩺 Diabetes Prediction Model using TensorFlow

This project involves building and training a machine learning model to predict whether a patient is likely to have diabetes, based on medical features. The model is built using **TensorFlow** and trained on a diabetes dataset.

---

## 📊 Dataset

The dataset includes features such as:

- Number of Pregnancies
- Glucose Level
- Blood Pressure
- Skin Thickness
- Insulin Level
- BMI
- Diabetes Pedigree Function
- Age

Each row in the dataset is labeled with a binary outcome:
- `0`: Non-diabetic
- `1`: Diabetic

---

## 🧠 Model

The model is a **binary classifier** built using **TensorFlow/Keras**. It was trained with a train-test split and evaluated using a confusion matrix and classification report.

### ✅ Model Performance:

| Metric        | Score |
|---------------|-------|
| **Accuracy**  | 0.76  |
| **Precision** | 0.81 (Class 0), 0.67 (Class 1) |
| **Recall**    | 0.82 (Class 0), 0.65 (Class 1) |
| **F1-score**  | 0.81 (Class 0), 0.66 (Class 1) |

> 🔍 Model performs better at identifying non-diabetic patients. Further tuning or class-balancing techniques may improve diabetic class performance.

---

## 🧪 Confusion Matrix
[[81 18]
[19 36]]
