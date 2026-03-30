# 📚 Library CRUD UI - Django Management System

A robust Library Management System built with **Django**, featuring a dual-architecture approach. This project demonstrates how to handle book data using traditional Django templates and modern RESTful APIs, all wrapped in a custom "Binary/Matrix" themed interface.



## 🚀 Features
* **Full CRUD Operations:** Create, Read, Update, and Delete books.
* **Hybrid Views:** Implementation using both **Function-Based Views (FBVs)** for simple logic and **Class-Based Views (CBVs)** for scalability.
* **REST API:** Integrated **Django REST Framework (DRF)** for programmatic data access.
* **Dynamic UI:** A custom sci-fi/tech-themed interface (as seen in screenshots).
* **Date Management:** Integrated date picker for tracking publication or entry dates.

---

## 🛠️ Tech Stack
* **Backend:** Django 5.x
* **API Framework:** Django REST Framework (DRF)
* **Frontend:** HTML5, CSS3 (Custom Matrix/Binary background), JavaScript
* **Database:** SQLite (Default)

---

## 📂 Project Structure

| Component | Description |
| :--- | :--- |
| `models.py` | Defines the `Book` schema (Title, Author, Description, Date). |
| `views.py` | Contains both CBVs (e.g., `BookListView`) and FBVs (e.g., `add_book`). |
| `serializers.py` | Handles JSON serialization for the REST API. |
| `urls.py` | Maps routes for both the Web UI and the API endpoints. |
| `templates/` | Custom HTML files with the dark-themed binary styling. |

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [download](https://github.com/dhiraj1008/LibraryMS)
   cd library-crud-django
