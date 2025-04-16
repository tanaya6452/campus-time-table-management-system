# campus-time-table-management-system
# Campus Timetable Generator

A web-based application for NMIMS students and faculty to manage and view classroom schedules efficiently. Built with a focus on accessibility, usability, and dynamic data handling.

## 🚀 Features

- 🧑‍💼 **Login/Signup System**  
  User authentication system with session protection for both students and admins.

- 📅 **Dynamic Timetable Display**  
  Shows class-wise schedules including room, branch, faculty, and subject.

- 🖱️ **Interactive UI with Tooltips**  
  Hover over classes to view room and subject details instantly.

- 🎨 **Modern Design with Themes**  
  Animated backgrounds and light/dark theme switching for a cool user experience.

- 🔍 **Live Subject Search**  
  Quickly find when and where a subject is being taught.

- 📌 **Today Highlighting**  
  Automatically highlights the current day's schedule.

- 🛠️ **Admin Panel**  
  Admins can update the schedule dynamically via a secure backend.

- 📄 **Export Timetable**  
  Download or print your schedule as a PDF with one click.

## 🧑‍💻 Tech Stack

- **Frontend**: HTML, CSS (internal + animations), JavaScript, AngularJS
- **Backend**: Node.js, Express.js
- **Database**: Microsoft SQL Server
- **Authentication**: Session-based auth with user/admin roles

## 📂 Project Structure

ClassTimetableProject/
│
├── index.html               --> Student Login Page
├── timetable.html           --> Timetable Display Page
├── admin.html               --> Admin Login Page
├── admin-panel.html         --> Admin Panel to Edit Timetables (UI only)
│
├── style.css                --> Global Stylesheet
├── script.js                --> Contains Timetable Logic, Registration & Login
│
├── nmims-footer.png         --> NMIMS Logo image used in login screen
│
└── (optional assets/)       --> Folder for future assets (images, backups, etc.)
________________________________________
