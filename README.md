# Task Manager App — Mobile App Developer Intern Assignment

Live App: https://bright-hummingbird-318433.netlify.app/
Backend API: https://traweli-task-backend.onrender.com/api/tasks/



## Objective

Build a simple mobile-friendly Task Manager web application using React (frontend) and Django (backend) to demonstrate understanding of component structure, REST APIs, and deployment.


## Features

- Add a new task
- View all tasks
- Mark a task as completed / undo
- Delete a task
- Mobile-friendly responsive UI
- Full CRUD API with Django REST Framework
- Deployed frontend + backend


## Tech Stack

Frontend:
- React JS
- Axios
- CSS (mobile responsive styling)
- Netlify deployment

Backend:
- Python
- Django
- Django REST Framework
- Gunicorn
- Render deployment


## Project Structure

taskmanager/
│
├── backend/     → Django REST API
└── frontend/    → React mobile UI

## Running the Project Locally

### 1. Clone repository

```bash
git clone https://github.com/YOUR_USERNAME/trawli_submission_taskmanager.git
cd trawli_submission_taskmanager

### 2. Backend setup

```bash
cd backend
python -m venv venv
venv\Scripts\activate     # Mac/Linux: source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Backend runs at:

```
http://127.0.0.1:8000/api/tasks/
```

---

### 3. Frontend setup

Open a new terminal:

```bash
cd frontend
npm install
npm start
```

Frontend runs at:

```
http://localhost:3000
```

---

## Deployment

Frontend deployed on Netlify  
Backend deployed on Render

The frontend communicates with the live backend API.

---

## Assumptions

- Simple task structure with title + completed status
- No authentication required
- SQLite database used for simplicity
- Focus was on CRUD functionality and deployment

---

## Evaluation Coverage

✔ React components and state management  
✔ REST API CRUD operations  
✔ Mobile responsive UI  
✔ Deployment completed  
✔ Clean project structure  
✔ Public live application  

---

## Notes

This project was completed within the assignment constraints with focus on functionality, clarity, and deployment readiness.

---

## Author

Ankush Aggarwal
