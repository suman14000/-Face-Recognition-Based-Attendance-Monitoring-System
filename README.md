# -Face-Recognition-Based-Attendance-Monitoring-System
This project is a Face Recognition Based Attendance Monitoring System designed to automate attendance tracking in classrooms or organizations using facial recognition technology. The system captures student images, recognizes faces in real-time, and marks attendance efficiently while generating daily and weekly reports.

📷 Features
🔐 New Registration
Register new students by capturing facial images.
Save student ID and Name to the database.

📸 Take Attendance
Automatically detects and recognizes registered faces.
Marks attendance with date and time.

🧾 Attendance Management
Displays live attendance records in a table format.
Allows deletion of old attendance data and images.
Generates CSV files for registrations and attendance.
Sends attendance reports via email to the HOD.

📊 Absentee Tracking
Identifies and lists absent students.
Easy monitoring of class-wise presence.

🛠️ Tech Stack
Language: Python
Libraries:
OpenCV (face detection & recognition)
Tkinter (GUI)
Pandas (data handling)
NumPy
smtplib (email sending)
Database: CSV files (can be replaced with MySQL or SQLite)

📌 How to Use
Run the program.
Register a new user by entering ID and Name, then capture facial images.
Click Take Attendance to detect and mark students present.
Export or email attendance records as needed.
