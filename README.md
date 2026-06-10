# 🏦 Loan Approval Automation using Machine Learning & n8n

## 📌 Project Overview

This project automates the loan approval process using:

- Machine Learning
- Logistic Regression
- Orange Data Mining
- n8n Workflow Automation
- Excel Dataset Analysis

The system predicts whether a loan should be:

✅ Approved  
❌ Rejected

based on customer financial data.

---

# 🚀 Technologies Used

| Technology | Purpose |
|---|---|
| Orange Data Mining | Machine Learning Model |
| Logistic Regression | Classification Algorithm |
| n8n | Workflow Automation |
| Excel / CSV | Dataset Handling |
| GitHub | Project Hosting |

---

# 📊 Dataset Features

The dataset contains customer financial information:

- Customer_ID
- Age
- Gender
- Monthly_Income
- Credit_Score
- Existing_Loan
- Loan_Amount
- Loan_Term_Years
- Employment_Type
- EMI_Percentage
- Savings_Balance
- Loan_Status

---

# 🤖 Machine Learning Model

The project uses **Logistic Regression** for binary classification.

### Prediction Categories

| Output | Meaning |
|---|---|
| Approved | Loan Accepted |
| Rejected | Loan Declined |

---

# 🔄 Orange Workflow

Orange workflow used:

```text
File
 ↓
Data Table
 ↓
Logistic Regression
 ↓
Test & Score
 ↓
Confusion Matrix
```

---

# ⚙️ n8n Automation Workflow

The automation workflow performs:

- Customer data processing
- Credit score verification
- Loan approval checks
- Automated email notifications

### Workflow Structure

```text
Manual Trigger
      ↓
Set Customer Data
      ↓
IF Credit Score ≥ 700
      ↓
Send Email Notification
```


---

# 📷 Project Screenshots

## Orange Workflow
![Orange Workflow]<img width="1600" height="850" alt="orange_workflow" src="https://github.com/user-attachments/assets/e485d153-8482-4456-8495-a5577d4eb781" />


---

## Dataset Preview
![Dataset Preview]<img width="1600" height="946" alt="dataset_preview png" src="https://github.com/user-attachments/assets/ecf5b26f-31c8-4fe6-893b-6aa1561e5741" />



---

## n8n Workflow
![n8n Workflow]<img width="1600" height="946" alt="n8n_workflow png" src="https://github.com/user-attachments/assets/a935a217-f072-4502-9d60-6b17c057217c" />



---

## Model Accuracy
![Model Accuracy]<img width="1600" height="946" alt="bi dash" src="https://github.com/user-attachments/assets/401c977c-b872-4f80-9b5c-2d740fd3f38b" />

---

# 📊 Power BI Dashboard

The dashboard provides business insights into:

- Loan Approval Trends
- Customer Risk Analysis
- Credit Score Distribution
- Approval vs Rejection Rate
- Financial Performance Metrics

![Power BI Dashboard](screenshots/Dashboard.png)# 🚨 Risk Classification System

| Risk Level | Decision |
|---|---|
| Low Risk | Approved |
| Medium Risk | Manual Review |
| High Risk | Rejected |

The machine learning model classifies applicants using:

- Credit Score
- Monthly Income
- Existing Loans
- EMI Percentage
- Savings Balance

---

## APPROVED LOAN 

![APPROVED LOAN]<img width="791" height="1600" alt="approved " src="https://github.com/user-attachments/assets/6729c789-8eee-419d-b1d7-389dbd63dbb7" />




---

---

---

# 📁 Project Structure

```bash
Loan-approval-automation/
│
├── dataset/
│   └── loan_data.csv
│
├── n8n-workflow/
│   └── workflow.json
│
├── orange-workflow/
│   └── workflow.ows
│
├── screenshots/
│   ├── orange_workflow.png
│   ├── dataset_preview.png
│   ├── n8n_workflow.png
│   ├── confusion_matrix.png
│   └── model_accuracy.png
│
└── README.md
```

---

# 💼 Business Impact

- Faster loan approval decisions
- Reduced manual work
- Automated customer communication
- Improved operational efficiency
- Better financial risk analysis

---

# 📚 Learning Outcomes

Through this project, I learned:

- Machine Learning basics
- Logistic Regression
- Workflow Automation
- n8n Integration
- Orange Data Mining
- Financial Analytics
- GitHub Project Management

---

# 🔮 Future Improvements

- Power BI Dashboard
- Real-time API Integration
- AI-based Risk Prediction
- Cloud Deployment
- Advanced Financial Analytics

---

# 👨‍💻 Author

MBA Finance Student  
Machine Learning & Automation Enthusiast
