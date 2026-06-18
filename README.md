# 🤖 Model

This project uses **Logistic Regression**, a supervised machine learning algorithm designed for binary classification tasks. The model predicts whether a passenger survived the Titanic disaster (`1`) or did not survive (`0`) based on features such as passenger class, gender, age, family information, fare, and embarkation port.

# ⚙️ Process Performed

* Loaded and explored the Titanic dataset.
* Handled missing values in the `Age` and `Embarked` columns.
* Removed irrelevant features (`PassengerId`, `Name`, `Ticket`, and `Cabin`).
* Encoded categorical variables into numerical format.
* Performed exploratory data analysis (EDA) using visualizations.
* Split the dataset into training and testing sets.
* Trained a Logistic Regression model using scikit-learn.
* Evaluated the model using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix.

# ✅ Conclusion

The Logistic Regression model achieved an accuracy of approximately **74%** on the test dataset, providing a solid baseline for Titanic survival prediction. This project demonstrates the complete machine learning workflow, including data preprocessing, feature engineering, model training, and evaluation, while reinforcing the practical application of Logistic Regression for binary classification problems.
