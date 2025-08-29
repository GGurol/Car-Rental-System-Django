Car Rental System (Django) : Forked from https://github.com/RipudamanM/Car-Rental-System-Django/tree/master

## GGurol's notice:

should be fixed:
    -add cars section to admin panel
    -prince is static, fix this
        *current calculation : cost_per_day = int(vehicle.capacity)*13 ( customer_portal/views.py )
    -car search : make like on search
    -on rent, show the price on view.

!!! if you having problem when "docker compose up --build" with "docker ps" show the correct outputs but "localhost:8000" has "no connection" error, try:

	-docker compose stop
	-docker compose up


==========================

This is a Car Rental Management System built using Django. The system allows customers to book cars online, manage bookings, and view car availability. Admins can manage car listings, booking statuses, and customer information.

Features
--------

- User registration and login
- Browse available cars
- Book a car with start and end dates
- View and manage bookings
- Admin panel for managing:
  - Car listings
  - Booking requests
  - User details

Tech Stack
----------

- Backend: Django
- Frontend: HTML, CSS, Bootstrap
- Database: SQLite (default for Django)

How to Run
----------

1. Clone the repository and extract the `.rar` file.
2. Navigate to the project directory.
3. Install dependencies:
   pip install -r requirements.txt
4. Run migrations:
   python manage.py migrate
5. Start the server:
   python manage.py runserver
6. Open http://127.0.0.1:8000/ in your browser.

Admin Login
-----------

Default admin credentials (if provided):
Username: admin
Password: admin123

Or create your own superuser:
    python manage.py createsuperuser
