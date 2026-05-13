# 🎬 Cinema Room & Movie Management System

<div align="center">

![MySQL](https://img.shields.io/badge/Database-MySQL-blue?style=for-the-badge&logo=mysql)
![Python](https://img.shields.io/badge/Backend-Python-yellow?style=for-the-badge&logo=python)
![HTML](https://img.shields.io/badge/Frontend-HTML5-orange?style=for-the-badge&logo=html5)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

# 📌 Project Overview

The **Cinema Room & Movie Management System** is a comprehensive Database Management System (DBMS) designed to simulate a real-world cinema booking and management platform.

This project provides functionalities for:

- 🎥 Movie management
- 🏢 Cinema room management
- 🗓 Screening schedule management
- 👥 Customer management
- 🎟 Ticket booking and cancellation
- 📊 Revenue and occupancy reporting

The system demonstrates advanced database design concepts, SQL optimization techniques, and Python–MySQL integration.

---

# 🛠 Technology Stack

| Component | Technology |
|------------|------------|
| Database | MySQL |
| Backend | Python |
| Connector | mysql-connector-python |
| Frontend | HTML |
| IDE | VS Code / PyCharm |
| Database Tool | MySQL Workbench |

---

# 📂 Project Structure

```plaintext
CINEMA_PROJECT/
│
├── cinema_website/
│   └── cinema_website.html
│
├── diagrams/
│   ├── er_diagram.png
│   ├── data_flow_diagram.png
│   └── er_diagram.mwb
│
├── python/
│   ├── main.py
│   ├── config.py
│   ├── db_connection.py
│   ├── movies.py
│   ├── rooms.py
│   ├── screenings.py
│   ├── tickets.py
│   ├── customers.py
│   ├── reports.py
│   └── generate_data.py
│
├── sql/
│   ├── 01_schema.sql
│   ├── 02_sample_data.sql
│   ├── 03_indexes_views.sql
│   ├── 04_stored_procedures.sql
│   ├── 05_functions_triggers.sql
│   ├── 06_security.sql
│   └── show_movies.csv
│
└── README.md
```

---

# 🚀 Main Features

## 🎥 1. Movie & Cinema Management

- Add, update, and delete movies
- Manage cinema rooms
- Create screening schedules
- Update movie information and showtimes

---

## 🎟 2. Ticket Booking System

- Real-time seat booking
- Automatic seat availability checking
- Ticket cancellation support
- Booking validation system

---

## 🧠 3. Advanced Database Features

### 🔹 Triggers

- Prevent overbooking
- Ensure seat availability integrity
- Maintain booking consistency

### 🔹 Functions

- Calculate revenue per screening
- Compute occupancy rates
- Generate analytical statistics

### 🔹 Stored Procedures

- Automate ticket booking workflows
- Simplify transaction processing
- Improve database consistency

### 🔹 Views & Indexes

- Optimize query performance
- Create summarized reports
- Improve search efficiency

---

# 🔐 Security System

The project implements **Role-Based Access Control (RBAC)**.

| Role | Permissions |
|------|-------------|
| Admin | Full database access |
| Ticket Clerk | Booking and customer operations |

Security scripts are included to manage database permissions and access control.

---

# 📊 Reporting System

The system provides multiple analytical reports, including:

- Revenue reports by movie
- Occupancy rate reports
- Customer booking statistics
- Screening performance analysis

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone <your-repository-url>
cd CINEMA_PROJECT
```

---

## 2️⃣ Setup MySQL Database

Run the SQL files in the following order:

```plaintext
01_schema.sql
02_sample_data.sql
03_indexes_views.sql
04_stored_procedures.sql
05_functions_triggers.sql
06_security.sql
```

You can execute them using:

- MySQL Workbench
- MySQL CLI

---

## 3️⃣ Install Required Package

```bash
pip install mysql-connector-python
```

---

## 4️⃣ Configure Database Connection

Edit:

```plaintext
python/config.py
```

Example:

```python
db_config = {
    "host": "localhost",
    "user": "root",
    "password": "your_password",
    "database": "cinema_management"
}
```

---

## 5️⃣ Run Application

```bash
cd python
python main.py
```

---

# 📦 Deliverables

- ✅ Complete Database Design (ERD + DFD)
- ✅ Full SQL Scripts
- ✅ Python CLI Application
- ✅ Sample Dataset (510+ records)
- ✅ HTML Landing Page
- ✅ Documentation

---

# 💡 Key Highlights

- Real-world cinema management simulation
- Fully normalized relational database design
- Advanced SQL implementation:
  - Triggers
  - Stored Procedures
  - Functions
  - Views
  - Indexes
- Python + MySQL integration
- Modular and scalable architecture

---

# 📈 Future Improvements

Potential future enhancements:

- Web-based booking interface
- Online payment integration
- QR-code ticket generation
- Dashboard and analytics
- RESTful API support
- Multi-branch cinema management

---

# 🖼 Database Diagrams

## ER Diagram

```markdown
Add image here:
![ER Diagram](C:\Users\Laptop\Desktop\cinema_project\diagrams\er_diagram.png)
```

## Data Flow Diagram

```markdown
Add image here:
![DFD](diagrams/data_flow_diagram.png)
```

---

# 👨‍💻 Authors

**DATCOM Lab**  
NEU – College of Technology  
National Economics University

📧 hung.tran@neu.edu.vn

---


