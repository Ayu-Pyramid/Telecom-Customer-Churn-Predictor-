his project predicts whether a customer is likely to leave a telecom company and creates simple retention emails for customers who are at risk.
What the Project Does
Loads customer data from CSV files
Explores and cleans the data
Converts text values into numbers so the model can understand them
Trains a machine learning model to predict customer churn
Tests the model and checks accuracy
Finds which features affect churn the most
Uses AI to write short emails to keep customers from leaving
Model Used
Logistic Regression
Accuracy on test data: about 85%
AI Retention Emails
Customers predicted to churn are flagged
The system decides a possible reason (high bill or service issues)
AI generates a short, professional email to retain the customer
Files
churn-bigml-80.csv – training data
churn-bigml-20.csv – testing data
retention_emails.txt – saved AI-generated emails
Tools & Libraries
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
OpenAI API
Goal
To show how machine learning and AI can help businesses predict customer churn and take action before customers leave.
