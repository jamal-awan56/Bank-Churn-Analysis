# Bank Churn Analysis

**Overview**

This project aims to predict customer churn for a bank using a dataset containing customer demographic, financial, and behavioral features. By accurately predicting churn, the bank can focus its efforts on retaining valuable customers.

**Key Highlights**

**Machine Learning Models:**

Various machine learning models, including LSTM-SAE (Long Short-Term Memory with Stacked Autoencoders), were implemented.

The models achieved an impressive accuracy of 99%.

**Class Imbalance Handling:**

To address the issue of class imbalance in the dataset, SMOTE-ENN (Synthetic Minority Over-sampling Technique combined with Edited Nearest Neighbors) was applied.

**Preprocessing Steps:**

Standard scaling was used to normalize the features.

Feature extraction and feature engineering were performed to enhance the dataset’s predictive power.

**Dataset Description**

The dataset includes the following key features:

customer_id: Unique identifier for each customer.

credit_score: Customer's credit score.

country: Country of residence (categorical).

gender: Gender of the customer (categorical).

age: Customer's age.

tenure: Number of years the customer has been with the bank.

balance: Bank balance of the customer.

products_number: Number of products used by the customer.

credit_card: Whether the customer owns a credit card (binary).

active_member: Whether the customer is an active member (binary).

estimated_salary: Customer's estimated salary.

churn: Target variable indicating churn status (1 for churned, 0 for retained).

**Methodology**

**Data Preprocessing:**

Missing values were handled appropriately.

Categorical variables were encoded using suitable techniques.

Standard scaling ensured uniformity across numerical features.

**Feature Engineering:**

Relevant features were extracted and engineered to improve model performance.

**Model Training and Evaluation:**

Multiple machine learning models were trained and evaluated.

LSTM-SAE was employed for its ability to capture sequential patterns in the data.

**The final model achieved a 99% accuracy rate.**

**Class Imbalance Solution:**

SMOTE-ENN was used to balance the dataset, enhancing model robustness.

**Results**

The project successfully demonstrated the potential of advanced machine learning techniques to achieve high predictive accuracy in a challenging domain. The combination of robust preprocessing, feature engineering, and model selection contributed to the outstanding performance. **The final model achieved a 99% accuracy rate.**

**Conclusion**

This analysis provides valuable insights into customer churn prediction and highlights the effectiveness of using sophisticated preprocessing techniques and state-of-the-art machine learning models. The results can guide banks in developing targeted retention strategies and improving customer satisfaction.
