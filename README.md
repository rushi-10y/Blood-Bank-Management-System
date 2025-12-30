🩸 Blood Bank & Organ Management System

A web-based Blood Bank and Organ Management System built using Flask and SQLite, designed to efficiently manage blood donors, organ donors, user authentication, and requests through a simple and user-friendly interface.

🚀 Features

🔐 User Registration & Login (Secure Authentication)

🧑‍⚕️ Donor Management (Blood & Organ Donors)

🏥 Blood & Organ Availability Tracking

📋 Request Management System

🗄️ SQLite Database Integration

🎨 Responsive UI using HTML, CSS & Bootstrap

🔒 Password Hashing for Security

🛠️ Tech Stack

Backend: Python (Flask)

Frontend: HTML, CSS, Bootstrap

Database: SQLite

ORM: SQLAlchemy

Security: Werkzeug Password Hashing

📁 Project Structure
BloodBank-and-Organ-Management/
│
├── myapp1.py              # Main Flask application
├── instance/
│   └── users.db           # SQLite database
├── static/
│   ├── css/
│   └── images/
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── ...
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/BloodBank-and-Organ-Management.git
cd BloodBank-and-Organ-Management

2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install flask flask-sqlalchemy werkzeug

4️⃣ Run the Application
python myapp1.py

5️⃣ Open in Browser
http://127.0.0.1:5000/

🧪 Default Database

Uses SQLite

Database file auto-created as:

instance/users.db

🔐 Security Features

Passwords stored using hashed encryption

Session-based authentication

Flash messages for alerts & feedback

📸 Screenshots (Optional)

Add screenshots here to improve project presentation

🌱 Future Enhancements

Email & SMS notifications

Role-based access (Admin / User / Hospital)

API integration

Cloud database support

Mobile application version

👨‍💻 Author

Rushikesh Kulkarni
🎓 B.Tech CSE, Parul University
💼 Aspiring Full-Stack / AI Engineer

📄 License

This project is for educational purposes.
You are free to modify and use it.
