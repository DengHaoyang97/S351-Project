# Student Management System

This is a simple student management system built using **Python Flask** and **SQLite**. It allows you to manage students, courses, and grades with a user-friendly interface. Below is the project structure and instructions to set up and run the application.

---

## Project Structure

```plaintext
student_management_system/
│
├── app.py                  # Application entry point and configuration
├── models.py               # Data model definitions
├── routes.py               # Routes and business logic
├── helpers.py              # Helper functions
├── config.py               # Configuration file
├── init_db.py              # Database initialization and sample data
│
├── instance/               # Instance folder (database)
│   └── app.db              # SQLite database file
│
├── static/                 # Static resources
│   ├── css/                # CSS files
│   └── js/                 # JavaScript files
│
└── templates/              # Template files
    ├── layout.html         # Base layout template
    ├── index.html          # Homepage template
    ├── 404.html            # 404 error page
    ├── 500.html            # 500 error page
    │
    ├── students/           # Templates for student-related pages
    │   ├── list.html       # Student list
    │   ├── add.html        # Add student
    │   ├── edit.html       # Edit student
    │   └── view.html       # View student details
    │
    ├── courses/            # Templates for course-related pages
    │   ├── list.html       # Course list
    │   ├── add.html        # Add course
    │   └── edit.html       # Edit course
    │
    └── grades/             # Templates for grade-related pages
        ├── list.html       # Grade list
        └── add.html        # Add grade