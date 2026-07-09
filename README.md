# Online_Quiz_System-
BCA Final Year Project using PHP and MySQL
# 📝 Online Quiz System

## 📌 Project Overview

Online Quiz System is a web-based application developed to conduct online quizzes in an efficient and user-friendly way. The system allows users to register, login, participate in quizzes, answer multiple-choice questions, and view their results instantly.

The admin can manage quiz categories, questions, users, and monitor quiz results through an admin dashboard.

This project is developed as a BCA Final Year Project.

---

## 🎯 Objectives

* To provide an online platform for conducting quizzes.
* To reduce manual evaluation of quiz exams.
* To provide instant result generation.
* To help administrators manage quiz questions and users easily.
* To improve learning and assessment processes.

---

## 🛠️ Technologies Used

### Frontend:

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Backend:

* Python (Flask)

### Database:

* MySQL

### Tools:

* MySQL Workbench
* Visual Studio Code
* Python

---

## ✨ Features

## 👤 User Module

* User Registration
* User Login and Logout
* View Available Quiz Categories
* Attempt Online Quiz
* Answer Multiple Choice Questions
* Automatic Score Calculation
* View Quiz Results
* Track Previous Attempts

---

## 🔐 Admin Module

* Admin Login
* Admin Dashboard
* Manage Users
* Add Quiz Categories
* Add / Update / Delete Questions
* Manage Quiz Questions
* View User Quiz Attempts
* View Results and Scores

---

## 🗄️ Database Details

Database Name:

```sql
online_quiz
```

### Main Tables:

* users
* admin
* categories
* questions
* results

---

## 📂 Project Structure

```text
Online_Quiz_System

│
├── app.py
├── config.py
├── database.sql
├── requirements.txt
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── register.html
│   ├── quiz.html
│   ├── result.html
│   └── admin_dashboard.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── images/
│
├── uploads/
│
└── README.md
```

---

## ⚙️ Installation Steps

### 1. Clone Repository

```bash
git clone https://github.com/username/Online-Quiz-System.git
```

### 2. Open Project Folder

```bash
cd Online_Quiz_System
```

### 3. Create Virtual Environment

```bash
python -m venv venv
```

### 4. Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

### 5. Install Required Packages

```bash
pip install -r requirements.txt
```

### 6. Setup Database

* Open MySQL Workbench
* Create database:

```sql
CREATE DATABASE online_quiz;
```

* Import:

```text
database.sql
```

### 7. Run Application

```bash
python app.py
```

Open browser:

```text
http://127.0.0.1:5000/
```

---

## 🔑 Login Details

### Admin Login

```text
Username: admin
Password: admin123
```

(User can update credentials according to database.)

---

## 📊 System Workflow

```
User Registration
        ↓
User Login
        ↓
Select Quiz Category
        ↓
Attempt Quiz
        ↓
Submit Answers
        ↓
Automatic Result Generation
```

---

## 📸 Screenshots

Add screenshots of:

* Home Page
* Registration Page
* Login Page
* Quiz Interface
* Result Page
* Admin Dashboard

---

## 🚀 Future Enhancements

* Timer Based Quiz
* Random Question Generation
* Certificate Generation
* Email Notification
* AI-Based Question Recommendation
* Performance Analysis Dashboard
* Mobile Application Support

---
## screenshoot
<img width="1917" height="901" alt="home page" src="https://github.com/user-attachments/assets/0e2c3601-0822-46e1-8bc5-270505b8f027" />
<img width="1912" height="912" alt="user register page" src="https://github.com/user-attachments/assets/6fc9155f-ab7d-477a-b20f-45b4e8b6f8ca" />
<img width="1912" height="908" alt="user login page" src="https://github.com/user-attachments/assets/9b2ae155-0b24-45c4-b624-89baba7753a9" />
<img width="1918" height="907" alt="user dashboard" src="https://github.com/user-attachments/assets/ca4f28e6-360f-435e-9ed1-49a7cef7d1df" />
<img width="1900" height="907" alt="quize satr wit timer" src="https://github.com/user-attachments/assets/914c00d0-f879-47d0-bae6-0a4ef877e137" />
<img width="1896" height="902" alt="submit" src="https://github.com/user-attachments/assets/37cb0a44-d0dd-4e0e-89d1-91abe4326c45" />
<img width="1918" height="903" alt="score of quiz" src="https://github.com/user-attachments/assets/b3795db6-5145-47a9-8e5f-584656e351b6" />
<img width="1916" height="873" alt="quiz history" src="https://github.com/user-attachments/assets/0e58b0bf-9b57-4bf5-8a05-b8d0add2683a" />
<img width="1918" height="852" alt="admin login" src="https://github.com/user-attachments/assets/b3026a26-20aa-47a3-b329-8ac5fd4487b4" />
<img width="1902" height="905" alt="admin dashboard" src="https://github.com/user-attachments/assets/057f292c-5c57-4dc3-af68-8d848372af3f" />
<img width="1913" height="862" alt="results of user on admin page" src="https://github.com/user-attachments/assets/5465c621-0bcf-4790-8f9f-a6b50254d4fa" />
<img width="1905" height="906" alt="add quetions with options" src="https://github.com/user-attachments/assets/114065dc-1e36-4292-a409-5777b9c3bd6f" />
<img width="1912" height="917" alt="edit quetions" src="https://github.com/user-attachments/assets/1d0e3d7a-9a12-469d-95ca-15c7b119f352" />

## 👩‍💻 Developer

**Divya Rahane**

BCA Science Project

---

## 📄 License

This project is developed for educational purposes only.
