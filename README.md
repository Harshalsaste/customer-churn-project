project name - Customer Churn Prediction 

Problem statement:
Predict which customers are likely to leave a telecom service.

Dataset:
Telco Customer Churn Dataset from Kaggle

Features:
* Tenure
* Monthly Charges
* Contract Type
* Internet Service

Models Used:
* Logistic Regression
* Decision Tree
* Neural Network
* LightGBM (Kaggle-level)

Results & Insights:

*Model Performance:
Logistic Regression ~0.80   
LightGBM ~0.88  

Best Model:
LightGBM performed best due to its ability to capture complex churn patterns and feature interactions.

Key Insights:
* Customers with month-to-month contracts are more likely to churn
* Higher monthly charges increase churn probability
* Long tenure significantly reduces churn risk

Visualizations:
#Feature Importance
#ROC Curve

Tech Stack:
Python, Scikit-learn, LightGBM, TensorFlow

## How to Run

```bash
pip install -r requirements.txt
```

## Author

Harshal Saste
