# 📌 Student Attendance Management System

A simple and efficient **Student Attendance Management System** built using **HTML, CSS, and JavaScript**.  
This project helps you manage student attendance with date-wise tracking and stores data in the browser using **localStorage**.

---

## 🚀 Features

- ➕ Add new students with auto-generated roll numbers  
- 📅 Select date to manage attendance  
- ✅ Mark students as **Present** or **Absent**  
- 💾 Data stored in browser using **localStorage**  
- 🔄 Data persists even after page refresh  
- ⚡ Dynamic UI updates without reloading  
- 🗑️ Easy to extend (delete/edit features can be added)

---

## 🛠️ Tech Stack

- **HTML** – Structure  
- **CSS** – Styling  
- **JavaScript** – Logic & DOM manipulation  
 

---


## 🧠 How It Works

- Students are stored as objects inside an array  
- Each student contains:
  - Roll Number  
  - Name  
  - Attendance (stored date-wise)  

- Data is saved using:
  ```js
  localStorage.setItem("students", JSON.stringify(students));



