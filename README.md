# 📚 Smart Attendance System

A comprehensive **web-based Smart Attendance System** designed to streamline attendance management in educational institutions through role-based access, automation, and detailed reporting.

---

## 📌 Overview

The Smart Attendance System provides dedicated interfaces for **Students**, **Teachers**, and **Administrators** to efficiently manage class attendance, monitor attendance metrics, and generate professional reports. The system minimizes manual work and offers real-time insights into attendance patterns.

---

## 🎯 Project Objectives

- Automate attendance tracking for educational institutions
- Reduce manual paperwork and administrative overhead
- Provide real-time attendance insights
- Enable students to monitor their own attendance status
- Generate comprehensive attendance reports in **PDF format**

---

## ✨ Key Features

### 👨‍🎓 Student Features
- Submit attendance for active class sessions
- View attendance history across enrolled courses
- Monitor real-time attendance percentage
- Access session-wise attendance records

### 👨‍🏫 Teacher Features
- Create and manage class sessions
- Track student attendance per session
- Generate and download attendance reports (PDF)
- View attendance statistics and trends
- Manage assigned courses and enrollments

### 👨‍💼 Administrator Features
- Create and manage courses
- Assign teachers to courses
- View and manage all attendance records
- Oversee system-wide user activities
- Generate institution-wide attendance analytics

---

## 🛠 Technologies Used

- **Backend:** PHP  
- **Frontend:** HTML5, CSS3, JavaScript  
- **Database:** MySQL / MariaDB  
- **PDF Generation:** Dompdf (HTML to PDF)  
- **Server:** Apache (via XAMPP)

### 📦 Dependencies

- **Dompdf** – HTML to PDF converter  
  - Supports CSS 2.1  
  - Handles tables, images, and styled layouts  
  - Used for generating professional attendance reports

---

## ⚙️ Installation & Setup

### Prerequisites
- XAMPP (Apache, PHP, MySQL)
- PHP 7.1 or higher
- Modern web browser (Chrome, Firefox, Edge)

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shanewaz-Aurnob/Database.git
   ```

2. **Project Setup**
   - Move the project folder to `htdocs` directory in XAMPP
   - Rename the folder if necessary

3. **Database Configuration**
   - Create a new MySQL database
   - Import the provided database schema (if available)
   - Update database credentials in the configuration file

4. **Run the Application**
   - Start Apache and MySQL from XAMPP
   - Open your browser and navigate to:
     ```
     http://localhost/Database/index.php
     ```
   - Adjust the URL based on your project folder name

---

## 🚀 Usage Guide

### For Students
- Log in with student credentials
- View enrolled courses
- Submit attendance for active sessions
- Monitor attendance percentage
- Download attendance records (if enabled)

### For Teachers
- Log in with teacher credentials
- Access assigned courses
- Create class sessions
- Mark and manage attendance
- Download PDF attendance reports
- Analyze attendance trends

### For Administrators
- Log in with administrator credentials
- Manage courses and users
- Assign teachers to courses
- View institution-wide attendance data
- Generate comprehensive reports

---

## 🗂 Project Structure

```
Database/
├── index.php                 # Main entry point
├── config/                   # Configuration files
├── classes/                  # PHP classes
├── pages/                    # Application pages
├── assets/                   # CSS, JavaScript, images
├── dompdf/                   # PDF generation library
├── database/                 # Database schema & migrations
└── README.md                 # Project documentation
```

---

## 🕘 Previous Version Information

- **Original Project Name:** CUSAS (Class Attendance System)
- **Original Repository:** https://github.com/Shanewaz-Aurnob/CUSAS
- **Base Technologies:** PHP, HTML/CSS, JavaScript
- **Original Folder Name:** cusas

---

## 👥 Contributors

- **Shanewaz Aurnob** — Lead Developer
- **Raisa Nuzhat** — Database Design & Documentation
- **Ratri Barua** — Frontend Development
- **Ramisa Zahara Matin** — Testing & QA

---

## 🔮 Future Enhancements

- Mobile application (Android & iOS)
- QR code-based attendance system
- Biometric attendance integration
- Email & SMS notifications
- Advanced analytics and data visualization
- REST API for third-party integration
- Multi-language support

---

## ⚠️ Known Limitations

- PDF layout constraints due to Dompdf limitations
- Limited support for CSS Flexbox and Grid in PDFs
- Large file uploads may require server configuration tuning

---

## 📄 License

This project was developed as part of educational coursework and is shared for **academic and reference purposes**.

---

## 📬 Support & Contact

For issues, questions, or contributions, please open an issue in the repository or contact the development team.
