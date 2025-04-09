# S351-Projectstudent_management_system/
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
    ├── index.html          # Home page
    ├── 404.html            # 404 error page
    ├── 500.html            # 500 error page
    │
    ├── students/           # Student-related templates
    │   ├── list.html       # Student list
    │   ├── add.html        # Add student
    │   ├── edit.html       # Edit student
    │   └── view.html       # View student details
    │
    ├── courses/            # Course-related templates
    │   ├── list.html       # Course list
    │   ├── add.html        # Add course
    │   └── edit.html       # Edit course
    │
    └── grades/             # Grade-related templates
        ├── list.html       # Grade list
        └── add.html        # Add grade
