# Team Task Manager

A full-stack web application designed for teams to create projects, assign tasks, and track progress. Built with a focus on simplicity, speed, and strict Role-Based Access Control (RBAC).

## 🚀 Features

*   **Secure Authentication:** User signup and login utilizing hashed passwords (bcrypt) and JWT (JSON Web Tokens) for secure session management.
*   **Role-Based Access Control (RBAC):**
    *   **Admins:** Full control to create projects, assign tasks to any team member, and oversee all operations.
    *   **Members:** Streamlined access to view assigned projects, check tasks, and update task statuses.
*   **Project & Team Management:** Easily group tasks by project for better organizational oversight.
*   **Task Tracking:** Create tasks with descriptions, due dates, and real-time status updates (Pending, In Progress, Completed).

## 🛠️ Tech Stack

*   **Backend:** Python 3, FastAPI
*   **Database:** SQLite (Local Development) / PostgreSQL (Production)
*   **ORM:** SQLAlchemy
*   **Authentication:** JWT, Passlib (bcrypt)
*   **Deployment:** Railway
