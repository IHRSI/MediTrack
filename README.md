# 🏥 Smart Healthcare Management System (SHMS)

> A JavaFX-based healthcare management system designed to streamline patient care, appointment scheduling, and doctor management through an interactive GUI and persistent data storage.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)
![OOP](https://img.shields.io/badge/OOP-Concepts-blue?style=for-the-badge)
![File%20Handling](https://img.shields.io/badge/File%20Handling-Java-green?style=for-the-badge)

[![Documentation](https://img.shields.io/badge/View-Project_Documentation-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/IHRSI/MediTrack/blob/main/SHMS.pdf)

---

## 📌 Overview

The **Smart Healthcare Management System (SHMS)** is an **Object-Oriented Programming mini project** developed using **JavaFX** and **Core Java** to improve healthcare management by digitizing records, optimizing appointment scheduling, and managing doctor/staff information efficiently.

The system provides a **centralized platform** for managing patient data, doctor allocation, and appointment scheduling while ensuring **persistent data storage** across sessions.

### ✨ Key Highlights

✔️ Centralized Patient Records
✔️ Appointment Scheduling & Doctor Allocation
✔️ Doctor & Staff Management
✔️ Persistent File-Based Storage
✔️ Interactive JavaFX GUI
✔️ Modular OOP-Based Design

---

## 🎯 Problem Statement

Traditional healthcare systems often struggle with inefficient record keeping, scheduling conflicts, and poor data accessibility.

The objective of **SHMS** is to build a reliable and scalable healthcare system that:

* Digitizes patient medical records
* Enables seamless appointment scheduling
* Manages doctor and staff information efficiently
* Improves healthcare workflow and accessibility
* Maintains secure and persistent data storage

---

## 🏗️ System Architecture

The project follows an **Object-Oriented Design** approach using modular classes and JavaFX components for better maintainability and scalability.

### Modules Included:

1. **Patient Registration & Medical Records**
2. **Appointment Scheduling & Doctor Allocation**
3. **Doctor & Staff Management**
4. **Data Persistence using Java I/O**
5. **Interactive GUI using JavaFX**

---

## 🚀 Features

### 👨‍⚕️ Patient Registration & Medical Records

* Register new patients
* Store medical history, allergies, treatments, and emergency contacts
* View patient database
* Clear patient records
* Persistent storage using text files

### 📅 Appointment Scheduling & Doctor Allocation

* Book appointments with available doctors
* Filter doctors by specialization
* Doctor availability validation
* Real-time appointment feedback
* Structured appointment management

### 🩺 Doctor & Staff Management

* Add doctor details
* View all doctors
* Clear doctor records
* Specialization-based management
* Persistent data handling

### 💾 Data Persistence

Data is stored using **Java File Handling** to ensure information remains available even after restarting the application.

Files used:

```txt
patients.txt
doctors.txt
appointments.txt
```

---

## 🛠️ Tech Stack

### Languages & Technologies

* **Java**
* **JavaFX**
* **Core Java**
* **Java Collections Framework**
* **Java Streams API**
* **BufferedReader / BufferedWriter**

### Core Concepts Used

* Object-Oriented Programming (OOP)
* Encapsulation
* Inheritance
* Polymorphism
* MVC Architecture
* Event-Driven Programming
* File Handling

---

## 📂 Project Structure

```bash
SHMS/
│── src/
│   ├── model/
│   ├── ui/
│   ├── utils/
│   ├── Patient.java
│   ├── Doctor.java
│   ├── Appointment.java
│
│── data/
│   ├── patients.txt
│   ├── doctors.txt
│   ├── appointments.txt
│
│── README.md
```

---

## ▶️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/SHMS.git
cd SHMS
```

### Compile Project

```bash
javac *.java
```

### Run Application

```bash
java Main
```

---

## 📈 Future Enhancements

* Database Integration (MySQL/PostgreSQL)
* Authentication System
* Prescription Management
* Analytics Dashboard
* Cloud-Based Deployment
* Web-Based Version

---

## 🧠 Learning Outcomes

This project strengthened practical understanding of:

* JavaFX GUI Development
* Object-Oriented Programming
* File Handling & Persistence
* MVC Architecture
* Event-Driven Programming
* Modular Software Design

---

## 🏁 Conclusion

The **Smart Healthcare Management System (SHMS)** demonstrates a modular and scalable approach to healthcare management using **JavaFX and Core Java**.

By integrating **patient registration**, **doctor management**, **appointment scheduling**, and **persistent storage**, the system simplifies hospital workflows and improves healthcare accessibility.

Its extensible architecture makes it suitable for future upgrades such as **database integration, authentication systems, and web deployment**.

---

## 📚 References

* JavaFX Documentation: https://openjfx.io/
* Oracle Java Documentation: https://www.oracle.com/java/
* JavaFX Tutorials: https://www.youtube.com/playlist?list=PLZPZq0r_RZOM-8vJA3NQFZB7JroDcMwev
