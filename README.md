# Simple Website with Admin Panel

This is a simple website with admin functionality, user accounts, and mobile responsiveness. It's built using PHP and SQLite for easy local development.

## Features
- User registration and login
- Admin panel with CRUD operations for posts
- Responsive design for various mobile devices (iPhone, Samsung, Xiaomi)
- SQLite database for easy setup
- Mobile-first CSS design

## Setup Instructions

1. Install XAMPP on your computer
2. Clone this repository to your XAMPP's htdocs folder
3. Start XAMPP's Apache server
4. Visit http://localhost/[folder-name] in your browser
5. The database will be automatically created when you first access the site

## Admin Account Setup

To create an admin account:
1. Register a new account through the website
2. Use SQLite database browser to modify the user's `is_admin` field to 1

## File Structure
- index.php - Home page
- login.php - User login
- register.php - User registration
- logout.php - Logout functionality
- css/style.css - Styles including mobile responsiveness
- config/database.php - Database configuration
- admin/
  - dashboard.php - Admin control panel
  - new_post.php - Create new posts
  - edit_post.php - Edit existing posts

## Mobile Support
- Responsive design works on various screen sizes
- Specific media queries for:
  - iPhone devices
  - Samsung Galaxy phones
  - Xiaomi phones