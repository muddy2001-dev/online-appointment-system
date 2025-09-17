🏥 Online Appointment Booking System

The Online Appointment Booking System is a web-based application that allows patients to book medical appointments online and 
enables administrators (doctors/clinic staff) to manage them efficiently.

📌 Features

✔️ Admin and patient login
✔️ Role-based access (Admin/Patient)
✔️ Book, confirm, update, and cancel appointments (Patient)
✔️ Manage appointments, patients, and schedules (Admin)
✔️ Appointment status: Pending → Confirmed → Completed/Cancelled
✔️ Secure authentication (hashed passwords & sessions)
✔️ Search and filter appointments by  patient
✔️ Prevents double-booking

💻 Technologies Used

Frontend: HTML, CSS, JavaScript, Ajax

Backend: PHP / MySQL

Database: MySQL

🚀 How to Run

Import the database:

Run the file doctor.sql in your MySQL server.

Configure database connection:

Edit database.php and update your MySQL username, password, and DB name.

Place the project in your local server root directory:

C:\xampp\htdocs\doctor\


Start your local server (XAMPP/WAMP/Laragon).

Open the system in your browser:

Admin Login: http://localhost/doctor/index.php

Patient Login: http://localhost/doctor/patients/welcome.php

🔑 Demo Credentials

👨‍💼 Admin Login

Email: admin@example.com

Password: Admin@123

👩‍⚕️ Patient Login

Email: user@example.com

Password: User@123
