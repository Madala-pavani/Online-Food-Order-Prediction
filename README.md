# Online-Food-Order-Prediction

# Overview

This project aims to predict whether a customer will order food online based on various demographic and behavioral factors. The dataset used includes attributes such as age, gender, occupation, income, and location details.

*Dataset*

The dataset contains 388 entries with 13 features:

Age (Numerical)

Gender (Categorical)

MaritalStatus (Categorical)

Occupation (Categorical)

MonthlyIncome (Categorical)

EducationalQualifications (Categorical)

FamilySize (Numerical)

Latitude (Numerical)

Longitude (Numerical)

PinCode (Numerical)

Output (Target Variable: Yes/No)

Feedback (Categorical)

Unnamed: 12 (Categorical)

*Data Preprocessing*

Checked for missing values and found none.

Converted categorical variables into numerical form using label encoding.

Identified correlations between numerical features using heatmaps.

*Machine Learning Models*

The following models were trained and evaluated on the dataset:

Naïve Bayes (GaussianNB)

Decision Tree Classifier

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

AdaBoost Classifier

*Model Evaluation*

Each model was assessed using:

Accuracy Score

Classification Report (Precision, Recall, F1-Score)

Confusion Matrix

*Key Findings*

Naïve Bayes: Achieved 100% accuracy.

Decision Tree Classifier: Achieved 100% accuracy.

KNN (k=5): Accuracy of 77.56%.

SVM: Accuracy of 76.28%, but had issues with precision.

AdaBoost Classifier: Achieved 100% accuracy.

*Dependencies*

Python 3.x

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

*Running the Code*

Ensure all dependencies are installed using:

pip install pandas numpy matplotlib seaborn scikit-learn

Run the Python script:

python online_food_order_prediction.py

Modify the dataset file path if necessary.

*Results Visualization*

Feature correlations were analyzed using heatmaps.

Confusion matrices were plotted to evaluate model performance.

Decision trees were visualized for better interpretability.

*Conclusion*

The Decision Tree and AdaBoost models performed the best with 100% accuracy, making them the ideal choices for predicting online food orders. Further improvements could be made by testing additional models or optimizing hyperparameters.
