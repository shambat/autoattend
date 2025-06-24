🎓 SHAM University - AutoAttend 📋
Welcome to the official repository for SHAM University AutoAttend, a lightweight, client-side exam attendance portal built using HTML, JavaScript, and TailwindCSS. Developed as part of a cybersecurity student's learning journey, this project demonstrates a simple and secure attendance system with localStorage-based persistence.
🔒 Test Admin Credentials:  

Username: admin  
Password: pass


⚠️ Warning: This project is for educational and ethical testing only. Do not deploy in a production environment without proper security measures.

🔗 Live Demo:👉 https://shambat.github.io/autoattend/

📌 Features

🔐 Admin Login ModalSecure login modal with role-based access control (currently hardcoded for testing).

🧑‍🎓 Student ID VerificationStudents enter their 4-digit ID to mark attendance.

✅ Eligibility CheckingAutomatically verifies student eligibility based on preloaded data.

🪑 Seat Allocation DisplayDisplays subject name and assigned seat in a clean, formatted style.

📁 CSV ExportExports attendance logs for the current day in .csv format.

🗑️ Reset FunctionClears all attendance logs from local storage after confirmation.

🕒 Live Clock DisplayShows the current time on the dashboard in real-time.

💾 LocalStorage IntegrationStores attendance data in the browser's local storage.



📚 Technologies Used

HTML5  
Tailwind CSS (via CDN)  
Vanilla JavaScript  
Browser LocalStorage API


📂 Project Structure
.
├── index.html       # Main application file
├── README.md        # Project documentation
└── /                # Hosted via GitHub Pages


🚀 How to Use

Visit the live app: AutoAttend Live
Log in using the test credentials:
Username: admin
Password: pass


Enter a 4-digit student ID (e.g., 1001) to verify and mark attendance.
Use the Download button to export attendance data as a .csv file for the current day.
Use the Reset button to clear all local data (use with caution).


⚙️ Future Enhancements

🔒 Backend integration with Python Flask or Node.js.
🛡️ JWT-based authentication for secure admin login.
🗃️ Persistent storage with SQLite or MongoDB.
🧠 AI-based facial recognition for attendance via webcam.
📈 Admin dashboard with analytics (e.g., present vs. absent students).
📧 Email notifications for ineligible students.
🧪 Penetration testing and vulnerability reports integration.


📌 Sample Student Data



ID
Name
Eligibility
Subject
Seat



1001
Ali Raza
Eligible
Mathematics
4,E


1002
Fatima Noor
Not Eligible
Physics
7,B


1003
Hassan Ali
Eligible
Chemistry
3,A


1004
Maria Khan
Not Eligible
Biology
5,D


1005
Ahmed Bilal
Eligible
English
6,C



ℹ️ Full student data is available in the students[] array in the index.html file.


📢 Disclaimer
This application is for educational and demonstration purposes only. The login credentials are intentionally exposed for front-end testing. Do not use in production without implementing secure authentication and backend validation.

🙌 Author
Muhammad EhtishamFinal Year Cybersecurity Student – Air University 🇵🇰📧 Email: connectsham95@gmail.com🌐 Website: www.ehtisham.space🔗 LinkedIn: linkedin.com/ehtishamcyber


💡 “Security is not a product, but a process.” – Bruce Schneier💬 Strong passwords make brute-forcing a hacker's nightmare!
