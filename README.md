# Hospital Server App

## Overview

This project is a Hospital server Application designed as part of a Database Design course. It manages hospital-related data efficiently, including patients, doctors, appointments, treatments, and more. The backend handles all data storage and retrieval through a well-structured database, while the front end is built using **Appsmith** for a user-friendly and interactive interface.

---

## Features

* **Patient Management:** Store and manage patient records, including personal details, medical history, and treatment plans.
* **Doctor Management:** Keep track of doctors, their specialties, schedules, and contact information.
* **Appointment Scheduling:** Book, view, update, and cancel patient appointments with doctors.
* **Medical Records:** Store diagnosis, prescriptions, and treatment details securely.
* **Staff Management:** Manage hospital staff details and roles.
* **Billing and Payments:** Record billing information and payment status for treatments and consultations.

---

## Technologies Used

* **Database:** SQL-based relational database (MySQL)
* **Backend:** Server-side logic to handle CRUD operations, implemented using \[your backend technology, Python/Flask
* **Frontend:** Appsmith — a low-code platform.

---

## Database Design

* **Entities:** Patients, Doctors, Appointments, Treatments, Staff, Bills, etc.
* **Relationships:** Properly normalized with foreign key constraints to ensure data integrity.
* **Sample Tables:**

  * `Patients (PatientID, Name, DOB, Contact, Address, MedicalHistory, ...)`
  * `Doctors (DoctorID, Name, Specialty, Contact, Schedule, ...)`
  * `Appointments (AppointmentID, PatientID, DoctorID, Date, Time, Status, ...)`
  * `Treatments (TreatmentID, AppointmentID, Diagnosis, Prescription, Notes, ...)`
  * `Staff (StaffID, Name, Role, Contact, ...)`
  * `Billing (BillID, PatientID, Amount, PaymentStatus, Date, ...)`


## Future Enhancements

* Add role-based access control for better security.
* Integrate real-time notifications for appointment reminders.
* Implement analytics dashboards for hospital management insights.
* Expand billing module to support insurance claims.

---

## Credits

Developed by: Ripandeep Kaur
Course: Database Design


---
