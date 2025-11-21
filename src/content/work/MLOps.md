---
title: Deep Learning – Real Estate Price Prediction
publishDate: 2024-12-01 00:00:00
img: /assets/MLOps.png
img_alt: Deep learning model for real estate price prediction
description: |
  This project focuses on building a deep learning model capable of predicting the market value of real estate properties using a public dataset. The work includes data preparation and exploration, training a neural network model, and fully deploying the application (backend + frontend) on AWS with a professional CI/CD pipeline.

  The application provides an API for generating predictions, a user-friendly web interface for data input, and a robust cloud infrastructure automating the build, deployment, and service management.
tags:
 - Deep Learning
 - Machine Learning
 - AWS
 - CI/CD
---

## 🏡 Deep Learning Project – Real Estate Price Prediction

**Date:** December 2024  
**Presented by:** Gabin Niel  

---

This project aims to build a deep learning model capable of predicting the market value of real estate properties using a public dataset.  
The work includes data preparation, exploration, model training, and full deployment on a cloud platform with a professional CI/CD pipeline.

### 🚀 Main Features

- 📊 Data exploration and cleaning  
- 🧠 Deep Learning modeling (neural network)  
- 🧪 Model evaluation and visualizations  
- 🌐 Deployment of a backend API to serve the model  
- 💻 Deployment of a frontend consuming the API  
- ⚙️ Automated CI/CD  
- ☁️ Fully cloud-based infrastructure on AWS  

### 🧠 Deep Learning Workflow

#### 1. Data Preparation  
Using the `data_immobiliers.csv` file:

- Removal of unnecessary columns  
- Analysis of missing values  
- Normalization / encoding  

#### 2. Exploration  
- Distribution of property values  
- Matplotlib visualizations  

#### 3. Modeling  
- Dense neural network (Keras/TensorFlow or PyTorch depending on the notebook)  
- Train/test split  
- Learning curves  

### ☁️ Cloud Architecture

The complete application (model + API + frontend) was deployed on AWS.

#### 🔹 Backend  
- FastAPI/Flask server (depending on the chosen implementation)  
- `/predict` endpoint serving the model  

#### 🔹 Frontend  
- Simple web interface allowing users to input values and obtain predictions  
- Deployed on the same cloud infrastructure  

#### 🗄️ Model Storage  
- The trained model is stored in Amazon S3  

### ⚙️ Automated CI/CD

A full CI/CD pipeline was implemented:

- 🛠️ Automatic image building (backend + frontend)  
- 📦 Push to Amazon ECR  
- 🚀 Automatic deployment on Amazon ECS  
- 🔒 Permissions management via IAM  
- 📈 Logs and monitoring via CloudWatch  

### 📦 AWS Services Used

| Service | Role |
|--------|------|
| Amazon S3 | Model storage |
| Amazon ECR | Docker registry for backend and frontend images |
| Amazon ECS (Fargate) | Execution of backend and frontend |
| IAM | Fine-grained permission management and S3 access |
| CloudWatch | Logs, monitoring, and alarms |
| Load Balancer | Public access |

### 📷 Demo Video

<video width="100%" controls>
  <source src="/assets/MLOps.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
