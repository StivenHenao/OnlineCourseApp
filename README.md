
# 🧑‍🏫 OnlineCourseApp

**OnlineCourseApp** is a Django-based web application for managing online courses. Users can register, enroll in courses, submit answers to quizzes, and view their results.

----------

## 📁 Project Structure


```
tfjzl-final-cloud-app-with-database/
├── onlinecourse/              # Main app with models, views, templates, etc.
│   ├── templates/onlinecourse/  # HTML templates for user interface
│   ├── admin.py               # Admin site registration
│   ├── models.py              # Data models for courses, users, questions, etc.
│   ├── views.py               # Core logic for user registration, login, enrollment, and quiz
│   └── urls.py                # URL routing for the app
├── static/                    # Static files (CSS, JS, etc.)
├── manage.py                  # Django’s CLI management tool
├── requirements.txt           # Python dependencies
├── db.sqlite3                 # SQLite database` 
```
----------

## 🚀 Features

-   User Registration & Login
    
-   Course Listing and Enrollment
    
-   Dynamic Exam Submission and Auto-Grading
    
-   Displays Exam Results with Scores
    
-   Admin Interface for Managing Models
    

----------

## ⚙️ Installation

1.  **Clone the repository**
    
    `git clone https://github.com/StivenHenao/OnlineCourseApp.git cd OnlineCourseApp` 
    
2.  **Create a virtual environment (optional but recommended)**    
    `python3 -m venv djangoenv source djangoenv/bin/activate` 
    
3.  **Install dependencies**
    
    `pip install -r requirements.txt` 
    
4.  **Run migrations**
 
    `python manage.py migrate` 
    
5.  **Start the development server**
    
    `python manage.py runserver` 
    
6.  **Access the app**  
    Open your browser and go to `http://127.0.0.1:8000/`
    

----------

## 🗃️ Models Overview Diagram

<div align="center"> <img src="https://i.imgur.com/LneeFuT.png" width="80%" alt="Add Customer Preview" /> <br/>

----------

## 📸 Screenshots

<div align="center"> <h3>🏠 Home</h3> <img src="https://i.imgur.com/YtZKbI4.png" width="80%" alt="Home Preview" /> <br/>

<div align="center"> <h3>👓 Start Quiz</h3> <img src="https://i.imgur.com/Tt21LL3.png" width="80%" alt="Add Customer Preview" /> <br/>

<div align="center"> <h3>✅ Results</h3> <img src="https://i.imgur.com/J2HkOms.png" width="80%" alt="Summary Preview" /> <br/>
