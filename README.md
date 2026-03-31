AI-Powered Identity Verification & Fraud Detection for KYC Compliance
This repository contains an end-to-end solution for automating the KYC (Know Your Customer) process using Artificial Intelligence. The system focuses on identity verification, document validation, and fraud detection to ensure secure and compliant user onboarding.

🚀 Features
Face Detection & Matching: Utilizes deep learning to identify and verify user faces against provided identity documents.

Document Detection & OCR: Automatically detects identity documents and extracts relevant information for validation.

Tamper Detection: Includes a specialized model to detect if documents have been digitally or physically altered.

Address Verification: An automated pipeline to verify the authenticity of addresses provided during the KYC process.

Integrated Frontend: A user-friendly web interface for a seamless eKYC experience.

📂 Project StructureDirectory/FileDescriptionFace detection/Models and scripts for facial recognition and liveness detection.document detection/Logic for identifying and processing ID cards, passports, etc.frontend/The web-based UI for the eKYC application.Adress_Detection.ipynbNotebook for processing and verifying user address details.tampmodeltraining.ipynbTraining script for the document anti-tampering model.tampering dataset.ipynbData preprocessing for fraud detection training.

🛠️ Tech Stack
Languages: Python (Jupyter Notebooks), HTML, CSS.

AI/ML Frameworks: TensorFlow/Keras or PyTorch (for model training).

Computer Vision: OpenCV for image processing and manipulation.

Frontend: Standard web technologies for the interface.

🔧 Installation & Setup
Clone the Repository:

Bash
git clone https://github.com/Bhargavi872004/AI-Powered-Identity-Verification-and-Fraud-Detection-for-KYC-Compliance.git
cd AI-Powered-Identity-Verification-and-Fraud-Detection-for-KYC-Compliance
Install Dependencies:
Ensure you have Python installed, then run:

Bash
pip install -r requirements.txt
(Note: You may need to create a requirements file based on the imports in the .ipynb files.)

Run the Models:
Open the Jupyter Notebooks to explore the training process and detection logic.

⚖️ License
This project is licensed under the MIT License.
