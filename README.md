# tripmanager

```markdown
# TripPlanner

TripPlanner is a full-stack travel booking website built with PHP, HTML, CSS, JavaScript, and MySQL. It provides users with the ability to book travel packages, manage their profiles, and perform various other actions. Admin users have enhanced privileges to manage the site, including package creation and user interaction.

## Features

### User Registration and Authentication
- Account Creation: Users can sign up to create new accounts.
- Login/Logout: Secure login and logout functionality.
- Password Reset: Users can reset their passwords if forgotten.

### Travel Package Booking
- Browse Packages: View available travel packages.
- Book Packages: Book your desired travel packages.

### User Dashboard
- Profile Management: Update profile information.
- Booking History: View past bookings and manage account details.

### Admin Panel
- Admin Login: Special access for administrators to manage the site.
- Package Management: Create, edit, and delete travel packages.
- Data Management: View user data, manage inquiries, and respond to user questions.

### Interactive User Interface
- Responsive Design: User-friendly design with responsive layouts for various devices.

### Database Management
- MySQL Database: Utilizes MySQL to store user data, bookings, packages, and inquiries.

## Getting Started

To get started with TripPlanner, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/eresdesre/tripmanager
cd tripmanager
```

### 2. Database Setup

- Create a MySQL Database**: Name the database `tripplanner`.
- Import the Database Schema: Use the `database.sql` file to set up the database schema and initial data.

```bash
mysql -u yourusername -p tripplanner < database/tripplanner.sql
```

### 3. Configuration

- Update Configuration: Open `includes/config.php` and update it with your database connection details.

### 4. Run the Project

- Start a Local Development Server: You can use PHP's built-in server or a local server environment like XAMPP or MAMP.
  
  ```bash
  php -S localhost:8000
  ```

- Access the Application**: Open your browser and go to `http://localhost:8000/` to view the site.

## Usage

- For Users:
  - Register a new account or log in if you already have one.
  - Browse and book travel packages.
  - Update your profile and manage bookings.

- For Admins:
  - Navigate to the admin login page to access the admin panel.
  - Manage travel packages, view user data, and handle inquiries.

## Contributing

If you want to contribute to TripPlanner, fork the site and add new features...
