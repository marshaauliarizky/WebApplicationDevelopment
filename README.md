# PinkBite Restaurant Queue & Reservation Management System

PinkBite is a web-based restaurant queue and reservation management application developed as a group project for the **Web Application Development** course.  
This system helps restaurants manage customer queues, table availability, reservations, and menu administration efficiently through a role-based platform for both admins and customers.

The application supports real-time queue tracking, automatic table assignment based on party size, reservation scheduling, and complete CRUD management for restaurant operations.


## Key Features

### Admin Features
Admins have access to a full dashboard to manage restaurant operations, including:

- Secure admin login with role-based access control  
- View summary statistics (total queue, tables ready, tables in use, reservations today)  
- Manage walk-in queue entries (Call, Assign Table, Track Status)  
- Table management with full CRUD operations  
  - Add, edit, delete, and free tables  
- Reservation management  
  - View upcoming reservations  
  - Seat customers instantly  
  - Update reservation status  
  - Delete or edit reservations  
- Menu management with image upload support (CRUD)


### Customer Features
Customers can interact with the restaurant system through:

- Registration and login system  
- View personal dashboard and profile  
- Take queue numbers and monitor queue status  
- Browse queue history  
- Create reservations with date, time, and party size  
- View latest reservation confirmation  
- Logout securely  


## System Highlights

- Role-based access control (Admin vs Customer)  
- Automatic table assignment based on party size and availability  
- Real-time updates for queue, reservations, and table status  
- Centralized database design with relational structure  
- User-friendly UI with Bootstrap and SweetAlert2 feedback alerts  
- Secure authentication using password hashing and verification  


## Tech Stack

- **Frontend:** HTML, CSS, Bootstrap  
- **Backend:** PHP  
- **Database:** MySQL  
- **UI Enhancements:** SweetAlert2, AOS Animations  
- **Server Environment:** Apache (XAMPP/WAMP)


## Database Structure (ERD Overview)

Main entities in the system include:

- Users (Admin & Customer authentication)
- Customers (Customer profiles)
- Tables (Restaurant seating management)
- Queue (Walk-in queue tracking)
- Reservations (Booking system)
- Table Assignments (Links queue/reservation to tables)
- Menu (Restaurant menu items)


## Main Modules

- `admin_dashboard.php` → Admin overview, queue/table/reservation management  
- `admin_menu.php` → CRUD menu management with image uploads  
- `queueing.php` → Customer queue system  
- `reservation.php` → Reservation submission and confirmation  
- `assign_table.php` → Automatic table allocation logic  
- `login.php` / `register.php` → Authentication system  


## Installation & Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/pinkbite-system.git
