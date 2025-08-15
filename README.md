# Report: Overview of Amazon SageMaker AI

## 1. Introduction

Amazon SageMaker AI is a fully managed service from AWS that allows building, training, and deploying machine learning (ML) models at scale. While it offers extensive hands-on capabilities, our current focus is on understanding its features, interface, and key components for strategic planning — not on deep technical implementation.

---

## 2. Service Access

- **AWS Console Navigation:**  
  When searching for "SageMaker" in the AWS Console, two services appear:
  
  1. **Amazon SageMaker**
  2. **Amazon SageMaker AI**
  
  The **correct option** for accessing the features covered in this report is **Amazon SageMaker AI**.
  
---

## 3. Initial Setup

- When launching SageMaker AI for the first time, a **domain** is created and configured for a **single user**.
- After setup, access is managed via **User Profiles**.
- Selecting the user profile grants access to multiple tools:
  - **SageMaker Studio** (primary workspace)
  - **Canvas**
  - **TensorBoard**
  - **Profiler**
  - Others as needed
  
---

## 4. SageMaker Studio Overview

SageMaker Studio is a **one-stop shop** for ML workflow management.

### 4.1 Data Management

- **Data Wrangler** – Prepare, transform, and visualize data.
- **Feature Store** – Manage and store ML features.
- **EMR Clusters** – Process large datasets.

<img width="1429" height="629" alt="image" src="https://github.com/user-attachments/assets/d90066de-6764-4175-ab6e-d41cd7dbfc75" />

### 4.2 Model Development

- **AutoML** – Automatically build, train, and tune models.
- **Experiments** – Track and compare ML training runs:
  <img width="1431" height="674" alt="image" src="https://github.com/user-attachments/assets/a988a826-0649-489f-870d-f993a3ccabc1" />
- **Jobs** – Train, evaluate, or optimize models.
- **Pipelines** – Automate end-to-end workflows.
- **JumpStart** – Quickly deploy pre-trained models from providers like HuggingFace, Meta, TensorFlow, PyTorch, Stability AI, etc.

<img width="1431" height="780" alt="image" src="https://github.com/user-attachments/assets/b3580457-07c6-4da1-aeb6-03132cd1083c" />

---

## 5 Applications within SageMaker Studio

From within Studio, additional ML tools can be launched:

- **JupyterLab** – Web-based IDE for notebooks and coding.
- **RStudio** – For R programming language users.
- **MLflow** – Open-source ML lifecycle management.

<img width="1431" height="781" alt="image" src="https://github.com/user-attachments/assets/57282b92-7c88-4a0d-9b9d-7de841b9500a" />

---

**End of Report**
