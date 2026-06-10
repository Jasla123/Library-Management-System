#   Library Management System

## Project Description

The **Library Management System** is a MySQL database project developed to manage and organize library operations efficiently. The system maintains records of books, customers, employees, library branches, issued books, and returned books.

This project demonstrates the implementation of a relational database using MySQL and applies various SQL concepts such as primary keys, foreign keys, joins, aggregate functions, grouping, sorting, and subqueries.

---

##  Objectives

* Manage book information and availability.
* Maintain customer records.
* Track book issue and return transactions.
* Store employee and branch details.
* Generate reports using SQL queries.

---

##  Database Name

**library**

---

##  Tables Created

### Branch

Stores branch information including branch number, manager details, address, and contact number.

### Employee

Stores employee details such as employee ID, employee name, position, salary, and branch assignment.

### Books

Maintains information about books including ISBN, title, category, rental price, availability status, author, and publisher.

### Customer

Stores customer registration details and customer information.

### IssueStatus

Tracks books issued to customers along with issue dates.

### ReturnStatus

Maintains records of returned books and return dates.

---

##  Technologies Used

* MySQL Workbench

---

##  SQL Concepts Implemented

* Database Creation
* Table Creation
* Primary Keys
* Foreign Keys
* Data Insertion
* Data Retrieval
* Joins
* Aggregate Functions
* GROUP BY
* HAVING Clause
* Subqueries
* Sorting and Filtering

---

## Queries Implemented

1. Retrieve available books from the library.
2. Display employee names and salaries in descending order.
3. Retrieve book titles and customers who issued them.
4. Display the total count of books in each category.
5. Retrieve employees earning more than ₹50,000.
6. Find customers registered before 2022 who have not issued any books.
7. Display branch-wise employee count.
8. Retrieve customers who issued books during June 2023.
9. Search books containing the word "History".
10. Display branches having more than five employees.
11. Retrieve managers and their branch addresses.
12. Display customers who issued books with rental prices greater than ₹25.

---


##  Learning Outcomes

This project helped in understanding:

* Relational database design
* Table relationships using foreign keys
* SQL query writing and optimization
* Data retrieval using joins and subqueries
* Database management using MySQL

---

##  Conclusion

The Library Management System successfully demonstrates the design and implementation of a relational database using MySQL. It provides an effective solution for managing library records and showcases essential database concepts used in real-world applications.
