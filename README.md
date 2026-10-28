# ✨ Task Manager

### A Simple Django-Based Task Management Web Application

A lightweight and user-friendly web application designed to help users organize tasks, manage deadlines, and track their progress efficiently.

<p align="center">
  <strong>Built with Django · SQLite · HTML · CSS</strong>
</p>

---

## 📌 Overview

**Task Manager** is a web application developed using Django that demonstrates the fundamental concepts of web development, including CRUD operations, database integration, Django templates, and ModelForms.

Users can create tasks, view task details, update task information, and delete tasks through a simple interface.

## 🚀 Features

- **Create Tasks** — Add tasks with titles, descriptions, statuses, and due dates.
- **View Tasks** — Browse all tasks and view individual task details.
- **Update Tasks** — Edit task information whenever needed.
- **Delete Tasks** — Remove tasks with a confirmation step.
- **Task Status** — Track tasks as Pending, In Progress, or Completed.
- **Due Dates** — Set deadlines for better task organization.
- **Dark & Light Mode** — Switch between two visual themes.
- **Admin Panel** — Manage task records through Django administration.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Django | Web framework and MVT architecture |
| SQLite | Database |
| HTML | Page structure |
| CSS | Styling and themes |
| Django ModelForm | Task form handling |

## 📂 Project Structure

```text
Task-Manager/
│
├── config/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── tasks/
│   ├── migrations/
│   ├── templates/
│   │   └── tasks/
│   ├── admin.py
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── static/
│   └── tasks/
│       └── style.css
│
├── manage.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Atik-Ahmed-1003/Task-Manager.git
cd Task-Manager
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate the Environment

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Create an Admin Account (Optional)

```bash
python manage.py createsuperuser
```

### 7. Start the Development Server

```bash
python manage.py runserver
```

Open the application in your browser:

**Application:** http://127.0.0.1:8000/

**Django Admin:** http://127.0.0.1:8000/admin/

## 📋 Task Status Options

| Status | Description |
|---|---|
| Pending | The task has not been completed yet |
| In Progress | The task is currently being worked on |
| Completed | The task has been finished |

## 🎯 Project Objectives

- Understand Django's Model-View-Template (MVT) architecture.
- Implement Create, Read, Update, and Delete operations.
- Work with models, forms, URL routing, and templates.
- Integrate a relational database using SQLite.
- Organize and document a Django project.

## 👨‍💻 Developer

**Atik Ahmed**

GitHub: [Atik-Ahmed-1003](https://github.com/Atik-Ahmed-1003)

---

<p align="center">
  Made with Python and Django
</p>