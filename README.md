
# ParkSpero - Melbourne Parking App

## 📌 Project Overview
ParkSpero is a Django-based web application that provides live parking availability, historical analytics, and demand prediction for Melbourne streets.


## 📂 Project Structure
```
 └── parkingapp-django/
     ├── config/                # Django project configuration
     ├── main/                  # Main application
     │   ├── services/          # Business logic and API services
     │   ├── static/            # Static files (CSS, JS, images)
     │   ├── templates/         # HTML templates
     │   └── views/             # Django views
     ├── venv/                  # Virtual environment
     ├── manage.py              # Django management script
     ├── requirements.txt       # Python dependencies
     └── db.sqlite3             # SQLite database (for dev)
```


## 🚀 Setup Instructions
### 1️⃣ Clone the repository


!git clone https://github.com/Kevin951113/ParkSpero-Melbourne.git
%cd ParkSpero-Melbourne


### 2️⃣ Create a Virtual Environment
#### Windows (PowerShell)


!python -m venv venv
!.env\Scripts\Activate


#### Mac/Linux


!python3 -m venv venv
!source venv/bin/activate


### 3️⃣ Install dependencies


!pip install -r requirements.txt


### 4️⃣ Run the Django server


!python manage.py runserver


## 💻 Access the App
Once the server starts, open your browser and visit:
```
http://127.0.0.1:8000
```


## 📌 Notes
- The database (`db.sqlite3`) is for local development only.
- Static files are located in `main/static/`.
- HTML templates are located in `main/templates/`.
- Business logic for analytics, predictions, and live parking updates is inside `main/services/`.

✅ You’re now ready to use ParkSpero locally!


<img width="1896" height="718" alt="image" src="https://github.com/user-attachments/assets/29a41107-96b5-4ca4-bd87-19595769c9a5" />

<img width="1903" height="853" alt="image" src="https://github.com/user-attachments/assets/4d17be77-9a77-405d-bc7f-287e89ef3167" />

<img width="1848" height="832" alt="image" src="https://github.com/user-attachments/assets/f327a301-f21b-43fb-a809-5bdeaa88ca80" />

<img width="1878" height="715" alt="image" src="https://github.com/user-attachments/assets/d7952b97-2c5b-4873-be44-eb62cf7a4cae" />




