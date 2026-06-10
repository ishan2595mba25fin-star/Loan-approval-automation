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
![Orange Workflow](screenshots/orange_workflow.png)

---

## Dataset Preview
![Dataset Preview](screenshots/dataset_preview.png)

---

## n8n Workflow
![n8n Workflow](screenshots/n8n_workflow.png)

---

## Confusion Matrix
![Confusion Matrix](screenshots/confusion_matrix.png)

---

## Model Accuracy
![Model Accuracy](screenshots/model_accuracy.png)

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
