🚗 DriveEasy Car Rental – Django Web Application
DriveEasy Car Rental is a full-stack web application developed using Python, Django, and the Django REST Framework. It is designed to streamline the process of renting cars online through a user-friendly interface and an efficient backend system. This project demonstrates how modern web development frameworks can be used to build scalable, secure, and interactive systems for real-world applications.

The system supports user authentication, including signup, login, and logout functionality with session-based access control. Users can browse a list of available cars, view details, and book their preferred vehicle. A key feature is the OTP-based password reset via email, implemented using Gmail's SMTP server and Django's email backend. The integration ensures security and convenience for users who need to recover their accounts.

For administrators, the project leverages Django's powerful admin interface to manage car listings, bookings, and registered users without needing direct database access. Car availability is updated automatically based on bookings, and records can be easily added, edited, or removed through the admin dashboard.

On the frontend, the system uses HTML, CSS, Bootstrap, and JavaScript to create responsive and interactive web pages. The design is clean and mobile-friendly, ensuring usability across devices. Additionally, the project integrates RESTful APIs using Django REST Framework, allowing for future expansion, such as mobile app integration or third-party service connections.

This project was developed for academic purposes and demonstrates best practices in Django development, including modular code structure, API usage, session handling, and user-centric features. It serves as a solid foundation for further improvements, such as payment gateway integration, Google Maps, role-based permissions, and mobile app development.
🔧 Features
User registration and login with session handling

OTP-based password reset via email (SMTP)

Car listing with dynamic availability

Booking system with user-specific history

Admin panel for managing cars, users, and bookings

REST API integration for scalable architecture

Responsive frontend using HTML, CSS, Bootstrap

JavaScript-enhanced forms and interactions

🛠️ Tech Stack
Backend: Python, Django, Django REST Framework

Frontend: HTML, CSS, Bootstrap, JavaScript

Database: SQLite with Django ORM

Email Service: Gmail SMTP

Tools: VS Code, Django Admin
