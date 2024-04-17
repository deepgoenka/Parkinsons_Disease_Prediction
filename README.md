# Parkinson's Disease Prediction

This repository contains a machine learning project that predicts Parkinson's disease based on various voice features.

### Libraries Used

- Pandas: For data manipulation and analysis.
- NumPy: For numerical computations.
- Scikit-learn: For machine learning algorithms and model evaluation.
- Matplotlib and Seaborn: For data visualization.
- Pickle: For saving and loading trained models.
- Warnings: For handling warning messages during execution.

### Data Preprocessing

- Imported the dataset and explored its structure and summary statistics.
- Visualized the distribution of labels (Healthy vs. Parkinson's) using a countplot.
- Checked for missing values in the dataset.

### Model Training and Evaluation

Three machine learning algorithms were employed for classification:

1. **Logistic Regression**: Achieved an accuracy of 90%.
2. **Support Vector Machine (SVM)**: Also achieved an accuracy of 90%.
3. **Random Forest**: Attained an accuracy of 80%.

Each model was trained, evaluated, and its performance visualized using a confusion matrix.

### Model Deployment

The SVM model was chosen for deployment due to its high accuracy. It was saved as `Parkinson's_Disease_Model.sav` using Pickle.
