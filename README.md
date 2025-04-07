# Supply-Chain-Analytics

**Project Overview**

This project aims to predict whether a product will go on backorder using 8 weeks of historical inventory and demand data. Early detection enables businesses to proactively manage inventory and reduce risk.

**Dataset Details**

product_train.csv: Training data including the target variable went_on_backorder (Yes/No).

product_test.csv: Test data without the target; used for final predictions.

**Approach & Methodology**

Classification Models Used:

Logistic Regression

Decision Tree

Random Forest

Extra Trees

Gradient Boosting

**Workflow:**

Cleaned and preprocessed data using pandas

Addressed class imbalance for the low event rate target variable

Built a complete pipeline for preprocessing and modeling using scikit-learn

Evaluated models using ROC AUC and F1 Score

Predicted backorder risk for unseen test data

**🛠 Tools & Libraries:**

pandas, numpy

scikit-learn (pipelines, classification models, evaluation metrics)

**Results**

Achieved ROC AUC score up to 94% on validation data

Optimized for recall and precision due to class imbalance
