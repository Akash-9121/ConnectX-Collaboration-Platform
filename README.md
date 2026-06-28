<div align="center">

# 🚀 ConnectX

### Architecting Efficient Collaboration

A modern collaboration platform for managing projects, tracking tasks, communicating in real-time, conducting video meetings, sharing files, and monitoring team productivity—all from a single workspace.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge)

</div>

---

# 📖 About ConnectX

ConnectX is a full-stack collaboration platform that centralizes project management, task tracking, real-time communication, video meetings, file sharing, analytics, and role-based collaboration into a single workspace.

Built using **HTML, CSS, JavaScript, Python, Flask, MySQL, Socket.IO, and WebRTC**, ConnectX delivers a seamless collaboration experience through secure authentication, role-based dashboards, project and task management, real-time messaging, video meetings, file sharing, reporting tools, and an interactive smart assistant.

---

# 🌐 Live Demo

**🚀 Live Demo:** https://connectx-app.onrender.com/

**Repository:** https://github.com/Akash-9121/ConnectX-Collaboration-Platform

---

# ✨ Key Features

## 🔐 Authentication & Authorization

- Secure user registration and login
- Google OAuth authentication
- Password hashing
- Session management
- Role-Based Access Control (Super Admin, Team Lead, Team Member)

---

## 📋 Project & Workspace Management

- Create and manage workspaces
- Organize projects
- Manage project members
- Track project progress

---

## ✅ Task Management

- Create, assign and update tasks
- Track task status
- Permission-based task operations

---

## 💬 Real-Time Collaboration

- Global team chat powered by Flask-SocketIO
- Instant team communication

---

## 🎥 Video Meetings

- Create meeting rooms
- Join meetings using Meeting IDs
- WebRTC-based video conferencing

---

## 📁 File Management

- Upload and organize project documents
- Centralized file management

---

## 📊 Reports & Analytics

- Project statistics
- Productivity insights
- Task completion metrics
- Interactive dashboard visualizations

---

## 🤖 Smart Assistant

An interactive assistant that helps users navigate the platform, execute common actions, and provides role-aware guidance based on user permissions.

---

## 🔔 Notifications

- Task updates
- Project activity alerts

---

## 🎨 User Experience

- Responsive interface
- Dark & Light theme
- Clean and modern dashboard
---

# 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| **Frontend** | HTML5, CSS3, JavaScript, Bootstrap |
| **Backend** | Python, Flask |
| **Database** | MySQL |
| **Authentication** | Flask-Login, Google OAuth |
| **Real-Time Communication** | Flask-SocketIO, Socket.IO |
| **Video Conferencing** | WebRTC |
| **Charts & Analytics** | Chart.js |
| **Deployment** | Render |

---

# 🏗️ System Architecture

```text
                     +----------------------+
                     |     Web Browser      |
                     +----------+-----------+
                                |
                                |
                     HTTP / WebSocket
                                |
                                ▼
                  +---------------------------+
                  |       Flask Backend       |
                  +------------+--------------+
                               |
          +--------------------+--------------------+
          |                    |                    |
          ▼                    ▼                    ▼
   Authentication        Project Logic      Socket.IO Server
          |                    |                    |
          +--------------------+--------------------+
                               |
                               ▼
                      +----------------+
                      |     MySQL      |
                      |    Database    |
                      +----------------+
                               |
                               ▼
              Stores Users, Projects, Tasks,
             Workspaces, Files & Notifications

                               |
                               ▼

                    WebRTC Video Meetings
```

---

# ⚙️ Installation & Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Akash-9121/ConnectX-Collaboration-Platform.git
```

### 2. Navigate to the Project Directory

```bash
cd ConnectX-Collaboration-Platform
```

### 3. Create a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure the Database

Create a MySQL database and update your MySQL credentials in the project's configuration file before running the application.

### 6. Run the Application

```bash
python app.py
```

Open your browser and visit:

```text
http://localhost:5000
```

---

# 📂 Folder Structure

```text
ConnectX-Collaboration-Platform/
│
├── static/
│   ├── css/
│   │   ├── modals.css
│   │   └── style.css
│   │
│   ├── js/
│   │   ├── meeting.js
│   │   └── script.js
│   │
│   └── images/
│
├── templates/
│   ├── base.html
│   ├── dashboard_base.html
│   ├── home.html
│   ├── login.html
│   ├── register.html
│   ├── workspace.html
│   ├── project_tasks.html
│   ├── members.html
│   ├── meetings.html
│   ├── meeting_room.html
│   ├── global_chat.html
│   ├── file_manager.html
│   ├── upload_file.html
│   ├── view_files.html
│   ├── reports.html
│   ├── notifications.html
│   ├── tl_dashboard.html
│   ├── tm_dashboard.html
│   ├── edit_task.html
│   └── google_role.html
│
├── app.py
├── promote_admin.py
├── requirements.txt
├── .gitignore
└── README.md
```
