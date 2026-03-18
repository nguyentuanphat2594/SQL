# **📊 Student Management System (SQL Project)**
## ***📌 Project Overview***

This project builds a relational database system to simulate a university student management environment.
The system is designed to manage:

- Student information

- Course registration

- Academic structure (Faculty, Department, Major)

- Teaching assignments

- Student performance and GPA

- The goal of this project is to apply SQL for real-world data analysis scenarios, transforming raw relational data into meaningful insights for academic management.

## ***🎯 Objectives***

- Design a normalized relational database

- Simulate a real-world university system

- Solve business questions using SQL queries

- Perform data aggregation, joins, and analytical queries

## ***🏗️ Database Schema***
- Conceptual Model (ERD)

- Physical Model (Relational Schema)

## ***🗂️ Dataset Description***

This project uses a synthetic dataset simulating a university system.

### Main Entities:

SinhVien (Students)
Stores personal and academic information of students

GiangVien (Lecturers)
Stores lecturer information and academic titles

MonHoc (Courses)
Contains course details such as name and credit units

LopHocPhan (Course Sections)
Represents specific classes opened in each semester

DangKy (Registrations)
Records student course registrations

KetQua (Results)
Stores student grades (midterm, final, GPA)

NganhHoc / ChuyenNganh (Major / Specialization)
Academic programs

Khoa / BoMon (Faculty / Department)
Organizational structure

HocKy (Semester)
Academic timeline

ThanNhan (Relatives)
Student family information

### 🔗 Relationships Overview

A student belongs to a major, specialization, and class

A lecturer belongs to a department → faculty

Courses are opened as class sections each semester

Students register for class sections → stored in DangKy

Results are recorded in KetQua

Lecturers are assigned to classes via PhuTrach

## ***📊 Business Questions & SQL Analysis***

This project answers real-world academic management questions:

**1. Student Distribution**

Number of students by major

**2. Class Statistics**

Number of students in each class

**3. Enrollment Analysis**

Students who did NOT register for courses in a semester

**4. Teaching Load**

Number of courses taught by each lecturer

**5. Student Workload**

Number of courses each student registered per semester

**6. Teaching Activity**

Number of classes taught by lecturers per semester

**7. Repeated Courses**

Students who retake a course multiple times

**8. Academic Performance**

Total credits accumulated

GPA calculation

**9. Missing Grades Detection**

Courses without recorded grades

**10. Course Performance**

Average grade per course per semester

**11. Top Students**

Students with highest GPA in each class

### 🛠️ Technologies Used

SQL Server Management Studio (SSMS)

## ***🚀 How to Run***
1. Open SQL Server Management Studio
2. Run file: QLSV-Nhóm_1.sql (create database + tables)
3. Run file: TruyvanQLSV-Nhóm_1.sql (analysis queries)

## ***💡 Key Skills Demonstrated***

- Database Design (ERD, normalization)

- Complex SQL Queries

- JOIN, GROUP BY, HAVING

- Subqueries & Aggregations

- Real-world Data Analysis Thinking

## ***👤 My Contributions***

As part of a team project, I was responsible for multiple stages of the system development, including both conceptual design and implementation:

### Dataset Preparation

- Participated in designing and generating the synthetic dataset

- Ensured data consistency and logical relationships between entities

### Database Design

- Contributed to both:

- Conceptual Design (ERD)

- Physical Design (Relational Schema in SQL Server)

- Reviewed and validated table structures, primary keys, and relationships

### SQL Development

Implemented and optimized analytical queries, including:

- Query (e): Course registration count per student

- Query (f): Teaching load per lecturer per semester

- Query (g): Students retaking courses

- Query (h): GPA and accumulated credits calculation

### System Validation & Testing

- Reviewed the entire database and queries for correctness

- Ensured queries return accurate and meaningful results

### Presentation

- Delivered the final project presentation

- Explained database design, query logic, and analytical results
