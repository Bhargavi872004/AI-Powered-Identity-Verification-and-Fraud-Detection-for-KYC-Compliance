# AI-Powered Identity Verification & Fraud Detection for KYC Compliance

This repository contains an **end-to-end solution** for automating the **KYC (Know Your Customer)** process using **Artificial Intelligence**.  
The system focuses on **identity verification, document validation, and fraud detection** to ensure **secure and compliant user onboarding**.

---

## 🚀 Features

### 👤 Face Detection & Matching
Utilizes deep learning models to detect faces and verify user identity by matching live images with ID documents.

### 📄 Document Detection & OCR
Automatically detects identity documents and extracts key information using Optical Character Recognition (OCR).

### 🛡️ Tamper Detection
Includes a specialized deep learning model to detect whether documents have been digitally or physically altered.

### 📍 Address Verification
Implements an automated pipeline to validate and verify user address details.

### 🌐 Integrated Frontend
Provides a user-friendly web interface for a seamless and guided eKYC experience.

---

## 📂 Project Structure
AI-Powered-Identity-Verification-and-Fraud-Detection-for-KYC-Compliance/
│

├── Face detection/ # Models and scripts for facial recognition and liveness detection

├── document detection/ # Logic for detecting and processing ID cards, passports, etc.

├── frontend/ # Web-based UI for the eKYC application
│
├── Adress_Detection.ipynb # Notebook for processing and verifying user address details

├── tampmodeltraining.ipynb # Training script for document anti-tampering model

├── tampering dataset.ipynb # Data preprocessing for fraud detection training
│
└── README.md


---

## 🛠️ Tech Stack

### Programming Languages
- Python (Jupyter Notebooks)
- HTML
- CSS

### AI / ML Frameworks
- TensorFlow / Keras or PyTorch

### Computer Vision
- OpenCV for image processing and manipulation

### Frontend
- Standard web technologies (HTML, CSS, JavaScript)

---

## 🔧 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Bhargavi872004/AI-Powered-Identity-Verification-and-Fraud-Detection-for-KYC-Compliance.git
cd AI-Powered-Identity-Verification-and-Fraud-Detection-for-KYC-Compliance

2. Install Dependencies

Ensure you have Python installed, then run:

pip install -r requirements.txt

Note: You may need to create the requirements.txt file based on the imports used in the Jupyter notebooks.

3. Run the Models

Open the Jupyter notebooks to explore:

Model training
Document detection
Face verification
Fraud detection pipeline
jupyter notebook

📊 Workflow Overview
User uploads identity documents and selfie.
System detects and extracts document information using OCR.
Face recognition verifies identity against the document.
Tamper detection checks for forged or altered documents.
Address verification validates the provided address.
Final verification status is generated.

⚖️ License

This project is licensed under the MIT License.
