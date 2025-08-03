# 📁 Personal Information Management System

> 🗃️ A mini DBMS project to manage personal information using **MongoDB**, **Node.js**, and a simple **web interface**.

---

## 🚀 Tech Stack   

- 🟢 **Node.js** – Backend logic & server
- 🍃 **MongoDB** – NoSQL database for storing personal info
- 🎨 **HTML + CSS** – Frontend structure & styling
- ✨ **JavaScript** – Interactive UI & API handling

---

## 💡 Features

- 📝 Add, edit, and delete personal information
- 🔍 View all records in a clean UI
- 🌐 RESTful API with MongoDB integration
- 🎯 Simple, clean, and beginner-friendly code

---

## 🛠️ How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/Divya-Darshan/DBMS-mini-project.git

2. Install dependencies:
   ```bash
   npm install
   node app.js
   npm audit fix
   npm audit

3. Run the server
      ```bash
      npm start

4. All in one Note : "This command won't work on Windows PowerShell" 
    ```bash
   for /f "tokens=14 delims= " %a in ('ipconfig ^| findstr "IPv4"') do (git clone https://github.com/Divya-Darshan/DBMS-mini-project.git && cd DBMS-mini-project && npm i && npm audit fix && npm audit && color 1F && cls &&  echo Choose weather local or host : && echo http://%a:3000 && echo http://localhost:3000 && color 07 && timeout -t 10 && start http://localhost:3000 && npm start)