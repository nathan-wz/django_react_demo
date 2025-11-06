# Planly

A minimalist, full-stack planner application designed to help users organize, manage, and track their daily tasks and events. The application provides a simple and intuitive interface for creating new tasks, marking them as complete, and keeping a clear overview of upcoming activities.

<img width="1804" height="727" alt="image" src="https://github.com/user-attachments/assets/44ec73d2-698e-42dd-9de1-1cbf5a23862a" />

## Technologies Used

This project is built using a combination of powerful and modern technologies for both the frontend and backend.

### Backend

* **Django:** A high-level Python web framework that encourages rapid development and clean, pragmatic design.

* **Django REST Framework:** A powerful and flexible toolkit for building Web APIs.

### Frontend

* **React:** A JavaScript library for building user interfaces.

* **HTML & CSS:** Standard web technologies for structure and styling.

## Features

* **Task Creation:** Easily add new tasks with a title and due date.

* **Task Management:** Mark tasks as completed to track progress.

* **User-friendly Interface:** A clean and responsive design for easy navigation on any device.

## Installation

To get the application up and running, you'll need to set up both the backend and frontend.

### 1. Backend Setup (Django)

1. **Prerequisites:** Ensure you have Python 3 and `pip` installed.

2. **Clone the Repository:**

3. **Install Dependencies:**

```bash
pip install -r requirements.txt
```

4. **Run Migrations:**
```bash
python manage.py migrate
```

5. **Start the Development Server:**
```bash
python manage.py runserver
```

### 2. Frontend Setup (React)

1. **Prerequisites:** Ensure you have Node.js and `npm` installed.

2. **Navigate to the Frontend Directory:**
```bash
cd ../frontend
```

3. **Install Dependencies:**
```bash
npm install
```

4. **Start the Development Server:**
```bash
npm start
```

The frontend will run on `http://localhost:3000` and the backend API will be available at `http://localhost:8000`.

## Project Structure
```bash
├── backend/                  # Django backend
│   ├── planner/              # Django project folder
│   ├── tasks/                # Django app for tasks
│   └── requirements.txt      # Python dependencies
├── frontend/                 # React frontend
│   ├── public/               # Static assets
│   ├── src/                  # React source code
│   └── package.json          # Node.js dependencies
└── README.md
```
