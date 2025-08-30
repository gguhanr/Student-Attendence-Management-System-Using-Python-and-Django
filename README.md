# 🎓 Student-Attendence-Management-System-Using-Python-and-Django

A **Student Attendance Management System** built using **Python (Django Framework)** for educational purposes.  

👉 If you find this project useful, don’t forget to **⭐ Star this repository!**  

---

## ✨ Features  

### 👨‍💼 Admin (HOD)  

1. Dashboard with summary charts of **Students, Staff, Courses, Subjects, Attendance, and Leaves**.  
2. Manage Staff (Add / Update / Delete).  
3. Manage Students (Add / Update / Delete).  
4. Manage Courses (Add / Update / Delete).  
5. Manage Subjects (Add / Update / Delete).  
6. Manage Sessions (Add / Update / Delete).  
7. View and track student attendance.  
8. Review and respond to feedback from Staff/Students.  
9. Approve or Reject leave applications (Staff/Students).  

### 👨‍🏫 Staff / Teachers  

1. Dashboard with summary charts of **Students, Subjects, Attendance, and Leaves**.  
2. Take and Update Student Attendance.  
3. Add / Update Student Results.  
4. Apply for Leave.  
5. Send Feedback to HOD.  

### 👩‍🎓 Students  

1. Dashboard with summary charts of **Attendance, Subjects, and Leave Status**.  
2. View Attendance Records.  
3. View Results.  
4. Apply for Leave.  
5. Send Feedback to HOD.  

---

## ⚙️ Installation & Setup  

### ✅ Pre-Requisites  

- [Git](https://git-scm.com/)  
- [Python (Latest Version)](https://www.python.org/downloads/)  
- [Pip (Package Manager)](https://pip.pypa.io/en/stable/installing/)  
  _(Alternative: Homebrew on Mac)_  

---

### 📌 Steps to Install  

#### 1️⃣ Create a Project Folder  
Choose a folder location and create a new directory.  

#### 2️⃣ Setup Virtual Environment  

Install Virtual Environment:  
```sh
pip install virtualenv
```

Create Virtual Environment:  

- **Windows**  
```sh
python -m venv venv
```

- **Mac/Linux**  
```sh
python3 -m venv venv
```

Activate Virtual Environment:  

- **Windows**  
```sh
venv\Scripts\activate
```

- **Mac/Linux**  
```sh
source venv/bin/activate
```

#### 3️⃣ Clone the Repository  

```sh
git clone https://github.com/ritikbanger/django-student-attendance-system.git
cd django-student-attendance-system
```

#### 4️⃣ Install Dependencies  

```sh
pip install -r requirements.txt
```

#### 5️⃣ Configure Allowed Hosts  

Open **settings.py** and update:  
```python
ALLOWED_HOSTS = ['*']
```

#### 6️⃣ Run the Server  

- **Windows**  
```sh
python manage.py runserver
```

- **Mac/Linux**  
```sh
python3 manage.py runserver
```

#### 7️⃣ Setup Admin Credentials  

Create a Superuser (HOD):  
```sh
python manage.py createsuperuser
```
Then enter **Email, Username, Password**.  

Or use default login credentials:  

- **HOD / SuperAdmin**  
  - Email: `admin@gmail.com`  
  - Password: `admin`  

- **Staff**  
  - Email: `staff@gmail.com`  
  - Password: `staff`  

- **Student**  
  - Email: `student@gmail.com`  
  - Password: `student`  

---

## 🤝 Support the Developer  

- ⭐ Star this repository if you like the project!  
- Contributions are welcome — feel free to **Fork & Pull Request**.  

---

## 📜 License  

This project is licensed under the **MIT License**.  

```
Copyright (c) 2022 Ritik Banger

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions...
```

---

🚀 Developed by **@ritikBanger, @mohitTaimni, and @ronitKhowal**  
👨‍🎓 For **Poornima Group, Jaipur**  

