FitZone Fitness Center Web Application

Project Overview  
FitZone Fitness Center is a modern web application designed to digitally manage gym operations. It gives customers the ability to register, log in, book memberships, schedule personal training, submit queries, and explore services online. The platform also supports staff and administrators, who can manage trainers, classes, appointments, and respond to customer interactions through dedicated dashboards.

––––––––––––––––––––––––––––––

Key Features  
• Secure user authentication with password hashing  
• Membership booking and management system  
• Personal training booking with trainer and package selection  
• Class management including yoga, cardio, and strength training  
• Customer query system with staff/admin responses  
• Admin and staff dashboard for complete control  
• Responsive design for mobile and desktop access  

––––––––––––––––––––––––––––––

Technologies Used  
Frontend: HTML5, CSS3, JavaScript  
Backend: PHP 8+, MySQL  
Database Management: phpMyAdmin  
Server: Apache (XAMPP/LAMP)  

––––––––––––––––––––––––––––––

Project Structure  
• index.php – Homepage  
• about.php – About Us Page  
• services.php – Services Offered  
• membership.php – Membership Plans  
• contact.php – Contact Us Page  
• gallery.php – Gallery Showcase  
• login.php – User Login  
• register.php – User Registration  
• dashboard.php – Customer Dashboard  
• admin/ – Admin and Staff Pages  
• includes/ – DB connection, helper functions  
• styles.css – Main Stylesheet  
• fitzone_db.sql – Database setup script  

––––––––––––––––––––––––––––––

Database Setup  
1. Open phpMyAdmin.  
2. Import the file fitzone_db.sql from the project folder.  
3. Required tables will be created (users, memberships, services, queries, appointments).  

––––––––––––––––––––––––––––––

Installation Guide  
1. Download or clone the project folder.  
2. Move it into the XAMPP htdocs directory (or your LAMP/Apache root).  
3. Start Apache and MySQL.  
4. Import fitzone_db.sql into phpMyAdmin.  
5. Run the project in your browser at: http://localhost/fitzone/  

––––––––––––––––––––––––––––––

User Roles  
• Customer – Register, login, book memberships, classes, and submit queries.  
• Staff – Manage queries, view appointments, respond to users.  
• Admin – Manage trainers, services, memberships, and oversee entire system.  

––––––––––––––––––––––––––––––

Contact  
For questions, support, or contributions, reach out to the FitZone Fitness Center Development Team.  

This README provides setup details, project usage, and role descriptions for the application.
