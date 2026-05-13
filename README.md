# cinema-management-system
PROJECT 08: MOVIE AND CINEMA ROOM MANAGEMENT SYSTEM 🎬
Developed by DATCOM Lab

NEU-College of Technology, National Economics University

Email: hung.tran@neu.edu.vn

📌 Project Objective
The objective of this project is to develop a robust database management system to efficiently manage movies, cinema rooms, screening schedules, customers, and ticket reservations. The system is designed to improve the booking experience, streamline cinema operations, and support automated report generation.

🛠 Tech Stack
Database Management System: MySQL

Programming Language: Python

Database Connector: mysql-connector-python

📂 Project Structure
Based on the repository organization:

cinema_website/: Contains cinema_website.html for the web-based landing page.

diagrams/: System design documents including:

er_diagram.png: Entity-Relationship model.

data_flow_diagram.png: System logic flow.

python/: The application layer containing:

main.py: Entry point for the Command-Line Interface (CLI).

config.py: Database connection settings.

tickets.py: Logic for seat booking and cancellations.

reports.py: Sales and occupancy rate generation.

sql/: Database implementation scripts:

01_schema.sql: Table structures (Movies, Rooms, Customers, etc.).

02_sample_data.sql: 510+ sample rows for testing.

03_indexes_views.sql: Query optimization and summaries.

04_stored_procedures.sql: Automated booking logic.

05_functions_triggers.sql: Occupancy calculations and overbooking prevention.

🚀 Main Functionalities
Management: Full CRUD operations for movies, cinema rooms, and screening schedules.

Booking System: Interactive seat selection with real-time availability checks.

Advanced DB Objects:

Triggers: Automatically prevent overbooking.

Functions: Calculate revenue per screening and occupancy rates.

Stored Procedures: Automate the ticket reservation process.

Security: Role-based access control (Admin and Ticket Clerk roles).

⚙️ Setup and Installation
1. Database Setup
Execute the SQL scripts in the sql/ folder in numerical order (01 to 06) using MySQL Workbench or any SQL client.

2. Python Environment
Install the required dependency:

Bash
pip install mysql-connector-python
3. Configuration
Update your database credentials in python/config.py:

Python
db_config = {
    'host': 'localhost',
    'user': 'your_user',
    'password': 'your_password',
    'database': 'cinema_management'
}
4. Running the App
Bash
cd python
python main.py
📊 Deliverables
Comprehensive Report: Database design, implementation details, and screenshots.

SQL Scripts: Full schema, sample data, and advanced objects.

Python Code: Functional booking and reporting application.

ER Diagram: Relational schema with PKs, FKs, and constraints.
