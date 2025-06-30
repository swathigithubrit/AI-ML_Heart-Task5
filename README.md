AI-ML_Heart-Task5
Predicting heart disease using Decision Tree and Random Forest classifiers with visualization and cross-validation in Python.

Heart Disease Prediction with Decision Tree and Random Forest

This project predicts the presence of heart disease in patients using Decision Tree and Random Forest classifiers. It uses a structured approach to train models, control overfitting, visualize decision trees, interpret feature importances, and validate results with cross-validation.

Heart Disease Prediction - It includes:
- Data preprocessing
- Training and visualizing a Decision Tree
- Controlling overfitting with limited depth
- Comparing with Random Forest accuracy
- Feature importance analysis
- Cross-validation for robust evaluation


Dataset 
The dataset contains patient medical attributes with a target label:

  Features:
  - age
  - sex
  - cp (chest pain type)
  - trestbps (resting blood pressure)
  - chol (serum cholesterol)
  - fbs (fasting blood sugar)
  - restecg (resting ECG results)
  - thalach (maximum heart rate achieved)
  - exang (exercise-induced angina)
  - oldpeak (ST depression)
  - slope (slope of the peak exercise ST segment)
  - ca (number of major vessels)
  - thal (thalassemia)
  
  - Target:
  - `target`: 0 = No Heart Disease, 1 = Heart Disease

---

Objectives

✅ Train a Decision Tree Classifier  
✅ Visualize the Decision Tree  
✅ Analyze overfitting and control tree depth  
✅ Train a Random Forest Classifier and compare accuracy  
✅ Interpret feature importances  
✅ Evaluate model with cross-validation  


Steps in the Notebook

1️⃣ Load and Inspect Data
- Load CSV file using pandas
- Check data structure and column names

2️⃣ Define Features and Target
- Separate input features (X) and target labels (y)

3️⃣ Train-Test Split
- Split data into training and testing sets (80/20)

4️⃣ Decision Tree Classifier
- Train a decision tree on the training set
- Predict on the test set
- Evaluate using accuracy and classification report
- Visualize the trained decision tree

5️⃣ Control Overfitting
- Train a shallower Decision Tree with `max_depth=3`
- Compare training and testing accuracy

6️⃣ Random Forest Classifier
- Train a Random Forest with 100 trees
- Predict and evaluate accuracy
- Compare with Decision Tree performance

7️⃣ Feature Importances
- Extract and visualize feature importances from Random Forest

8️⃣ Cross-Validation
- Perform 5-fold cross-validation to estimate model stability

---

Results

- Decision Tree accuracy (default): Varies, typically overfits
- Limited-depth Decision Tree accuracy: Improved generalization
- Random Forest accuracy: Typically highest accuracy and robustness
- Cross-validation mean accuracy: Reliable performance estimate
- Feature importance plots show most predictive medical features.

---

📌 Tools Used

- Python 3
- pandas
- numpy
- matplotlib
- scikit-learn

---
