# 📚 Smart Attendance System

## Overview

This is a comprehensive web-based **Smart Attendance System** designed to streamline the attendance management process in educational institutions. The system provides a role-based interface for students, teachers, and administrators to efficiently manage class attendance, generate reports, and track attendance metrics.

## Project Description

A web-based smart attendance system that allows students to submit their attendance, teachers to create sessions for classes, and administrators to manage courses and view detailed attendance reports. Built with a focus on ease of use and comprehensive reporting capabilities, this system reduces manual attendance tracking and provides real-time insights into student attendance patterns.

### Key Objectives

- **Automate attendance tracking** for educational institutions
- **Reduce manual paperwork** and administrative overhead
- **Provide real-time attendance insights** to teachers and administrators
- **Enable students** to monitor their own attendance status
- **Generate comprehensive attendance reports** in PDF format

## Features

### 👨‍🎓 Student Features
- **Attendance Submission**: Students can easily submit their attendance for each class session
- **Attendance Tracking**: View personal attendance records across all enrolled courses
- **Percentage Calculation**: Monitor real-time attendance percentage for each course
- **Session History**: Access historical attendance data

### 👨‍🏫 Teacher Features
- **Session Creation**: Create class sessions and manage attendance for enrolled courses
- **Attendance Management**: Track which students attended each class
- **Report Generation**: Download comprehensive attendance reports in PDF format
- **Course Management**: Manage assigned courses and student enrollments
- **Analytics**: View attendance trends and statistics

### 👨‍💼 Administrator Features
- **Course Management**: Create and manage courses across the institution
- **Teacher Assignment**: Assign teachers to specific courses
- **Attendance Records**: View and manage attendance records for all class sessions
- **System Administration**: Oversee all system activities and user management
- **Comprehensive Reports**: Generate institution-wide attendance analytics

## Technologies Used

- **Backend**: PHP
- **Frontend**: HTML5, CSS3, JavaScript
- **PDF Generation**: Dompdf (HTML to PDF converter)
- **Database**: MySQL/MariaDB (recommended)
- **Server**: Apache (via XAMPP)

### Dependencies

The project includes **Dompdf** library for PDF report generation:
- **Dompdf**: HTML to PDF converter with CSS 2.1 support
- Supports complex table layouts, images, and styling
- Enables professional attendance report generation

## Installation

### Prerequisites
- **XAMPP** (or similar AMP stack with Apache, PHP, MySQL)
- **PHP 7.1 or higher**
- **Web browser** (Chrome, Firefox, Safari, Edge)

**Install XAMPP:

Download from Apache Friends
Install and start Apache and MySQL services
Configure the project:

Place the cloned folder in your XAMPP htdocs directory
Rename or configure the folder path accordingly
Setup Database:

Create a new MySQL database for the project
Import the database schema (if provided)
Update database connection credentials in the configuration file
Access the application:

Open your browser and navigate to: http://localhost/Database/index.php
Or adjust the URL based on your folder name in htdocs
Usage
For Students
Log in with your student credentials
View available courses
Submit attendance for active sessions
Monitor your attendance percentage
Download your attendance records if available
For Teachers
Log in with your teacher credentials
Navigate to your assigned courses
Create new class sessions
Mark attendance for each session
Download attendance reports in PDF format
Review attendance statistics and trends
For Administrators
Log in with administrator credentials
Create and manage courses
Assign teachers to courses
Manage user accounts
View institution-wide attendance reports
Generate comprehensive analytics
Project Structure
Code
Database/
├── index.php                 # Main entry point
├── config/                   # Configuration files
├── classes/                  # PHP classes
├── pages/                    # Application pages
├── assets/                   # CSS, JavaScript, images
├── dompdf/                   # PDF generation library
├── database/                 # Database schema and migrations
└── README.md                 # This file
Previous Version Information
Original Project Name: CUSAS (Class Attendance System)

Original Repository: https://github.com/aurnob101/CUSAS
Previous Implementation: Web-based attendance management system
Base Technologies: PHP, HTML/CSS, JavaScript
Previous Folder: cusas
Contributing
This project was developed collaboratively by:

Shanewaz Aurnob - Lead Developer
Raisa Nuzhat - Database Design & Documentation
Ratri Barua - Frontend Development
Ramisa Zahara Matin - Testing & QA
Future Enhancements
 Mobile application for iOS and Android
 Biometric attendance integration
 Email notifications for attendance alerts
 Advanced analytics and data visualization
 API for third-party integrations
 Multi-language support
 SMS notifications
 QR code-based attendance
Known Limitations
Current PDF generation has some layout constraints (inherited from Dompdf)
CSS Flexbox and Grid layouts have limited support in PDF reports
Large file uploads may require server configuration adjustments
License
This project is part of educational coursework and is shared for reference purposes.

Support & Contact
For questions, issues, or contributions, please contact the development team or create an issue in the repository.**

### Setup Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Shanewaz-Aurnob/Database.git
