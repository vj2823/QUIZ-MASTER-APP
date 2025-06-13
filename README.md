# QUIZ-MASTER-APP
mad1 project
# Quiz Master - Project README

## Introduction
Quiz Master is a web-based application designed for quiz management. It allows an **admin** to create subjects, chapters, quizzes, and questions, while **users** can register, attempt quizzes, and track their scores.

## Features
- User authentication (Admin & Users)
- Admin dashboard for managing subjects, chapters, quizzes, and questions
- Users can take quizzes and view their scores
- RESTful API integration
- Quiz analytics using Chart.js

## Setup and Run the Project

### 1. Clone the Repository
```sh
git clone https://github.com/your-repo/quiz-master.git
cd quiz-master
```

### 2. Create a Virtual Environment
```sh
python -m venv myenv
```

### 3. Activate the Virtual Environment
#### On Windows:
```sh
myenv\Scripts\activate
```
#### On macOS/Linux:
```sh
source myenv/bin/activate
```

### 4. Install Dependencies
```sh
pip install -r requirements.txt
```

### 5. Set Up the Database
```sh
python setup_db.py
```
(This script initializes the database schema and adds the admin user.)

### 6. Run the Server
```sh
python app.py
```

### 7. Access the Application
Open your browser and go to:
```sh
http://127.0.0.1:5000/
```

## API Endpoints
- **User Authentication**: `/register`, `/login`, `/logout`
- **Quiz Management**: `/quizzes`, `/quiz/add`, `/quiz/update`, `/quiz/delete`
- **Questions**: `/questions`, `/question/add`, `/question/edit`, `/question/delete`
- **Scores**: `/scores`, `/scores/{id}`

## Technologies Used
- **Backend**: Flask, Flask-Login, Flask-SQLAlchemy, Flask-RESTful
- **Frontend**: HTML, CSS, Bootstrap, Jinja2, Chart.js
- **Database**: SQLite



