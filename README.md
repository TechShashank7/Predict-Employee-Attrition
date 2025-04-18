# 👩‍💼 Employee Attrition Prediction

This project uses machine learning to predict whether an employee is likely to leave an organization based on various attributes like job role, satisfaction level, income, and more. It helps HR departments take proactive steps to retain valuable employees.

---

## 📌 Problem Statement

Predict employee attrition using classification techniques based on historical HR data.

---

## 📊 Dataset

The dataset contains various features about employees, such as:

- Age
- Gender
- Job Role
- Monthly Income
- Distance from Home
- Job Satisfaction
- Years at Company
- OverTime
- ...and more.

Target column:
- `Attrition` — whether the employee left (`Yes`) or stayed (`No`)

---

## 🛠️ Methodology

1. **Data Preprocessing**
   - Label Encoding of categorical variables
   - Mapping target labels (Yes/No) to (1/0)
   - Standardization using `StandardScaler`

2. **Model Building**
   - Split the dataset into training and test sets (80-20 split)
   - Train a Logistic Regression model
   - Evaluate performance using accuracy, classification report, and confusion matrix

3. **Visualization**
   - Confusion Matrix
   - Correlation Heatmap

---

## 🧠 Model Used

- **Logistic Regression** — Simple and interpretable classification model ideal for binary outcomes like attrition.

---

## 📈 Results

- Accuracy Score: _~(depends on dataset)_
- Detailed classification report including precision, recall, and F1-score
- Visualizations to better understand model performance and feature relationships

---

## 📷 Visual Outputs

### Confusion Matrix  
![Confusion Matrix](path/to/confusion_matrix.png)
