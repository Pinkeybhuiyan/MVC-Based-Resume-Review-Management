### **Project Name:** Resume Review Management System

#### **Overview**

The **Resume Review Management System** is a robust, full-stack web application designed to streamline the workflow between job seekers looking for professional feedback, expert reviewers, and system administrators. Built using a strict **Model-View-Controller (MVC)** architectural pattern, the application ensures a clean separation of concerns, high maintainability, and secure data handling.

#### **Key Features & Architecture**

* **Strict MVC Pattern:** Organized systematically into configuration (`config/`), database logic (`models/`), business logic and routing (`controllers/`), user interfaces (`views/`), and styling assets (`assets/`).
* **Role-Based Access Control (RBAC):** Implements dedicated, secure dashboards tailored for three distinct user roles:
* **Admins:** Manage users, oversee system-wide statistics, and assign resumes to reviewers.
* **Reviewers:** Evaluate candidate CVs and provide professional grading or feedback.
* **Job Seekers:** Upload resumes, track review statuses, and view feedback.


* **Secure Authentication & Session Management:** Features secure user login/registration, password hashing, custom session tracking, and a cookie-based **"Remember Me"** functionality with automatic session recovery and clean destruction on logout.
* **Interactive Security & Account Recovery:** Built-in multi-step account recovery workflows utilizing personalized security questions and unique database identification.
* **Client & Server-Side Validation:** Form inputs are reinforced with JavaScript validation for instant user feedback alongside server-side verification to maintain data integrity.

#### **Tech Stack**

* **Backend:** PHP (Procedural/Modular architecture with MySQLi)
* **Database:** MySQL
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Environment:** Apache/PHP Local Server environment
