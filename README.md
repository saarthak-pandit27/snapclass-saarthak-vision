📸 SnapClass — AI-Powered Attendance & Classroom Management System

Welcome to SnapClass — an AI-powered attendance and classroom management platform designed to automate student attendance using Face Recognition, Voice Biometric Verification, and QR-based enrollment.

🌐 Live Application: SnapClass

⸻

🌟 Key Features

* 🤖 AI Face Recognition: Automatically identify students and mark attendance.
* 🎙️ Voice Biometric Verification: Additional identity verification using voice.
* 📱 QR-Based Student Enrollment: Fast and convenient student registration.
* 👨‍🏫 Teacher Dashboard: Manage students, subjects, and attendance records.
* 👨‍🎓 Student Dashboard: View profile, subjects, and attendance history.
* 🔐 Authentication System: Secure student and teacher login workflows.
* 📊 Attendance Management: Automated digital attendance tracking.
* 📷 Real-Time Camera Processing: Live camera-based AI verification.
* ☁️ Cloud-Ready Architecture: Designed for modern web deployment.

⸻

🛠️ Built With

* Python — Core application and AI logic.
* Streamlit — Interactive web application.
* OpenCV — Computer vision and image processing.
* MediaPipe — Real-time vision processing.
* Streamlit-WebRTC — Real-time camera streaming.
* Supabase — Authentication and backend services.
* PostgreSQL — Persistent database.
* Git & GitHub — Version control and deployment.

⸻

🧠 AI & System Workflow

Student
   │
   ▼
QR Enrollment
   │
   ▼
Authentication
   │
   ├───────────────┐
   ▼               ▼
Face Recognition   Voice Verification
   │               │
   └───────┬───────┘
           ▼
    Identity Verified
           │
           ▼
   Attendance Marked
           │
           ▼
     Database Storage
           │
           ▼
   Teacher / Student
       Dashboard

⸻

📂 Repository Structure

SnapClass/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── assets/
│   ├── images/
│   ├── icons/
│   └── css/
│
├── components/
│   ├── student/
│   ├── teacher/
│   └── dashboard/
│
├── services/
│   ├── authentication/
│   ├── face_recognition/
│   ├── voice_verification/
│   └── attendance/
│
├── database/
│   ├── connection.py
│   └── queries.py
│
├── models/
│   └── biometric_models/
│
├── utils/
│   ├── helpers.py
│   └── validators.py
│
└── data/

⸻

🚀 Local Development Setup

1. Clone the Repository

git clone https://github.com/YOUR-USERNAME/SnapClass.git
cd SnapClass

2. Create Virtual Environment

python -m venv .venv

Activate it:

macOS / Linux

source .venv/bin/activate

Windows

.venv\Scripts\activate

3. Install Dependencies

pip install -r requirements.txt

4. Configure Environment Variables

Create a .env file and add your required credentials:

SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key

⚠️ Never commit API keys, database credentials, or other secrets to GitHub.

5. Run the Application

streamlit run app.py

The application will start at:

http://localhost:8501

⸻

📊 Project Highlights

SnapClass demonstrates practical implementation of:

Artificial Intelligence • Computer Vision • Biometric Authentication • Real-Time Processing • Database Management • Cloud Deployment • Web Application Development

⸻

🔮 Future Enhancements

* 🚨 Liveness detection against photo/video spoofing.
* 📈 Advanced attendance analytics.
* 🔔 Automated low-attendance notifications.
* 📱 Dedicated mobile application.
* 🧠 AI-powered student performance insights.
* 🏫 Multi-institution support.
* 🔐 Advanced biometric security.

⸻

👨‍💻 Developer

Saarthak Pandit

B.Tech Artificial Intelligence & Machine Learning
Amity University Punjab

* 📧 Email: panditsaarthak586@gmail.com
* 💼 LinkedIn: linkedin.com/in/saarthak-pandit-a7b7a4319
* 🐙 GitHub: @saarthak-pandit27

⸻

⭐ Support

If you find SnapClass useful or interesting:

⭐ Star the repository
🍴 Fork the project
🐛 Report issues
💡 Suggest improvements

⸻

<p align="center">

📸 SnapClass

Smarter Attendance. Smarter Classrooms.

Built & Engineered by Saarthak Pandit © 2026

</p>
