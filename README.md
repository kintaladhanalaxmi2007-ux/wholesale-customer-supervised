# wholesale-customer-supervised

📌 Project Overview
This project focuses on analyzing wholesale customer purchasing behavior using supervised machine learning. The goal is to classify customers into two categories:
HORECA (Hotels, Restaurants, Cafés)
Retail
By understanding customer spending patterns, businesses can improve marketing strategies, inventory management, and decision-making.
🎯 Problem Statement
Wholesale businesses deal with different types of customers who show varying purchasing behaviors. Manually identifying customer types is difficult and can lead to:
Poor marketing strategies
Inefficient inventory management
Wrong business decisions
✅ Objective
Build a machine learning model to:
Analyze customer spending data
Identify patterns
Predict whether a customer is Retail or HORECA
📊 Dataset Information
Source: UCI Machine Learning Repository
Records: 440 customers
Features: Annual spending in different categories
🔗 Dataset Link
https://archive.ics.uci.edu/ml/machine-learning-databases/00292/Wholesale%20customers%20data.csv⁠�
📁 Features Description
Feature
Description
Channel
Target variable (1 = HORECA, 2 = Retail)
Region
Customer region
Fresh
Spending on fresh products
Milk
Spending on milk products
Grocery
Spending on grocery items
Frozen
Spending on frozen products
Detergents_Paper
Spending on cleaning products
Delicassen
Spending on specialty food
🔍 Data Preprocessing
✔️ Checked missing values
✔️ Removed duplicates
✔️ Applied Standard Scaling
✔️ Encoded categorical data

⚠️ Why Scaling?
Features have different ranges, so scaling ensures:
Equal contribution of all features
Better performance of models like KNN, SVM

📈 Exploratory Data Analysis (EDA)
Key Insights:
Retail customers spend more on:
Grocery
Detergents Paper
Milk
HORECA customers spend more on:
Fresh products
Frozen items
Detergents Paper is the strongest differentiator

🤖 Models Used
Logistic Regression
Decision Tree
Random Forest

🏆 Model Performance
Model
Accuracy
Logistic Regression
88%
Decision Tree
92%
Random Forest
94% ✅
 Best Model: Random Forest

📊 Evaluation Metrics
Accuracy
Precision
Recall
F1 Score
Confusion Matrix

💡 Business Insights
Clear difference in purchasing behavior
Strong indicators:
Retail → Grocery & Detergents
HORECA → Fresh products

📌 Recommendations
Segment customers into Retail & HORECA
Use targeted marketing strategies
Offer discounts:
Grocery → Retail
Fresh → HORECA
Optimize inventory based on demand
Use predictions for decision-making

⚠️ Limitations
Small dataset (440 records)
Limited features
No demographic data
Possible overfitting

🚀 Future Scope
Add more features (demographics, frequency)
Use advanced models (XGBoost)
Hyperparameter tuning
Build dashboard (Power BI / Tableau)
Deploy as web application

📌 Conclusion
This project successfully demonstrates how supervised learning can classify customers based on purchasing behavior.
The insights help businesses improve:
Customer segmentation
Marketing strategies
Inventory planning
 Random Forest model achieved the best performance with 94% accuracy.


✅ Give GitHub upload steps
✅ Add project screenshots section
✅ Create README with badges (more professional look)
