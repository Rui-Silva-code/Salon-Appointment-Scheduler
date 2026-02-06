# 💈 Salon Appointment Scheduler (CLI)

Terminal-based appointment scheduling system built with **Bash** and **PostgreSQL**.  
This project demonstrates backend fundamentals such as relational database design, SQL queries, and command-line user interaction.

> Educational / portfolio project (CLI-based)

---

## 🚀 Overview

This application allows users to schedule salon appointments directly from the terminal.

Users can:
- Choose a service
- Enter their phone number
- Register as a new customer if needed
- Schedule an appointment time
- Persist all data in a PostgreSQL database

---

## 🛠️ Technologies Used

- **Bash**
- **PostgreSQL**
- **SQL (DDL & DML)**
- `psql` CLI tool

---

## 🧠 Key Concepts Demonstrated

- Relational database design
- Primary & foreign keys
- SQL constraints
- Sequences and auto-increment IDs
- Input validation
- Bash scripting logic
- Database-driven workflows
- CLI-based application flow

---

## 🗄️ Database Structure

The database includes the following tables:

- **services**
- **customers**
- **appointments**

Relationships:
- One customer → many appointments
- One service → many appointments

Foreign keys ensure data consistency.

---

## ⚙️ Installation & Setup

### Prerequisites

- PostgreSQL
- Bash (Linux / WSL / macOS)
- `psql` available in terminal

---

### Step 1: Clone Repository

```bash
git clone https://github.com/Rui-Silva-code/Salon-Appointment-Scheduler.git
cd Salon-Appointment-Scheduler
````
### Step 2: Create Database

```bash
psql -U postgres

CREATE DATABASE salon;
````

### Step 3: Import Database Schema
```bash
psql -U postgres -d salon -f salon.sql
````

### Step 4: Run the Application
```bash
bash salon.sh
````

🎓 Learning Context

This project was completed as part of the freeCodeCamp Relational Database Certification, with additional improvements for portfolio presentation.
