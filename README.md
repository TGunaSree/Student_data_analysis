# Student Data Analysis Project

##  Project Overview
A SQL-based relational database designed to manage and analyze student enrollments and course performance.

##  Tech Stack
- **Database:**  MySQL
- **Tooling:**  MySQL Workbench

##  Database Schema
The project uses a relational model with two main entities:
- **Students:** Tracks student names, grades, and enrollment dates.
- **Courses:** Contains course details, credits, and instructor names.

[click here to view the ER diagram](https://www.gleek.io/templates/student-management-er)

##  Key Queries
I performed the following analysis:
1. **Enrollment Distribution:** Used `GROUP BY` to find student counts per course.
2. **Performance Tracking:** Filtered students by high grades to identify top performers.
3. **Relational Joins:** Connected students to their specific instructors and course credits.
