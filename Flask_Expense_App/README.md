# Flask Expense Tracker

A simple and efficient web application built using **Flask** for tracking daily expenses, managing transactions, and visualizing financial data.  
This project helps users record income/expenses and understand their spending habits using interactive charts.

---

## 🚀 Features

### 🔐 User Authentication
- User registration & login  
- Password reset  
- Unique email validation  
- Secure session handling  
- Auto session timeout after inactivity  

### 🏠 Dashboard (Home Page)
- Add income, expenses, savings, or investments  
- View all transactions in a table  
- Edit & delete records  
- Summary of totals  
- Clean, user-friendly interface  

### 📊 Expense Analysis
- Category-wise charts (Pie & Bar)  
- Monthly trends (Line chart)  
- Interactive graphs using Plotly  
- Download graphs as images  

### 👤 Profile Management
- Update name, email, and password  
- Profile accessible only after login  

### 📞 Contact Page
- Submit a message or feedback  
- Works with or without login  

---

## 🗂 Project Structure

Expense_Tracker/
│
├── main.py
├── support.py
├── requirements.txt
│
├── templates/
│ ├── login.html
│ ├── register.html
│ ├── home.html
│ ├── analysis.html
│ ├── profile.html
│ ├── contact.html
│
└── static/
├── css/style.css
└── js/script.js

## ⚙️ Installation & Setup Guide

1️⃣ Clone the repository
```bash
git clone <your-repository-link>
2️⃣ Install dependencies
bash
Copy code
pip install -r requirements.txt
3️⃣ Run the application
bash
Copy code
python main.py
Now open the browser and visit:

cpp
Copy code
http://127.0.0.1:5000/
🛠 Technologies Used
Flask (Python Web Framework)

SQLite (Database)

Plotly (Data Visualization)

Pandas (Data Processing)

HTML, CSS, JavaScript (Frontend)

