
# Bean Classification using Machine Learning

This project focuses on building classification models to identify different types of beans based on their physical features. Multiple machine learning algorithms were tested and compared, including Logistic Regression, Random Forest, KNN, and SVC. After model evaluation, **Support Vector Classifier (SVC)** was found to be the best-performing model.

---

## Dataset Overview
The dataset contains measurements of various bean samples and their corresponding categories (classes).  
Each row represents one bean sample, and each column represents a numerical attribute such as shape, size, or texture.

**Target Variable:** Bean Type (7 Classes)

---

## Project Workflow
1. **Data Loading & Cleaning**
   - Handled missing values and ensured consistent formatting.
2. **Exploratory Data Analysis**
   - Visualized feature distributions and class balance.
   - Checked correlations to identify informative predictors.
3. **Feature Scaling**
   - Standardization applied to improve model training on distance-based models.
4. **Model Training & Comparison**
   - Trained multiple models and compared performance metrics.
5. **Hyperparameter Tuning**
   - Grid Search / Random Search applied (where relevant).
6. **Final Model Selection**
   - Selected SVC based on performance on test data.

---

## Best Model: Support Vector Classifier (SVC)

### Performance Metrics (Test Set)

| Metric        | Score  |
|---------------|--------|
| **Accuracy**  | 0.92   |
| **Macro F1**  | 0.936  |
| **Weighted F1** | 0.923 |

### Classification Report
