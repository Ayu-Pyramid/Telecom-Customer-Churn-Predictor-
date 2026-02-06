Customer Churn Prediction & AI Retention Agent
📌 Project Overview
This project predicts whether a telecom customer is likely to leave and automatically generates professional retention emails for at-risk customers. It combines machine learning for churn prediction with Generative AI for personalized customer outreach.
🚀 Key Features
Data Processing & Modeling:
Loads and explores customer data from CSV files
Cleans and preprocesses data, converting text values to numeric form
Trains a logistic regression model to predict churn
Evaluates model performance (accuracy ~85%)
Identifies key factors contributing to churn
AI-Generated Retention Emails:
Flags customers predicted to churn
Determines potential reasons for churn (e.g., high bills, service issues)
Uses AI to generate short, professional emails aimed at retaining customers
Saves generated emails to retention_emails.txt
🛠️ Tech Stack & Tools
Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
APIs: OpenAI GPT-4 for email generation
📁 Project Files
churn-bigml-80.csv – training dataset
churn-bigml-20.csv – testing dataset
retention_emails.txt – AI-generated retention emails
🎯 Goal
Demonstrate how machine learning and AI can help businesses predict customer churn and proactively engage at-risk customers to improve retention.
