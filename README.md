# Smart Healthcare Management System (SHMS)

## Object Oriented Programming Mini Project

### Submitted By

- **Aakarsh Jha** - Roll No. 39 (230905248)  
- **Hiten Raj Singh** - Roll No. 23 (230905152)  
- **Dhruv Grover** - Roll No. 55 (230905434)  
- **Pratishthraj Singh Chauhan** - Roll No. 7 (230905036)  
- **Akshat Rana** - Roll No. 60 (230905496)  

**Section C**

**Submitted to:**  
Dr. Andrew J  
Associate Professor  
Department of Computer Science and Engineering  
Manipal Institute of Technology, Manipal, Karnataka – 576104  
**Date:** October 2024  

---

## Introduction

The Smart Healthcare Management System (SHMS) is designed to address challenges in the healthcare sector by integrating various functionalities to streamline workflows and improve patient care. Built using JavaFX and core Java, SHMS offers:

- Centralized patient records
- Appointment scheduling
- Doctor/staff management
- Persistent data storage

---

## Problem Statement

Design and implement a robust SHMS to:
- Digitize patient records
- Schedule appointments efficiently
- Manage doctor and staff profiles
- Enhance data accessibility and integrity

---

## System Modules

### 1. Patient Registration and Medical Records

- **Technologies**: JavaFX for GUI, Java for logic
- **Features**:
  - Patient registration form with fields for medical history, allergies, emergency contacts
  - Object model using a `Patient` class
  - Data displayed and managed via JavaFX TextFields and TextArea
  - Persistent storage using file system

### 2. Appointment Scheduling and Doctor Allocation

- **Appointment Class**:
  - Encapsulates `Patient` and `Doctor` objects
  - `toString()` method for readable output

- **AppointmentScheduling Class**:
  - GUI for booking appointments using TextFields and ComboBox
  - Filters doctors by specialization using Java Streams
  - Validates and books appointments
  - Real-time feedback via TextArea

### 3. Doctor and Staff Management

- **DoctorManagement Class**:
  - Add, view, and clear doctor data
  - Uses JavaFX TextFields and Buttons
  - Stores data persistently via file utilities
  - Structured GUI using VBox layout

### 4. Data Persistence

- Uses Java I/O (BufferedReader/Writer)
- Data files:
  - `patients.txt`
  - `doctors.txt`
  - `appointments.txt`
- Ensures data survives application restarts
- Supports error handling and data consistency

### 5. Compiling and Running

- Use `javac` for compiling `.java` files
- Use `java` command to run the JavaFX application
- The GUI covers:
  - Patient registration
  - Appointment scheduling
  - Doctor management

---

## Sample Screenshots

> _Note: Screenshots include interfaces for patient registration, appointment booking, and doctor management._

---

## Conclusion

SHMS provides a modular, maintainable, and scalable solution for hospital management using Java and JavaFX. Key benefits:

- MVC architecture for separation of concerns
- Persistent storage with I/O streams
- Responsive and interactive GUI
- Easily extendable for future enhancements like database support or web deployment

---

## References

- [JavaFX Documentation](https://openjfx.io/)
- [Oracle Java Downloads](https://www.oracle.com/in/java/technologies/downloads/)
- [Ubuntu Setup](https://ubuntu.com/download/desktop)
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [JavaFX Tutorials](https://www.youtube.com/playlist?list=PLZPZq0r_RZOM-8vJA3NQFZB7JroDcMwev)
