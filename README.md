# Student Grade Management System

This project implements a system for managing student grades using SQLAlchemy and PostgreSQL. The system allows storing and processing data about students, teachers, subjects, and grades.

## Features:
- Top 5 students with the highest average grades.
- Best student in a specific subject.
- Average grade by group for a specific subject.
- Overall average grade for all students.
- And much more...

## Setup Instructions

## Requirements

- Python 3.13+
- Docker

### 1. Clone the repository:
```bash
git clone https://github.com/Dmytro-Chernomord/goit-pythonweb-hw-06
cd goit-pythonweb-hw-06
```

```bash
pip install -r requirements.txt
```

### 2. Start PostgreSQL with Docker

```bash
docker run --name some-postgres -p 5432:5432 -e POSTGRES_PASSWORD=mysecretpassword -d postgres
```

### 3. Start App

```bash
python main.py 
```