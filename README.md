# Heart Disease Feature Selection and Classification

This project aims to analyze heart disease datasets using feature selection methods—**Lasso** and **Wrapper Methods**—to identify the most significant features and classify the presence of heart disease.

---

## Dataset Description

The datasets used in this project come from four databases:
1. **Cleveland**
2. **Hungary**
3. **Switzerland**
4. **VA Long Beach**

### Dataset Characteristics
- **Type**: Multivariate
- **Subject Area**: Health and Medicine
- **Instances**: 303
- **Features**: 13 (subset of 76 attributes)

The "goal" field refers to the presence of heart disease in the patient:
- **0**: No heart disease
- **1, 2, 3, 4**: Different degrees of heart disease presence.

The primary focus is on the Cleveland database, which is widely used in machine learning research for binary classification:
- **Absence (0)** vs. **Presence (1, 2, 3, 4)** of heart disease.

---

## Objectives

1. **Feature Selection**:
   - Use **Lasso Regression** to identify significant features.
   - Apply **Wrapper Methods** (Recursive Feature Elimination) for feature selection.

2. **Classification**:
   - Build classification models based on selected features to predict heart disease presence.

---

## Methods

### **1. Lasso Regression**
- **Purpose**: Identifies important features by shrinking less significant feature coefficients to zero.
- **Visualization**: Feature importance chart.

### **2. Wrapper Methods**
- **Purpose**: Select features by recursively training models on subsets and evaluating performance.
- **Visualization**: Selected features chart.

---

## Visualizations

### 1. Lasso Regression Feature Importance
![Lasso Feature Importance](images/lasso_feature_importance.png)

### 2. Wrapper Methods Feature Selection
![Wrapper Feature Selection](images/wrapper_feature_selection.png)

---

## How to Run

### **1. Prerequisites**
- Python 3.7 or higher
- Jupyter Notebook
- Dependencies listed in `requirements.txt`

### **2. Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Heart-Disease-Feature-Selection-and-Classification.git
