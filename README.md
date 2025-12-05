# abet
ABET: A custom-built, full-stack application using Pure PHP/MySQL to provide automated business consultation and expert analysis.

# ABET - Information-Business Expert System

An advanced, web-based expert system designed to assist aspiring entrepreneurs in properly planning business processes, understanding legal and financial requirements, and automatically obtaining market analysis data. ABET helps citizens start and manage their businesses effectively.

## 🚀 Quick Setup Guide

### 📋 Prerequisites
- **XAMPP** (Includes Apache, MySQL, PHP 7.4 or higher)
- Web Browser (Chrome, Firefox, Edge)

### Installation Steps

1. **Start XAMPP Services**
    - Open the XAMPP Control Panel.
    - Start **Apache** and **MySQL** services.

2. **Database Initialization**
    - Open your browser and navigate to: `http://localhost/my/install.php`
    - The `install.php` page will automatically create and configure the necessary database structure.

3. **System Access (Login)**
    - Access the login page via URL: `http://localhost/my/auth/login.php`
    - **Default Credentials:**
        - **Email:** `admin@abet.uz`
        - **Password:** `admin123`

4. **Security Notice (Crucial!)**
    - After the successful installation, **delete the `install.php` file** from the `/my/` directory immediately to prevent unauthorized database modifications.

---

## 🛠️ Technological Stack

ABET is built on a simple, robust, and proven stack:

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Backend Logic** | **PHP (Pure PHP/PDO)** | Core business logic and database communication. |
| **Frontend/UI** | **Bootstrap 5** | Responsive design and component styling. |
| **Database** | **MySQL 8.x** | Data storage and management. |
| **Iconography** | **Feather Icons** | Clean and modern vector icons. |
| **Data Visualization**| **Chart.js** | Generating interactive charts for analysis modules. |

---

## ✨ Key Features & Modules

ABET is designed around comprehensive modules to cover all stages of business initiation:

1.  **Diagnosis and Direction Selection**
2.  **Business Plan Generator**
3.  **Financial Analysis and Forecasting**
4.  **Risk Assessment Module**
5.  **Tax System Recommendations**
6.  **Market Analysis & Segmentation**
7.  **Permit and License Guide**
8.  **Knowledge Base (FAQ/Articles)**
9.  **User Cabinet (Personalized Dashboard)**
10. **Admin Panel (System Management)**

### User Roles

The system utilizes three primary user roles:

* **Super Admin:** Full system oversight and control.
* **Expert:** Manages content, business directions, and expert recommendations.
* **Entrepreneur:** The primary user, utilizing business planning and analysis tools.

---

## 👨‍💻 Development Guidelines

If you wish to contribute to the project:

1.  Edit or modify existing code files as required.
2.  Any database changes **must** be documented and added to `database/schema.sql`.
3.  Place new modules or significant features into the corresponding directory (e.g., `entrepreneur/`, `expert/`).

## ⚠️ Troubleshooting

**Database Connection Error:**
-   Verify your MySQL service is running in XAMPP.
-   Check database configuration settings in the `config/database.php` file.

**Page Not Found / Access Error:**
-   Ensure the Apache service is running.
-   Confirm the URL is correctly entered: `http://localhost/my/`

---

## 📜 License

This project is created and maintained for **educational purposes** only.
---

## 📂 File Structure Overview

The project follows a modular structure for easy navigation and scaling:
