# 🔒 Phishing Email Detection System – Machine Learning Model for Email Security

## Overview
The Phishing Email Detection System is a machine learning based cybersecurity project that identifies whether an email is phishing or legitimate. Phishing attacks are commonly used by attackers to trick users into revealing sensitive information such as passwords, banking details, or personal data. This project analyzes the text content of emails and predicts whether the email is safe or a phishing attempt using trained machine learning models.

## Dataset Information
- Source: Kaggle – Phishing Email Detection Dataset  
- Size: Approximately 18,000+ emails  
- Classes:
  - 0 – Safe Email
  - 1 – Phishing Email
- Feature Used: Email text body content

## Machine Learning Models Used
This project tests multiple machine learning algorithms to compare their performance in detecting phishing emails:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Naive Bayes
- XGBoost

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Natural Language Processing (NLP)
- Jupyter Notebook / Google Colab

## Project Workflow
1. Load the phishing email dataset.
2. Clean and preprocess the email text data.
3. Convert text data into numerical features using NLP techniques.
4. Train multiple machine learning models on the dataset.
5. Evaluate the model performance.
6. Accept user email text input.
7. Predict whether the email is phishing or safe.

## Usage
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all the cells.
3. Enter an email message when prompted.
4. The system will classify the email as phishing or legitimate.

## Example
Input Email:
Your bank account has been suspended. Click the link below to verify your account immediately.

Output:
Phishing Email Detected

## Project Structure
Phishing-Email-Detection-System  
│  
├── Phishing_Email_Detection.ipynb  
└── README.md  

## Applications
- Email phishing detection systems
- Spam filtering tools
- Cybersecurity learning projects
- Security awareness tools

## Author
Kunal Ambulkar  
B.Sc Cyber Security Student
