Event Management System

Project Description

The Event Management System is a web application developed using Python and Django. This application provides an intuitive platform for users to manage events seamlessly, including creating, booking, and viewing upcoming events. It also includes user authentication for secure access and role-based functionalities.

Features

User Features:

Event Browsing: View a list of available events.

Event Booking: Book tickets for available events.

User Registration and Login: Secure user authentication and account creation.

Personalized Dashboard: View your booking history and upcoming events.

Admin Features:

Event Management: Create, edit, and delete events.

Booking Management: View and manage user bookings.

User Management: Manage registered users and their roles.

Technologies Used

Backend: Python, Django Framework

Frontend: HTML5, CSS3, JavaScript, Bootstrap

Version Control: Git



Prerequisites

Before running the project, ensure you have the following installed:

Python (version 3.8 or above)

Django (version 4.0 or above)

Git




Prerequisites

Before running the project, ensure you have the following installed:

Python (version 3.8 or above)

Django (version 4.0 or above)

Git

Installation and Setup

Clone the repository:

git clone https://github.com/yourusername/event-management-system.git
cd event-management-system

Create and activate a virtual environment:

python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate

Install required dependencies:

pip install -r requirements.txt

Apply database migrations:

python manage.py makemigrations
python manage.py migrate

Create a superuser for admin access:

python manage.py createsuperuser

Run the development server:

python manage.py runserver

Open the application in your browser:

http://127.0.0.1:8000/


Future Enhancements

Payment Integration: Add payment gateways for booking confirmation.

Event Notifications: Notify users about upcoming events via email.

Search and Filter: Allow users to search and filter events based on categories, dates, and locations.

Multi-Language Support: Support multiple languages for a wider audience.



