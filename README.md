# 👋 Hi, I'm Soniya Lingam

### 💻 Aspiring Software Developer | Full-Stack Developer | B.Tech IT Student

<p align="left">
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="YOUR_GITHUB_URL">
    <img src="https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github" />
  </a>
  <a href="mailto:YOUR_EMAIL">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail" />
  </a>
</p>

---

## 👩‍💻 About Me

I am a **B.Tech Information Technology student** passionate about software development, full-stack web applications, and problem solving.

I enjoy transforming real-world requirements into practical software solutions and continuously improving my skills across frontend development, backend development, databases, and programming.

- 🎓 **B.Tech Information Technology (2027)** – National Engineering College
- 💻 Aspiring **Full-Stack Developer**
- 🚀 Currently focusing on **MERN Stack Development**
- 🧠 Strong interest in **Problem Solving & Data Structures**
- 👥 **Vice President – Computer Society of India (CSI)**
- 🤝 **IT Association Executive Member**
- 🌱 Continuously learning and exploring modern technologies

---

# 🚀 Featured Project

## 🎓 Gatepass Management System

> **A full-stack MERN application designed to digitize and streamline student gatepass, leave, attendance, approval, and parent communication processes.**

The **Gatepass Management System** is a role-based web application that connects **Students, Parents, Tutors, HODs, Wardens, and Administrators** through a centralized platform.

The system replaces manual gatepass and leave management with a structured digital workflow.

### 🎯 Problem Statement

Traditional college gatepass and leave processes can involve:

- Manual paperwork
- Time-consuming approval processes
- Delayed parent communication
- Difficulty tracking attendance
- Lack of centralized information
- Difficulty managing different user roles

### 💡 Solution

The Gatepass Management System provides a centralized platform where students can submit leave requests, parents can authenticate using OTP, and authorized staff can review, approve, and manage leave and attendance information efficiently.

---

### ✨ Key Features

| Feature | Description |
|---|---|
| 🔐 Role-Based Access | Separate access for Admin, HOD, Tutor, Warden, Parent and Student |
| 📱 Parent OTP Login | Secure OTP-based parent authentication |
| 📝 Leave Management | Students can submit ordinary and emergency leave requests |
| ✅ Approval Workflow | Authorized staff can review and approve leave requests |
| 📊 Attendance Tracking | Centralized student attendance management |
| 📧 Email Notifications | Automated notifications for important leave activities |
| 🔒 Protected Routes | Authentication-based access to application modules |
| 📁 File Upload | Support for file uploads using Multer |
| 📊 Excel Processing | Excel data processing using XLSX |
| 🔄 REST APIs | Structured communication between frontend and backend |
| 📱 Responsive UI | User-friendly interface across different screen sizes |

---

### 🛠️ Technology Stack

#### Frontend

![React](https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-671DD8?style=for-the-badge&logo=axios&logoColor=white)

#### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

#### Database

![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)

#### Authentication & Utilities

![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

### 🏗️ Application Architecture

```text
                         ┌─────────────────────┐
                         │      Users          │
                         │                     │
                         │ Student | Parent    │
                         │ Tutor | HOD | Warden│
                         │ Admin                │
                         └──────────┬──────────┘
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │     React.js        │
                         │     Frontend        │
                         │   Vite + Tailwind   │
                         └──────────┬──────────┘
                                    │
                              RESTful APIs
                                    │
                                    ▼
                         ┌─────────────────────┐
                         │ Node.js + Express   │
                         │      Backend        │
                         └──────────┬──────────┘
                                    │
                  ┌─────────────────┼─────────────────┐
                  │                 │                 │
                  ▼                 ▼                 ▼
           ┌────────────┐   ┌─────────────┐   ┌─────────────┐
           │  MongoDB   │   │    JWT +    │   │    Email    │
           │ + Mongoose │   │     OTP     │   │ Notifications│
           └────────────┘   └─────────────┘   └─────────────┘
