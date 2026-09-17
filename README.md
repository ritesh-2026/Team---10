# 🏥 Clinic Appointment Booking System

A simple **Clinic Appointment Booking System** developed as a **1st Semester BCA Database Management Systems (DBMS) project**.

The project demonstrates the use of database concepts to manage **patients, doctors, appointments, and consultation types** in a clinic environment.

---

## 📌 Project Information

| Detail | Description |
|---|---|
| **Project Title** | Clinic Appointment Booking System |
| **Subject** | Database Management Systems (DBMS) |
| **Course** | BCA – 1st Semester |
| **Problem Statement** | Clinic – Appointment Booking |
| **Feature Set** | Feature Set III |
| **Database Concept** | Relational Database Management System |

---

## 🎯 Objective

The main objective of this project is to design a database system that can efficiently store and manage clinic appointment information.

The system focuses on maintaining:

- Patient details
- Doctor details
- Appointment details
- Consultation type
- Appointment status
- Appointment date and time

It also demonstrates how different entities are related in a relational database.

---

## 🧩 Feature Set III

This project contains the following major features:

### 1. 👤 Patient Details

Stores information about patients.

**Attributes include:**
- Patient ID
- Patient Name
- Contact Number

### 2. 👨‍⚕️ Doctor Details

Stores information about doctors.

**Attributes include:**
- Doctor ID
- Doctor Name
- Specialization

### 3. 📅 Appointment

Stores information related to appointments.

**Attributes include:**
- Appointment ID
- Patient ID
- Doctor ID
- Appointment Date
- Appointment Time
- Consultation Type
- Appointment Status

### 4. 💻 Consultation Type

Defines how the consultation takes place.

Examples:

- In-person
- Online

### 5. 📌 Appointment Status

Maintains the current status of an appointment.

Examples:

- Scheduled
- Completed
- Cancelled

---

## 🗃️ Database Entities

The main entities used in the project are:

```text
PATIENT
   |
   | 1
   |
   | M
APPOINTMENT
   |
   | M
   |
   | 1
DOCTOR
