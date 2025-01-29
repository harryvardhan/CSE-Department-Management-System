# CSE-Department-Management-System
## Description
The **CSE Department Management System** is a web-based platform for managing student and faculty interactions. Faculty can upload study materials, mark attendance, and manage records, while students access resources and track progress. It ensures secure authentication and efficient academic management.

## Overview
The **CSE Department Management System** is a web-based platform designed to streamline student and faculty interactions. It allows faculty members to upload study materials, mark attendance, and manage student records, while students can access course content and track their academic progress.

## Features
- **Admin Dashboard**: Manage faculty and student data.
- **Faculty Dashboard**: Upload study materials, mark attendance, and update sessional marks.
- **Student Portal**: Access study materials, attendance records, and sessional marks.
- **Secure Authentication**: Separate login pages for admin, faculty, and students.
- **Database Integration**: Uses MySQL for storing user information and academic records.

## Technologies Used
- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL

## Installation & Setup

### 1. Clone the Repository
```sh
   git clone https://github.com/yourusername/CSE-Department.git
   cd CSE-Department
```

### 2. Set Up the Database
1. Open **phpMyAdmin** or any MySQL database manager.
2. Create a new database named `cse_department`.
3. Import `cse_department.sql` into the database.

### 3. Configure Database Connection
- Open `db_connection.php` and update the database credentials:
```php
$servername = "localhost";
$username = "your_username";
$password = "your_password";
$dbname = "cse_department";
```

### 4. Run the Application
- Start a local server using XAMPP or any other PHP server.
- Place the project files in the `htdocs` directory (if using XAMPP).
- Open `http://localhost/CSE-Department/` in a browser.

## Folder Structure
```
CSE-Department/
│── css/                # Stylesheets
│── js/                 # JavaScript files (if any)
│── php/                # Backend PHP scripts
│── sql/                # Database schema and queries
│── index.html          # Homepage
│── aboutus.html        # About Us page
│── admin_dashboard.php # Admin panel
│── faculty_dashboard.php # Faculty panel
│── db_connection.php   # Database connection file
```

## Security Considerations
- Avoid storing plain text passwords; use hashing (`password_hash()` in PHP).
- Move sensitive credentials to environment variables.
- Implement session management to prevent unauthorized access.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For any queries, feel free to contact **Harsh Vardhan Tiwari** at [harrytiw10@gmail.com](mailto:harrytiw10@gmail.com).

