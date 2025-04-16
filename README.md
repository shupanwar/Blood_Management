# Blood Bank Management System

The **Blood Bank Management System** is a Django-based web application designed to streamline the process of blood donation, request, and stock management. It allows users to register as donors, request blood in emergencies, and helps admins monitor blood availability efficiently.

---
## Features

- Donor registration with blood group, contact details, and availability
- Blood request form for patients or hospitals
- Admin panel for managing donors, requests, and stock
- Search feature for available blood types
- Authentication for both users and admin
- Mobile-friendly, responsive design

---

## Technologies Used

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default), can be upgraded to MySQL/PostgreSQL
- **Other Tools**: Git, GitHub, VS Code

---

## Screenshots

> (Add your own real screenshots in a folder called `screenshots/` and update these links accordingly.)

### Home Page
![Home](https://github.com/user-attachments/assets/7eb6ac4c-510f-4f9d-8af9-397d1008b4c4)

### Donor Registration
![Donor Signup](https://github.com/user-attachments/assets/020a4fec-4f69-4f70-b060-561682b45b5f)

### Blood Request Form
![Blood Request](https://github.com/user-attachments/assets/befa0904-aec3-452f-9f33-eff339ec8298)

### Admin Dashboard
![admindashboard](https://github.com/user-attachments/assets/eefb0b0a-f367-41a8-81ff-34bbb74520b1)

---

## Setup Instructions

1. **Clone the Repository**
   ```bash
    git clone https://github.com/your-username/blood-bank.git
   cd blood-bank
2. **Create a Virtual Environment**
   
   python -m venv env
   
   source env/bin/activate   # Mac/Linux
   
   env\Scripts\activate      # Windows
   
3. **Install Requirements**
   
    pip install -r requirements.txt
   
4. **Run Migrations**
   
    python manage.py migrate

5. **Create Superuser**
   
    python manage.py createsuperuser

6. **Start Development Server**
   
    python manage.py runserver
   
7. **Access the Application**
   
    Main site: http://127.0.0.1:8000/
   
    Admin panel: http://127.0.0.1:8000/admin/


Folder Structure
   
   blood-bank/
   
   │
   
   ├── bloodbank/         # Main project settings
   
   ├── core/              # Your app (models, views, templates)
   
   ├── templates/         # HTML templates
   
   ├── static/            # Static files (CSS, JS, images)
   
   ├── media/             # Uploaded media (if any)
   
   ├── db.sqlite3         # SQLite DB
   
   ├── requirements.txt   # Python dependencies
   
   ├── .gitignore
   
   ├── README.md


License

   This project is licensed under the MIT License — see the LICENSE file for details.

Author

   Shubham Parmar
   
   Full-Stack Developer
   

