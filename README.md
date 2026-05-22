# Fraudulent Transaction Detection for Digital Money Transfer

## Project Overview

This project focuses on developing a machine learning–driven fraud detection system for NovaPay, a digital-first cross-border money transfer company operating across the United Kingdom, Canada, and the United States.

The solution replaces NovaPay’s traditional static rules-based fraud detection process with a scalable, adaptive, and explainable machine learning system capable of detecting fraudulent transactions in real time while minimizing false positives.

The project combines concepts from:
- Data Engineering
- Machine Learning
- Explainable AI
- API deployment
- MLOps and monitoring

to simulate a production-grade fraud detection platform used within modern fintech organizations.

---

# Problem We Are Solving

Digital payment platforms process millions of transactions daily across multiple countries and digital channels. As transaction volumes continue to grow, fraudsters increasingly exploit vulnerabilities using:
- identity theft
- account takeover
- unauthorized payments
- transaction laundering

NovaPay currently relies on a static rules-based fraud detection system combined with manual review processes. However, this approach creates several major challenges:

## Operational Challenges
- Manual fraud reviews cannot scale efficiently with real-time transaction volumes
- Static fraud rules struggle to adapt to evolving fraud tactics
- Fraud investigations become slower and less effective as transaction volume grows

## Financial Challenges
- Fraud-related chargebacks and refunds increase operational costs
- Missed fraudulent transactions lead to direct financial losses
- False positives frustrate legitimate customers and negatively impact user experience

## Regulatory Challenges
- Financial institutions require transparent and explainable fraud decisions
- AML and KYC regulations demand auditable fraud monitoring systems
- Weak fraud controls may result in compliance risks and regulatory scrutiny

In addition, fraudulent transactions represent less than 1% of all observations, creating a highly imbalanced classification problem that makes fraud detection particularly challenging.

This project aims to solve these problems by building a scalable machine learning–driven fraud detection system capable of:
- identifying fraudulent transactions in real time
- reducing false positives
- improving fraud recall
- supporting explainable fraud decisions
- scaling with increasing transaction volumes

---

# Company Overview

NovaPay is a digital-first cross-border money transfer company based in Toronto, Canada. The company enables customers to seamlessly send, receive, and hold multiple currencies across international borders.

NovaPay operates across:
- United Kingdom
- Canada
- United States

The platform serves:
- expatriates supporting families abroad
- freelancers receiving global payments
- businesses managing international payroll

## Key Highlights

- Processes millions of monthly cross-border transactions
- Prioritizes affordability, speed, and exceptional digital experiences
- Supports secure multi-currency international transactions
- Focuses on accessible and transparent financial services

Maintaining secure transaction processing is critical to protecting customer trust and ensuring operational stability.

---

# Target Variable

The target variable used for supervised machine learning classification is:

```python
fraud_label
```

This column tells the model whether a transaction is legitimate or fraudulent.

| Value | Meaning |
|---|---|
| 0 | Legitimate Transaction |
| 1 | Fraudulent Transaction |

The values `0` and `1` are the classes contained inside the target variable, while `fraud_label` is the actual target column the machine learning model learns to predict.














