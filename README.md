# No-Code Churn Prediction System

A no-code machine learning project built using AWS SageMaker Canvas to predict customer churn and automate high-risk user alerts.

---

## 📌 Project Overview
This project predicts whether a user is likely to churn based on behavioral and activity data such as login frequency, session duration, purchases, and app engagement.

The system was built using AWS SageMaker Canvas without manual coding and integrated with AWS cloud services for automation and scalability.

---

## 🚀 Features
- Batch churn prediction
- Real-time single-user prediction
- Feature impact analysis
- Automated email alerts using SNS
- Scalable cloud-based workflow

---

## ☁️ AWS Services Used
- Amazon SageMaker Canvas
- Amazon S3
- AWS Lambda
- Amazon SNS
- AWS IAM

---

## 🏗️ System Architecture Flow

```text
Local Dataset / User Behavioral Data
                │
                ▼
       Amazon SageMaker Canvas
     (Data Preparation & AutoML)
                │
                ▼
      Churn Prediction Model
   (Binary Classification Model)
                │
      ┌─────────┴─────────┐
      ▼                   ▼
Batch Predictions    Real-Time Predictions
(Multiple Users)      (Single User)
      │                   │
      └─────────┬─────────┘
                ▼
        Prediction Results
                │
                ▼
          Amazon S3 Bucket
      (Stores Prediction Data)
                │
                ▼
          AWS Lambda Trigger
   (Processes High-Risk Users)
                │
                ▼
            Amazon SNS
    (Automated Email Alerts)
                │
                ▼
         Business Stakeholders
   (Retention & Decision Making)
```

## 📊 Model Capabilities
- Binary classification model
- Predicts churn probability
- Supports batch and real-time predictions
- Automated risk notification system

---

## 🎯 Business Impact
Helps businesses identify high-risk users early and take proactive retention actions using predictive analytics and automation.

---

## 📷 Project Screenshots

### 🔹 Model Overview
![Model Overview](screenshots/model-overview.png)

### 🔹 Feature Importance Analysis
![Feature Analysis](screenshots/feature-analysis.png)

### 🔹 Batch Prediction
![Batch Prediction](screenshots/batch-prediction.png)

### 🔹 Real-Time Prediction (High Churn Risk)
![Single Prediction Yes](screenshots/single-prediction-yes.png)

### 🔹 Real-Time Prediction (Low Churn Risk)
![Single Prediction No](screenshots/single-prediction-no.png)

### 🔹 Automated SNS Email Alert
![SNS Alert](screenshots/sns-alert.png)

are available in the `screenshots/` folder.

---

## 👨‍💻 Author
Caren Victor
