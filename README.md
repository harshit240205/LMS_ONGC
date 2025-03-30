# LMS_ONGC

# Library Management System

A modern web-based Library Management System built with PHP, MySQL, and Bootstrap. This system helps libraries manage their books, users, and book lending operations efficiently.

## Features

### User Features
- User registration and login
- Book search and browsing
- Book request system
- View issued books
- Profile management
- Password change functionality
- Dark/Light mode toggle

### Admin Features
- Admin login
- Book management (Add, Edit, Delete)
- User management
- Issue/Return book management
- View all issued books
- Generate reports
- System settings

## Software Requirements

- XAMPP (Apache + MySQL + PHP)
- PHP 7.0 or higher
- MySQL 5.6 or higher
- Modern web browser (Chrome, Firefox, Safari, Edge)

## Installation Steps

1. **Install XAMPP**
   - Download and install XAMPP from [https://www.apachefriends.org/](https://www.apachefriends.org/)
   - Start Apache and MySQL services from XAMPP Control Panel

2. **Clone/Download Project**
   - Clone this repository or download the ZIP file
   - Extract the files to `C:/xampp/htdocs/Library-Management-System/`

3. **Database Setup**
   - Open your web browser and go to `http://localhost/phpmyadmin`
   - Create a new database named `library`
   - Import the `library.sql` file from the project directory
   - The database will be created with all necessary tables

4. **Access the System**
   - Open your web browser
   - Go to `http://localhost/Library-Management-System`
   - You can now access the system

## Default Login Credentials

### Admin Login
- Username: admin
- Password: admin123

### User Registration
- Users can register themselves through the signup page
- After registration, they can login with their credentials

## Key Functionalities

### Book Management
- Add new books with details (title, author, ISBN, etc.)
- Edit existing book information
- Delete books from the system
- Search books by title, author, or category

### User Management
- User registration and authentication
- Profile management
- Password change
- View issued books history

### Book Lending System
- Issue books to users
- Track return dates
- Handle book returns
- View all issued books

### Modern UI Features
- Responsive design
- Dark/Light mode toggle
- Modern dashboard
- User-friendly interface
- Interactive notifications

## Security Features
- Password hashing
- Session management
- Input validation
- SQL injection prevention
- XSS protection

## File Structure
```
Library-Management-System/
├── admin/                 # Admin panel files
├── assets/               # CSS, JS, and images
├── includes/             # Common PHP files
├── library.sql          # Database schema
├── index.php            # Main entry point
           
```

## Contributing
Feel free to submit issues and enhancement requests!


## Support
For support, please contact the system administrator or create an issue in the repository. 
