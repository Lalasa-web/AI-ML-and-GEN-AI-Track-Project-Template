# 📘 Smart Lender Internship Project Repository

## Project Overview

This repository contains the complete project work carried out during the internship for the **Smart Lender – Loan Approval Prediction System**. It includes all project phases, starting from brainstorming and requirement analysis to project development, testing, documentation, and final demonstration.

The main application is a Machine Learning-based loan approval prediction system developed using **Python, Flask, Scikit-learn, and XGBoost**. The application predicts whether a loan application is likely to be **Approved** or **Rejected** based on applicant details and displays a prediction confidence score.

---

# Repository Structure

```
Repository
│
├── 1. Brainstorming & Ideation/
│      └── Project brainstorming and idea generation documents
│
├── 2. Requirement Analysis/
│      └── Requirement gathering and analysis documents
│
├── 3. Project Design Phase/
│      └── Design documents, architecture, and diagrams
│
├── 4. Project Planning Phase/
│      └── Planning documents and project schedule
│
├── 5. Project Development Phase/
│      └── Smart-Lender/
│            ├── Dataset/
│            ├── models/
│            ├── static/
│            ├── templates/
│            ├── app.py
│            ├── predict.py
│            ├── loan_analysis.ipynb
│            ├── loan_modeling.ipynb
│            ├── requirements.txt
│            └── Procfile
│
├── 6. Project Testing/
│      └── Testing reports and test cases
│
├── 7. Project Documentation/
│      └── Project reports and supporting documents
│
└── 8. Project Demonstration/
       └── Demo documents and presentation materials
```

---

# Smart Lender Project

Smart Lender is a Machine Learning-based web application that predicts whether a loan application is likely to be approved based on applicant information.

The application analyzes multiple applicant details including:

- Gender
- Marital Status
- Dependents
- Education
- Self Employment
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area

The trained model predicts:

- ✅ Loan Approved
- ❌ Loan Rejected

along with a confidence score.

---

# Technologies Used

- Python
- Flask
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Joblib
- HTML
- CSS
- Git
- GitHub
- Render (Deployment)

---

# Machine Learning Workflow

1. Collect historical loan dataset.
2. Perform data analysis and preprocessing.
3. Handle missing values.
4. Encode categorical features.
5. Scale numerical features.
6. Train multiple Machine Learning models.
7. Select the best-performing model.
8. Save the trained model and preprocessing objects.
9. Integrate the model with Flask.
10. Deploy the application on Render.

---

# Project Features

- Loan approval prediction
- Confidence score
- User-friendly interface
- Machine Learning integration
- Flask web application
- Cloud deployment using Render

---

# Running the Project Locally

Navigate to the project folder:

```
5. Project Development Phase/Smart-Lender
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python app.py
```

Open your browser:

```
http://127.0.0.1:5000/
```

---

# Live Deployment

The Smart Lender application has been successfully deployed on **Render**, allowing users to access the application online without setting up the local environment.

---

# Project Phases Included

- Brainstorming & Ideation
- Requirement Analysis
- Project Design
- Project Planning
- Project Development
- Project Testing
- Project Documentation
- Project Demonstration

---

# Future Enhancements

- Database integration
- User authentication
- Loan history management
- Admin dashboard
- Real-time credit score integration
- Email notification system
- Improved prediction using larger datasets

---

Internship Project

**Smart Lender – Loan Approval Prediction System**
