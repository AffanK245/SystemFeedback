# SystemFeedback
Django-based employee feedback system
# SystemFeedback – Workforce Productivity Suite

SystemFeedback is a simple, powerful HR management system built with Django. It allows CEOs, managers, and employees to manage attendance, salary, feedback, and leave in one centralized platform.


## 🔑 Default Logins

- **CEO**: `admin@admin.com` / `admin`
- **Manager**: `manager@manager.com` / `manager`
- **Employee**: `employee@employee.com` / `employee`

---

## ✨ Features

### CEO Can:
- Manage managers and employees
- Create departments and divisions
- Approve/reject leave
- View/respond to feedback

### Manager Can:
- Take attendance
- Add salaries
- Apply for leave
- Send feedback to Employees


### Employee Can:
- View salary and attendance
- Apply for leave
- Send feedback to CEO
- Check the feedback from manager


---

## ⚙️ How to Run Locally

1. **Clone the project**
   git clone https://github.com/AffanK245/SystemFeedback.git
   cd SystemFeedback

2. Create and activate a virtual environment
   python -m venv venv
   venv\Scripts\activate   # On Windows


3. Create a .env file in the root directory:
   DATABASE_URL="postgres://your_user:your_password@localhost:5432/your_db"
   SECRET_KEY="your_secret_key"

4. Install all dependencies
   pip install -r requirements.txt

5.Run migrations
  python manage.py makemigrations
  python manage.py migrate

6. Create a superuser
   python manage.py createsuperuser

7.Run the development server
  python manage.py runserver

8.Visit http://127.0.0.1:8000/ in your browser.











