Hospital Management System

Overview:

This is a Hospital Management System project developed using Java and JDBC (Java Database Connectivity) to manage and automate various operations in a hospital. The system enables different users, such as Admins, Doctors, and Receptionists, to log in and perform specific role-based actions such as managing patients, appointments, and hospital staff efficiently.

Features:

Role-based access: Admins, Doctors, and Receptionists have different access levels and functionalities.
User authentication: Secure login system that verifies users from the database.
Patient management: Add, update, and delete patient records.
Appointment scheduling: Manage doctor appointments for patients.
Doctor management: View doctor schedules, update information, and assign duties.
Database integration: Utilizes MySQL for database storage and retrieval using JDBC.

Setup and Installation:

1. Clone the repository:
git clone https://github.com/yourusername/hospital-management-system.git

2. Database setup:

Install MySQL.
Run the SQL scripts located in the resources/schema.sql file to create the necessary database tables.
Update the database connection details in the HospitalManagementSystem.java file or a configuration file.

3. Run the application:

Compile and run the Java application.
javac src/HospitalManagementSystem.java
java src/HospitalManagementSystem

Database Schema:

The project uses a MySQL database with the following main tables:

users: Stores login credentials and roles (admin, doctor, receptionist).
patients: Manages patient information such as name, age, and medical history.
doctors: Manages doctor profiles, specializations, and schedules.
appointments: Manages patient appointments with doctors.

Technologies Used:

Java
JDBC (Java Database Connectivity)
MySQL
Swing (for GUI)

Future Enhancements:

Implement search functionality for finding patients or doctors by name.
Add billing management for patient treatments.
Improve the UI design with more advanced features.


Contributing:

Contributions are welcome! Please feel free to submit a Pull Request
License
This project is licensed under the MIT Licens

Contact
For any inquiries, reach out to me at vansh070605@gmail.com
