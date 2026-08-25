# Todo List Web Application

A Django-based task management application built as a practice project for Mate Academy.

---

## 🛠 Tech Stack

* **Python 3.12+**
* **Django 5.0+**
* **SQLite** (Default Database)
* **HTML5 / CSS**

---

## 📌 Features

### 1. Task Management
* **Home Page (`/`)**: Displays all tasks in a single interface.
* **Smart Sorting**: Tasks are automatically ordered — incomplete tasks (`Not done`) appear first, followed by completed tasks (`Done`). Within each group, tasks are sorted from newest to oldest.
* **Status Toggle**: A **Complete / Undo** button toggles task completion state dynamically and redirects back to the home page.
* **CRUD Operations**: Full support for creating, reading, updating, and deleting tasks.

### 2. Tag Management
* **Tag List Page (`/tags/`)**: Tabular overview of all created tags.
* **Many-to-Many Relationship**: Tasks can have multiple tags, and a single tag can belong to multiple tasks.
* **CRUD Operations**: Full support for creating, updating, and deleting tags.

### 3. Navigation
* **Persistent Sidebar**: Present across all pages for quick navigation between the Task List and Tag List.

---

## 🚀 Local Setup Instructions

### 1. Clone the repository:
```bash
git clone https://github.com/chizenkosofia-creator/Todo_List.git