# 🎓 EduNova

> A modern, open-source School Management System built with Django.

EduNova is a comprehensive and scalable School Management System designed to simplify academic administration, student management, teacher management, and school operations through a clean and modern web interface.

---

## ✨ Features

- 👨‍🎓 Student Management
- 👨‍🏫 Teacher Management
- 👨‍👩‍👧 Parent Portal
- 📚 Classroom Management
- 📝 Quiz & Examination System
- 📊 Report Cards
- 💰 Financial Management
- 📅 Academic Calendar
- 📢 News & Announcements
- 🔐 Authentication & Authorization
- 📱 Progressive Web App (PWA)
- 🌍 Responsive Design

---

## 🛠️ Tech Stack

| Technology | Version |
|------------|----------|
| Python | 3.x |
| Django | 3.2+ |
| PostgreSQL | Supported |
| SQLite | Supported |
| Gunicorn | Production |
| Nginx | Reverse Proxy |
| Docker | Supported |

---

## 📁 Project Structure

```
EduNova/
├── account/
├── financial/
├── main/
├── manager/
├── parent/
├── poll/
├── quiz/
├── student/
├── teacher/
├── templates/
├── static/
├── Dockerfile
├── docker-compose.yml
├── manage.py
└── requirements.txt
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/EduNova.git

cd EduNova
```

### Create Virtual Environment

```bash
python -m venv .venv
```

### Activate Environment

Windows

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Migrations

```bash
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Start Development Server

```bash
python manage.py runserver
```

---

## 🌐 Production Deployment

EduNova can be deployed using:

- Docker
- Docker Compose
- Gunicorn
- Nginx
- PostgreSQL

---

## 📸 Screenshots

Coming Soon...

---

## 🗺️ Roadmap

- [ ] Upgrade to Django 5
- [ ] REST API
- [ ] JWT Authentication
- [ ] Multi-language Support
- [ ] Multi-school Support
- [ ] Attendance System
- [ ] Online Assignments
- [ ] Online Exams
- [ ] Notifications
- [ ] Mobile Application

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the project and submit a Pull Request.

---

## 📄 License

This project is distributed under the MIT License.

See the LICENSE file for more information.

---

## ⭐ Support

If you find this project useful, please consider giving it a ⭐ on GitHub.

---

## 👨‍💻 Author

**EduNova Team**

Building the future of digital education.