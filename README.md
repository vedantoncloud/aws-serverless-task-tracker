# 🚀 AWS Serverless Task Tracker

A full-stack **serverless web application** built using **Amazon Web Services (AWS)** that allows users to securely manage tasks with a scalable, cost-efficient cloud architecture.

---

## ✨ Features

- 🔐 Secure user authentication using **Amazon Cognito**
- ➕ Create tasks using REST APIs
- 📋 Fetch tasks from DynamoDB
- ☁️ Fully serverless architecture (no servers to manage)
- 📈 Highly scalable and cost-efficient design

---

## 🧱 System Architecture

Frontend (Amazon S3 + CloudFront)  
→ Amazon API Gateway  
→ AWS Lambda  
→ Amazon DynamoDB  
→ Response to Client

---

## 🛠️ AWS Services Used

- **Amazon S3** – Static frontend hosting  
- **Amazon CloudFront** – Content Delivery Network (CDN)  
- **AWS Lambda** – Backend business logic  
- **Amazon API Gateway** – RESTful API endpoints  
- **Amazon DynamoDB** – NoSQL database for task storage  
- **Amazon Cognito** – User authentication & authorization  
- **AWS IAM** – Secure access control and permissions  

---

## 📂 Repository Structure

```text
aws-serverless-task-tracker/
│
├── index.html        # Frontend UI
├── styles.css        # Styling
├── Screenshots/      # Application & API screenshots
├── README.md         # Project documentation

---
📌 Internship Context
This project was developed as part of a Cloud Engineering Internship at HEPro, focusing on hands-on experience with AWS serverless services, cloud architecture, and real-world application deployment.

👤 Author
Vedant Mishra
Cloud & DevOps Enthusiast | AWS Serverless Developer
