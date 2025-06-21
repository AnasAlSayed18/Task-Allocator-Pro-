# 📌 Task Allocator Pro (TAP)

**Task Allocator Pro (TAP)** is a lightweight and user-friendly task management web application developed using **PHP, HTML, CSS, and MySQL**. It is designed to streamline workflow coordination in small teams by allowing role-specific control over projects, tasks, and progress tracking.

---

## 🚀 Features

### 🔐 User Management
- Multi-step user registration with session handling
- Secure login and logout functionality
- **Role-based access control**:
  - 👤 Manager
  - 🧑‍🏫 Project Leader
  - 👨‍💻 Team Member

---

### 👤 Manager Capabilities
- Add and manage new projects with full metadata
- Upload and manage project-related documents
- Assign **project leaders** to specific projects

---

### 🧑‍🏫 Project Leader Capabilities
- Create and define tasks within assigned projects
- Assign team members to tasks with:
  - Specific roles
  - Contribution percentages
- Validate that total contributions equal 100%
- Track and update overall project progress

---

### 👨‍💻 Team Member Capabilities
- Accept or reject assigned tasks
- View assigned task details, deadlines, and roles
- Update task status using a **progress slider**

---

### 🔍 Search & Tracking
- **Search** tasks by:
  - Task ID
  - Task name
  - Priority level
  - Status
  - Project name
- **Real-time progress tracking**
- Smart filters depending on user role

---

## 📷 Screenshots

> *(Insert screenshots in your GitHub repository or README here)*  
> Example:  
> ![Dashboard](screenshots/dashboard.png)  
> ![Task Progress Slider](screenshots/progress_slider.png)

---

## 💾 Technologies Used
- **Frontend**: HTML, CSS (Vanilla)
- **Backend**: PHP
- **Database**: MySQL
- **Session Handling**: PHP Native Sessions

---

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/TAP.git
