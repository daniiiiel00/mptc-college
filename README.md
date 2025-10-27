# 🎓 MPTC College Registrar & Blog Site

A **Full Stack Web Application** for **MPTC College** that combines a **student registration system**, **college portfolio**, and **blog/news platform**.  
The portal streamlines the **college admission process**, **content publishing**, and **public communication** — built with modern web technologies.

---

## 🌐 Project Overview

The **MPTC College Registrar & Blog Site** is designed to:
- Digitize student registration and management.
- Share updates, news, and announcements through a blog system.
- Showcase the college’s achievements, courses, and facilities.
- Serve as an all-in-one platform for students, faculty, and visitors.

---

## 🚀 Key Features

### 🧑‍🎓 Student Module
- Online student registration form with validation.
- Secure database storage for student records.
- Registration confirmation and login system.
- Profile and academic info management.

### 📰 Blog & News System
- Admins can create, edit, and delete posts.
- Public users can read latest news and updates.
- Categorized blog posts (Events, Academics, Announcements, etc.)
- SEO-friendly URL and structured content layout.

### 🏛️ College Portfolio
- About the college, departments, and courses.
- Showcase staff members and leadership profiles.
- Gallery section with campus photos and events.
- Contact information and inquiry form.

### 🔒 Admin Dashboard
- Manage student records, blog posts, and messages.
- Approve or reject student registrations.
- Upload images and content through simple CMS.
- Secure login system with role-based access.

---

## 🧱 Tech Stack

| Technology | Role |
|-------------|------|
| **HTML5** | Structure and content layout |
| **CSS3 / SCSS** | Styling, layout, and responsive design |
| **JavaScript (Vanilla JS)** | Client-side validation and dynamic features |
| **PHP (Core)** | Backend logic, routing, and data handling |
| **MySQL / SQL** | Database for students, posts, and admin data |

---

## 🗄️ Database Structure (Overview)

**Tables:**
- `admins` – Stores admin login data
- `students` – Student registration records
- `blog_posts` – News and blog content
- `categories` – Blog post categories
- `messages` – Contact form submissions
- `gallery` – Media and images for portfolio

---

## ⚙️ Installation Guide

1. **Clone the Repository**
   ```bash
   git clone https://github.com/daniiiiel00/mptc-college.git
   
Move to the Project Directory

cd mptc-college-portal
Create a Database

Open phpMyAdmin

Create a new database (e.g. mptc_college_db)

Import the file database.sql from the project folder

Configure Database Connection
Edit config.php or db_connect.php:

$servername = "localhost";
$username = "root";
$password = "";
$dbname = "mptc_college_db";

Run on Local Server

Place the project folder in your htdocs (XAMPP) or www (WAMP) directory

Start Apache and MySQL

Open browser and visit:
http://localhost/mptc-college

| Role  | Username | Password   |
| ----- | -------- | ---------- |
| Admin | `admin`  | `admin123` |

🧭 Project Structure

mptc-college-portal/
│
├
│   ├── css/
│   ├── js/
│   ├── scss/
│   ├── images/
│
├── includes/
│   ├── index.html
│   ├── about.html
│   ├── regstration.html
│   |    course.html


📱 Responsive Design

Built with mobile-first design principles.

Optimized for desktop, tablet, and mobile devices.

Uses SCSS for cleaner, modular styling and easier theme customization.

🔧 Future Enhancements

Online student login portal for grades and attendance

Email verification and notifications

Comment system for blog posts

Admin activity logs

REST API integration for mobile access

👨‍💻 Author

Daniel Melese
Diploma in Web Development & Database Administration
🏆 Skilled in HTML, CSS, SCSS, JS, PHP, SQL, and Full Stack Web Development
📧 Email: danielmelese240@gmail.com
🌐 GitHub: https://github.com/daniiiiel00
