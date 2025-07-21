# 📁 EZ Backend Intern Assignment

This repository contains the solution to the **EZ Backend Intern Assessment**. It is a secure file-sharing API built using **FastAPI**, supporting **role-based access control**, **JWT authentication**, and **Fernet encryption**. The API allows restricted upload/download of specific document types: `.docx`, `.pptx`, and `.xlsx`.

---

## 🔧 Tech Stack

- **Language**: Python 3  
- **Framework**: FastAPI  
- **Authentication**: OAuth2 with JWT  
- **Role-Based Access**: `ops`, `client`  
- **Security**: Fernet Encryption for Email Verification  
- **Data Storage**: In-Memory (Python dictionaries)  
- **Package Management**: pip (`requirements.txt`)  
- **API Testing**: Postman (Collection Included)

---

## 📁 Project Structure

ez-backend-intern-assignment/
├── main.py # FastAPI application logic
├── .env # Environment variables (not committed)
├── requirements.txt # Project dependencies
├── uploads/ # Folder for uploaded files
├── SecureFileSharingAPI.postman_collection.json # Postman collection
└── README.md # Project documentation

---

## 🔐 Features

- ✅ **User Registration** with role selection (`client`, `ops`)
- ✉️ **Email Verification** simulated with Fernet token
- 🔑 **JWT-based Login & Authentication**
- 🔒 **Role-based File Access**
  - `ops`: Upload files
  - `client`: List and download files
- 🔗 **Secure One-Time Download Links**
- 📜 **Download History Simulation**

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/sahilsingh78/ez-backend-intern-assignment.git
cd ez-
---

## 🔐 Features

- ✅ **User Registration** with role selection (`client`, `ops`)
- ✉️ **Email Verification** simulated with Fernet token
- 🔑 **JWT-based Login & Authentication**
- 🔒 **Role-based File Access**
  - `ops`: Upload files
  - `client`: List and download files
- 🔗 **Secure One-Time Download Links**
- 📜 **Download History Simulation**

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/sahilsingh78/ez-backend-intern-assignment.git
cd ez-backend-intern-assignment
backend-intern-assignment

---

## 🔐 Features

- ✅ **User Registration** with role selection (`client`, `ops`)
- ✉️ **Email Verification** simulated with Fernet token
- 🔑 **JWT-based Login & Authentication**
- 🔒 **Role-based File Access**
  - `ops`: Upload files
  - `client`: List and download files
- 🔗 **Secure One-Time Download Links**
- 📜 **Download History Simulation**

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/sahilsingh78/ez-backend-intern-assignment.git
cd ez-backend-intern-assignment

### 2.Install Dependencies
pip install -r requirements.txt

### 3. Set Up Environment Variables
Create a .env file in the root directory with the following content:
SECRET_KEY=your_jwt_secret_key
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=30
FERNET_KEY=your_fernet_key_here

To generate a Fernet key:
from cryptography.fernet import Fernet
print(Fernet.generate_key().decode())

### 4.Run the Application
uvicorn main:app --reload

###5. Open API Docs in Browser
http://127.0.0.1:8000/docs

✅ Notes
The application does not use a persistent database; all data is stored in memory for simplicity.

File uploads are restricted to .docx, .pptx, and .xlsx formats.

One-time download tokens expire upon usage for added security.

📌 Author
Sahil Singh
📧 sahilsingh78

