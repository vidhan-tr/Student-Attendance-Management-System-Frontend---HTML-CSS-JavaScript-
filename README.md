🧾 Description

A simple and efficient Student Attendance Management System built using vanilla JavaScript, HTML, and CSS.
This project allows users to add students, mark attendance (Present/Absent), and store all data in the browser using localStorage, ensuring persistence even after page refresh.




🚀 Features
➕ Add new students with auto-generated roll numbers
📅 Select date to mark attendance
✅ Mark students as Present or Absent
💾 Data stored in localStorage (no database required)
🔄 Persistent data even after page reload
🗑️ Option to delete/update data (extendable)
⚡ Dynamic UI updates without page refresh



🛠️ Tech Stack
HTML – Structure
CSS – Styling
JavaScript – Logic & DOM manipulation



🧠 How It Works
Student data is stored as an array of objects
Each student contains:
Roll number
Name
Attendance (date-wise object)
Data is saved using localStorage.setItem()
On page load, data is retrieved using localStorage.getItem()
UI is dynamically rendered using JavaScript
