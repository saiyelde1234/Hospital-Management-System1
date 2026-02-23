<img width="1920" height="3525" alt="Home" src="https://github.com/user-attachments/assets/e3c4bd65-d28f-42ed-a5b4-a3c188fcd611" /># 🏥 Hospital Management System (HMS)

A web-based Hospital Management System built using **Python (Flask)**, **SQLite**, and **Razorpay API** to digitize and streamline hospital operations like appointment booking, doctor management, and automated communication.

🔗 **Live Demo**: [Life Care Clinic](https://hospital-management-system1-92b2.onrender.com)

---

## 📌 Features

- 🌐 Responsive web UI with HTML, CSS, Tailwind, and JavaScript
- 👨‍⚕️ Doctor profile viewing for patients
- 🗓️ Patient appointment booking system
- 🔐 Secure login and role-based access (Patient/Admin)
- 🧑‍💼 Admin dashboard to manage doctors, appointments, messages
- 📧 Email notifications (Appointment approved/cancelled)
- 💳 Razorpay payment integration for online fee payment

---

## 🎯 Aim

To design and develop a user-friendly hospital management system that improves communication and efficiency in hospital operations.

---

## 🎯 Objectives

1. Provide an online platform for patients to book appointments and access hospital info.
2. Enable admins to manage doctors, appointments, and contact messages securely.
3. Implement secure, role-based login for both patients and admins.

---

## 🧰 Tools & Technologies Used

### Front-End:
- HTML5 – Page structure
- CSS3 – Styling
- Tailwind CSS – Responsive UI
- JavaScript – Client-side interactivity
- Jinja2 – Templating engine

### Back-End:
- Python (Flask) – Web framework
- SQLite – Lightweight, file-based database

### Other Tools:
- Render – Deployment platform
- Git & GitHub – Version control and collaboration
- Gmail SMTP – Automated email delivery
- VS Code – Code editor

---

## 📐 System Design Overview

### 👥 User Roles:
- **Patient:** Can register, log in, view doctors, and book appointments.
- **Admin:** Can log in securely to manage doctor info, appointments, contact messages, and send status updates.

### 🖥️ Pages:
- **Home:** Overview and navigation
- **About Us:** Hospital background and mission
- **Doctors:** Doctor profiles and specializations
- **Appointments:** Booking form for patients
- **Contact Us:** Feedback/contact form
- **Admin Dashboard:** Manage bookings and messages

---

## 🔁 Functional Workflow

1. Patients register/login and request an appointment.
2. Admin reviews the request and approves or cancels it.
3. Upon approval, the system sends a email.
4. Admin can track all interactions from a single dashboard.

---

## 📧 Email Notification System

- ✔️ **Appointment Approved**: Sends confirmation email .
- ❌ **Appointment Cancelled**: Sends cancellation notification.

---

## 💡 Future Enhancements

- 📄 Digital prescriptions
- 🔔 Real-time push notifications
- 📱 Mobile app integration

---

## ✅ Result

The system provides a streamlined interface for hospital staff to manage appointments and patient queries efficiently, while patients experience a faster, digital-first healthcare booking process.

---

## 🏁 Deployment

This project is deployed using **Render** with support for Flask, SQLite, email services, and payment integration.

🔗 **Deployed Link**: [Life Care Clinic](https://hospital-management-system1-92b2.onrender.com)

---

## 📸 Snapshots 

### 🏠 Homepage
![Homepage Screenshot]("\Downloads\Home.png")
*Figure 1: Homepage with navigation to About, Doctors, and Appointments*



### 📄 About Us Page

![About Us]("\Downloads\About.png")

*Figure 2: About Us page showing hospital mission, values, and achievements.*

---

### 👨‍⚕️ Doctor Details Page

![Doctor Details](static/images/screenshots/screencapture-127-0-0-1-4518-doctors-2025-05-05-02_19_10.png)

*Figure 3: List of doctors with their specialization, qualifications, and experience.*

---

### 📅 Appointment Booking Form

![Appointment Form](static/images/screenshots/screencapture-127-0-0-1-4518-appointments-2025-05-05-02_19_28.png)

*Figure 4: Patient appointment form to select doctor, date, and time.*

---

### 🔐 Admin Login Page

![Admin Login](static/images/screenshots/screencapture-127-0-0-1-4518-admin-login-2025-05-05-02_27_42.png)

*Figure 5: Secure login page for hospital administrators.*

---

### 📊 Admin Dashboard

![Dashboard](static/images/screenshots/screencapture-127-0-0-1-4518-dashboard-2025-05-05-02_35_18.png)

*Figure 6: Admin panel to manage appointments, messages, and status updates.*

---

### 📧 Email Notifications

![Email Notification - Approved](static/images/screenshots/approved.jpg)

*Figure 7: Email sent to patient after appointment approval with Razorpay link.*

![Email Notification - Cancelled](static/images/screenshots/cancelled.jpg)

*Figure 8: Email sent to patient notifying them of appointment cancellation.*

---


