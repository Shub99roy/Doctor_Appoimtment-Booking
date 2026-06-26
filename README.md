# Full-Stack Doctor Appointment Booking System

A secure, responsive, and performant multi-tier web application engineered using the MERN stack. This platform implements robust Role-Based Access Control (RBAC) to isolate workflows across discrete dashboards tailored for Administrators, Medical Staff (Doctors), and Patients.

---

## 🚀 Key Features

* **Multi-Role Authentication & Authorization:** Implemented strict Role-Based Access Control (RBAC) using JSON Web Tokens (JWT) and secure cookie storage to split dashboards into Admin, Doctor, and Patient views.
* **Conflict-Free Scheduling Engine:** Engineered a robust backend algorithm to process real-time appointment bookings, dynamically checking availability windows to eliminate double-booking conflicts.
* **Administrative Control Panel:** Comprehensive CRUD management panel allowing administrators to onboard verified medical staff, manage global clinic schedules, and audit system-wide bookings.
* **Doctor Workspace:** Tailored interface for doctors to manage incoming patient queues, update individual appointment statuses, and track personal daily agendas.
* **Patient Portal:** Seamless user experience enabling patients to filter verified doctors by specialty, review open time slots, and self-schedule or track their medical appointments.
* **Fully Responsive UI:** Crafted utilizing React and Tailwind CSS, guaranteeing rapid page load speeds and fluid user experiences across desktop and mobile screen viewports.

---

## 🛠️ Tech Stack

* **Frontend:** React.js, Tailwind CSS, HTML5, CSS3, Vite
* **Backend:** Node.js, Express.js, RESTful API Design
* **Database:** MongoDB (Schema Optimization & Object Modeling via Mongoose)
* **Authentication:** JSON Web Tokens (JWT), Crypto-hashed Passwords
* **Deployment & Tooling:** Git, Postman, Vercel / Render

---
<img width="1920" height="864" alt="Screenshot (50)" src="https://github.com/user-attachments/assets/4431c2ae-5da2-4a00-8825-5c0363075895" />

<img width="1920" height="858" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/44e8853f-feb8-4586-85be-4b9e06fbf56d" />
<img width="1920" height="856" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/54110c7d-fc78-4405-b601-5473d596623c" />


<img width="1920" height="874" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/5edb8dbb-4300-4868-96bf-28c5b488c622" />



<img width="1920" height="861" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/a62cc23d-98b1-4f36-9835-8d83ca09bf68" />

<img width="1920" height="856" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/5496dc17-6fca-4595-a0e8-1239c8615686" />


## 📂 Architecture & Directory Structure

```text
├── backend/
│   ├── config/          # Database connection & environmental configurations
│   ├── controllers/     # Core business logic for users, doctors, and slots
│   ├── middleware/      # Auth verification and RBAC route protection
│   ├── models/          # Optimized MongoDB database schemas
│   ├── routes/          # RESTful API endpoints
│   └── server.js        # Application entry point
│
└── frontend/
    ├── src/
    │   ├── components/  # Modular, reusable UI elements
    │   ├── context/     # Global state management for user authentication
    │   ├── pages/       # Dashboard and portal view layouts
    │   └── App.jsx      # React router and application layout mapping







