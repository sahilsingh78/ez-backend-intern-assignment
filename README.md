# EZ Backend Intern Assignment

## 📝 Overview

This repository contains the solution to the Backend Intern assignment provided by EZ as part of the recruitment process. The assignment demonstrates backend development skills including API creation, data management, and implementation of business logic using [Your Chosen Language/Framework, e.g., PHP, Node.js, Python Flask, etc.].

---

## 🚀 Tech Stack

- Programming Language: [e.g., PHP / Node.js / Python]
- Framework: [e.g., Laravel / Express.js / Flask]
- Database: [e.g., MySQL / PostgreSQL / MongoDB / SQLite]
- Tools Used: 
  - Git & GitHub
  - Postman (for API testing)
  - VS Code (Editor)

---

## 📂 Project Structure
/project-root
│
├── /routes # API route definitions
├── /controllers # Business logic and API handlers
├── /models # Database schemas/models
├── /utils # Utility/helper functions
├── /config # DB config / environment setup
├── .env # Environment variables (excluded from repo)
├── README.md # Project documentation
└── index.js/app.php/main.py # Entry point

---

## 📬 APIs Implemented

| Method | Endpoint         | Description                   |
|--------|------------------|-------------------------------|
| GET    | `/tasks`         | Get all tasks                 |
| POST   | `/tasks`         | Create a new task             |
| PUT    | `/tasks/:id`     | Update an existing task       |
| DELETE | `/tasks/:id`     | Delete a task                 |

> Add or modify according to your actual implementation

---

## ⚙️ Setup & Run Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ez-backend-assignment.git
   cd ez-backend-assignment
2. Install Dependencies
npm install         # For Node.js
composer install    # For PHP
pip install -r requirements.txt  # For Python
Setup Environment Variables
3. Create a .env file in the root directory with appropriate values:
DB_HOST=localhost
DB_USER=root
DB_PASS=your_password
DB_NAME=ez_test_db
4. Run the Application
   npm start           # Node.js
php -S localhost:8000 # PHP
python app.py       # Python
5.Test the APIs
Use Postman or cURL to test endpoints.
