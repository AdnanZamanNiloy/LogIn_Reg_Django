
````markdown
# 👤 Django User Authentication System

This is a Django-based user authentication system that includes:

- 🔐 **User Registration**  
- 🔑 **Login / Logout**  
- 🔁 **Forgot Password (Reset via Email)**  
- 👤 **User Profile View & Update**

Perfect as a starter for projects that require user accounts and secure access control.

---

## 🚀 Features

- ✅ User Sign Up with validation  
- ✅ Secure Login and Logout  
- ✅ Forgot Password & Reset via Email  
- ✅ Update User Profile (Username, Email, etc.)  
- ✅ Django Messages for alerts (success/error)  
- ✅ Built using Django’s built-in `auth` system  

---

## 📦 Getting Started

Follow these steps to set up the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/AdnanZamanNiloy/django-auth-system.git

# 2. Move into the project directory
cd django-auth-system

# 3. Install virtualenv if needed
pip install virtualenv

# 4. Create a virtual environment
virtualenv venv

# 5. Activate the virtual environment
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate

# 6. Install required packages
pip install -r requirements.txt
````

---

## ⚙ Setup

### 📂 Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 📧 Email Configuration for Password Reset

Add this to your `settings.py`:

```python
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_PORT = 587
EMAIL_USE_TLS = True
EMAIL_HOST_USER = 'your-email@gmail.com'
EMAIL_HOST_PASSWORD = 'your-app-password'  # Use App Password if using Gmail
```

---

### 🧪 Create a Superuser

```bash
python manage.py createsuperuser
```

---

## ▶ Running the App

```bash
python manage.py runserver
```

Visit your browser:
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 📸 Preview

* 📝 Registration Page
* 🔐 Login Page
* 📧 Forgot Password
* 👤 User Profile Page

*Add screenshots here:*

```markdown
![Registration](assets/registration.png)
![Login](assets/login.png)
![Forgot Password](assets/forgot-password.png)
![Profile](assets/profile.png)
```

---

## 🛠 Technologies Used

* 🐍 Python 3
* 🌐 Django Framework
* 🔐 Django Authentication
* 💅 HTML, CSS, Bootstrap
* 💾 SQLite (default DB)

---

## 👨‍💻 Author

Made with ❤️ by **Adnan Zaman**
