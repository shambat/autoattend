# 🎓 SHAM University - AutoAttend | Web-Based Exam Attendance Portal

AutoAttend is a lightweight, front-end based web application designed to streamline exam attendance for SHAM University. It demonstrates the implementation of a secure and user-friendly exam attendance system using **HTML5**, **Tailwind CSS**, and **Vanilla JavaScript**.

This project was developed as part of a cybersecurity student’s academic initiative to explore secure client-side operations and UI development, incorporating browser-based data handling with `localStorage`.

---

## 🔐 Admin Credentials for Testing

> ⚠️ *For ethical testing and demonstration purposes only.*

```
Username: admin  
Password: pass
```

---

## 🔗 Live Deployment

Deployed via GitHub Pages:  
🔗 [https://shambat.github.io/autoattend/](https://shambat.github.io/autoattend/)

---

## 📌 Core Features

- **Admin Login Panel**  
  Secured modal login interface (credentials hardcoded for demonstration).

- **Student ID Validation**  
  Marks attendance through a 4-digit Student ID input with real-time verification.

- **Eligibility Enforcement**  
  Automatically checks each student's eligibility status from a static dataset.

- **Seat Allocation View**  
  Displays assigned seat and subject information upon verification.

- **CSV Export Capability**  
  Exports the current day’s attendance to a downloadable `.csv` file.

- **Real-Time Clock Display**  
  Live clock for monitoring check-in times.

- **LocalStorage Integration**  
  Attendance records are maintained client-side using browser localStorage.

- **System Reset Function**  
  Clears all stored attendance data with user confirmation.

---

## 🧰 Technologies Used

- `HTML5` – Semantic and structured markup  
- `Tailwind CSS` – Utility-first styling using CDN  
- `JavaScript (ES6)` – Front-end logic and data handling  
- `localStorage` – Client-side data persistence

---

## 📁 Project Structure

```
.
├── index.html         # Main application interface
├── README.md          # Project documentation
└── /                  # Hosted via GitHub Pages
```

---

## 🚀 Usage Instructions

1. Open the [live application](https://shambat.github.io/autoattend/)
2. Login using:
   - Username: `admin`
   - Password: `pass`
3. Enter a valid 4-digit student ID (e.g., `1001`)
4. If the student is eligible:
   - Attendance is marked
   - Subject and seat number are displayed
5. Use "Download Today’s Records" to export `.csv`
6. Use "Reset App" to clear all attendance logs (with confirmation prompt)

---

## 📊 Sample Dataset

Below is a subset of the preloaded dataset (`students[]`) embedded in the application.

| ID   | Name           | Eligibility   | Subject            | Seat |
|------|----------------|---------------|---------------------|------|
| 1001 | Ali Raza       | Eligible      | Mathematics         | 4,E  |
| 1002 | Fatima Noor    | Not Eligible  | Physics             | 7,B  |
| 1003 | Hassan Ali     | Eligible      | Chemistry           | 3,A  |
| 1004 | Maria Khan     | Not Eligible  | Biology             | 5,D  |
| 1005 | Ahmed Bilal    | Eligible      | English             | 6,C  |

> *Full dataset is available in the `index.html` under the `students[]` array.*

---

## 🔐 Security & Ethical Disclaimer

This system is intended for educational use only and is not secure for production deployment.  
- Admin credentials are hardcoded for demonstration.  
- There is no backend or encrypted authentication mechanism.  
- Do not store or process real student data in its current form.

> Production-ready implementations must include:
> - Backend authentication (e.g., Flask, Node.js)
> - Encrypted credential storage (e.g., bcrypt)
> - Secure session handling and audit logs
> - Database-backed record keeping

---

## 🧩 Planned Enhancements (v2.0 Roadmap)

- Backend API integration (Flask or Node.js)
- JWT-based authentication
- MongoDB/SQLite support for persistent records
- Admin dashboard with attendance analytics
- Facial recognition-based student validation (ML integration)
- Email notification system for ineligible students
- Role-based access and logs for auditing

---

## 👤 Author

**Muhammad Ehtisham**  
Final Year Cybersecurity Student – Air University, Pakistan  
📧 Email: [connectsham95@gmail.com](mailto:connectsham95@gmail.com)  
🌐 Portfolio: [www.ehtisham.space](https://www.ehtisham.space)  
🔗 LinkedIn: [linkedin.com/in/ehtishamcyber](https://linkedin.com/in/ehtishamcyber)

---

## 🧠 Quote

> “Security is not a product, but a process.” — *Bruce Schneier*  
> *AutoAttend empowers secure attendance marking with simplicity and clarity.*
