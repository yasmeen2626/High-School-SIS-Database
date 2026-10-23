# High-School-SIS-Database 🎓

A comprehensive MySQL relational database system designed for **Al-Tamayoz Secondary School**. This project is part of the **SQL101** course certification from the Satr platform, demonstrating proficiency in database design, data definition (DDL), data manipulation (DML), and optimization.

## 🌟 Key Features
- **Database Schema Design:** Built dedicated tables for `STUDENT`, `TEACHER`, and `SUBJECT` with properly defined constraints (Primary Keys, Auto-Increments, and Uniqueness).
- **Comprehensive Dataset:** Seeded the database with structured data for 45+ students, 10+ teachers, and 6+ subjects.
- **Advanced Queries:** Implementation of data sorting (ascending order), column aliasing for enhanced readability, and conditional updates.
- **Schema Management:** Demonstrated database refactoring capabilities using `ALTER` and `RENAME` commands.

## 🛠️ Tech Stack & Database Specifications
- **Database Engine:** MySQL
- **Data Types Used:** `VARCHAR`, `DATE`, `CHAR(1)` (for gender), `DECIMAL(5,2)` (for precise GPA tracking up to 100.00).

## 📊 Database Components & Requirements Covered

### 1. Data Schema Creation
- Fully structured table generation with strict data constraints.
- Displayed and verified table availability within the schema environment.

### 2. Mock Data Seeding
- **Students:** 45 unique student profiles across multiple academic tracks (Scientific / Humanities) and grade levels (1-6).
- **Teachers:** 10 registered faculty records with localized office numbers (`Off-100` series).
- **Subjects:** Core high school curriculum subjects setup.

### 3. Queries & Operations Executed
- Sorted student records alphabetically using `ORDER BY`.
- Applied columns formatting using `AS` aliases for readable data delivery.
- Performed precision updates on transactional records using strict `WHERE` key filtering.
- Renamed foundational entities (`COURSE` updated to `SUBJECT`) utilizing `ALTER` query structures.
*This repository serves as a practical assessment and proof of core relational database management capabilities.*

