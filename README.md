📝 EduPortal - Student Management & Admin Dashboard
EduPortal is a lightweight, frontend-driven Student Registration System designed for educational institutions. It features a secure dual-access architecture that separates the student experience from administrative management, all powered by modern Vanilla JavaScript and browser storage.

🚀 Key Features
👨‍🎓 Student Portal
Secure Access: Students log in using unique credentials (Roll No & Email) to view only their specific registration details.

Data Privacy: No public data leakage; students cannot see records of other students.

Withdrawal Requests: Instead of direct deletion, students submit a formal "Withdrawal Request" with a reason, which is sent to the Admin for review.

🛡️ Admin Dashboard
Centralized Control: A master view of all registered students in a clean, tabular format.

Advanced Search: Real-time filtering system to find students by Name, Roll Number, or Department instantly.

Request Management: A dedicated section to review student comments and withdrawal reasons.

Database Management: Full authority to delete individual records or clear the entire database.

🛠️ Tech Stack
HTML5: Semantic structure for accessibility.

CSS3: Custom styling with a modern, responsive "Glassmorphism" inspired UI.

JavaScript (ES6+): Pure Vanilla JS for DOM manipulation and logic.

LocalStorage: Persistent data storage without the need for a backend server.

SessionStorage: Secure session handling to protect private routes.

📂 Project Structure
Plaintext

├── index.html       # Student Registration Form (Home)
├── login.html       # Dual-login gateway (Student/Admin)
├── data.html        # Private Student View / Success Page
├── admin.html       # Secure Admin Control Panel
├── style.css        # Global styles and Dashboard layouts
└── README.md        # Project documentation
⚙️ How to Use
Registration: Navigate to index.html and fill out the student registration form.

Student Login: * Go to the Login page.

Enter the Roll Number and Email used during registration.

View your data or submit a withdrawal request.

Admin Access:

Go to the Login page and select "Admin Access."

Default Username: admin

Default Password: 1234

Manage the database and view student requests.

📝 Future Roadmap
[ ] Integration with Firebase for real-time cloud storage.

[ ] PDF Generation for student registration receipts.

[ ] Profile Picture upload functionality.

[ ] Email notifications using EmailJS.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.
