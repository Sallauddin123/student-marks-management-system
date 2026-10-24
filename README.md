# 🎓 EduTrack – Student Marks Management System

A responsive student portal where students can sign up, log in, and manage their **profile, attendance, marks and fee details** – and generate a downloadable **student ID card** from their profile.

Built with **HTML, CSS and JavaScript** (no frameworks, single file).

## ✨ Features

- **Landing page** with login / sign-up pop-up
- **Sign up** with full name, roll number, branch, section, email, phone, parent's number and password
- **Strong password rule**: 8+ characters, a capital letter, a number and a special symbol (live checklist)
- **Passwords are hashed** (SHA-256) – never stored as plain text
- **Dashboard** with attendance ring, average marks and grade, fee progress and subject-wise charts
- **Editable sections**: Profile, Attendance, Marks and Fees (add, edit, delete rows and save)
- **Profile photo upload**
- **Student ID card** (photo, name, roll number, course, section, phone, parent's phone, barcode) with **PNG download**
- **Themes**: 5 colour themes + light / dark mode
- **Admin panel**: view and edit any student's records
- Fully responsive (desktop sidebar, mobile bottom navigation)

## 🛠 Tech stack

HTML5 · CSS3 (variables, grid, flexbox) · Vanilla JavaScript · Web Crypto API · Canvas API · localStorage

## 🚀 Run locally

1. Download or clone this repository
2. Open `index.html` in any browser – no installation needed

## 🔐 Admin access

Click **Admin** in the top bar and enter the admin password.
The default password is set in `index.html` (`ADMIN_PASS`) – **change it before publishing**.

## ⚠️ Note on data storage

This demo stores data in the browser's **localStorage**, so accounts exist only on the device where they were created. It is meant for learning and portfolio use – do not store real student data in it.

## 🔮 Future improvements

- Flask / Node backend with a MySQL database and server-side authentication
- Role-based access (student, teacher, admin)
- Export marks and attendance as PDF / Excel
- Email notifications for attendance shortage and fee due dates

## 📸 Screenshots

Add screenshots here (landing page, dashboard, ID card):

```
![Landing page](screenshots/landing.png)
![Dashboard](screenshots/dashboard.png)
![ID card](screenshots/id-card.png)
```

## 👤 Author

**Sallauddin Patan** – B.Tech ECE · Python · MySQL · JavaScript
🔗 LinkedIn: _add your profile link_
