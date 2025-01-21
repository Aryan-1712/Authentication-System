# Authentication-System
## Overview

This is a basic authentication system website built using Django. The system includes functionality for user login and logout.

## Features

- **User Authentication:**
  - Secure login and logout functionality.
  - Session-based authentication.
- **Home Page:**
  - Displays a welcome message after login.
- **Login Page:**
  - Users can log in with their credentials.
- **Logout:**
  - Users can securely log out of their accounts.
- **Admin Panel:**
  - The superuser can manage users and view authentication logs.

## Technologies Used

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default Django database)

## Installation Instructions

1. Clone the repository:
   
   git clone https://github.com/Aryan-1712/Authentication-System.git
   
2. Navigate to the project directory:
   
   cd Authentication-System
   
3. Create a virtual environment:
   
   python -m venv venv
   
4. Activate the virtual environment:
   - On Windows:
   
     venv\Scripts\activate
   
   - On macOS/Linux:
   
     source venv/bin/activate
   
5. Install dependencies:
   
   pip install -r requirements.txt
   
6. Run database migrations:
   
   python manage.py migrate
   
7. Create a superuser to access the admin panel:
   
   python manage.py createsuperuser
   
8. Run the development server:
   
   python manage.py runserver
   
9. Open the website in your browser:
   
   http://127.0.0.1:8000
   

## Usage

1. Navigate to the login page and enter your credentials.
2. After logging in, users will be redirected to the home page.
3. Users can log out using the logout button.
4. Admins can log in via `/admin/` to manage users.

## Folder Structure


AuthProject/
│-- manage.py
│-- AuthApp/
│   ├── migrations/
│   ├── static/
│   ├── templates/
│   ├── admin.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│-- db.sqlite3
│-- requirements.txt
│-- README.md


## Contributing

Contributions are welcome! Feel free to submit pull requests or report issues.

## Contact

For any questions, please feel free to reach out via GitHub.
