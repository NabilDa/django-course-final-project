# Online Course App – Assessment Feature

An enhanced Django-based online course platform that allows instructors to create exams and learners to submit and view their results.

---

## 📌 Features
- Added `Question`, `Choice`, and `Submission` models for exam functionality
- Integrated exam creation and management through the Django admin site
- Updated course detail pages to display questions and multiple-choice options
- Implemented a submission view to handle learners’ exam answers
- Added a result view and template to evaluate and display exam scores

## 🛠️ Technologies Used
- Backend: Django
- Database: SQLite (default)
- Frontend: Django Templates, HTML, CSS
---

## 🚀 Getting Started

### Prerequisites
- Python (version 3.11 or later)
- Django (version 3.2 or later) 
- pip (Python package manager) 

### Installation
```bash
# Clone the repo
git clone https://github.com/NabilDa/django-course-final-project.git

# Navigate to project folder
cd django-course-final-project

# Install dependencies
pip install -r requirements.txt
```

### Run the Application
#### Apply migrations
python manage.py migrate

#### Create a superuser to access the admin panel
python manage.py createsuperuser

#### Run the server
python manage.py runserver

## 👨‍💻 Author
Nabil Daoui – [LinkedIn](https://www.linkedin.com/in/nabil-d/) | [Portfolio](https://www.nabildaoui.tech/)
