# Statements

## 1. Problem Statement
Most university departments, along with educational institutions, still maintain students' records using fragmented or outdated methods, such as spreadsheets or physical registers. The process involves inefficiencies, resultant delays in quickly retrieving detailed information concerning any particular student, potential inconsistencies in data recording, and a very time-consuming process for generating the necessary academic reports. A simple, reliable, and centralized tool is needed to make it possible for administrators to carry out key operations related to the data of students in a quick manner.

## 2. Project Scope

The scope of the project SRM is only to develop a CLI application in Java.

The system will focus on maintaining only the core information about the students:

Data Domain: Student demographic and enrollment data includes ID, Name, Course, and Contact.

Operations: Full CRUD - Create, Read, Update, Delete.

Persistence: Data will be persisted by either using local file handling, for example, CSV or JSON, or, in other cases, a simple embedded database connection like SQLite.

Exclusions: Advanced features out of the scope for this project are GUIs, network communications, complex authentication or role management, and integration with any external system.

## 3. Target Users

The main target user of the Student Record Manager is:

System Administrators: These are departmental heads, academic coordinators, or administrative staff responsible for the maintenance of official student enrollment and academic records.

## 4. High-Level Features

The following are the high-level functionalities of the Student Record Manager:

Student Creation: The ability to take in the student's essential details and create a new, distinctive record of that student in the system.

Record Retrieval & Search: Lists all current student records or identifies a particular student by unique identifiers, for instance, Student ID. Data Modification Course: The ability to update existing students' information, for example, course or contact details. Delete Record: A safe way of removing a student record from the system. Data Persistence: The program will autosave and autoload all student data from the local medium at program startup and shutdown.