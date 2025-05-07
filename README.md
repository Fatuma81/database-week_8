# database-week_8
# Clinic Booking System

## 📘 Project Description
The **Clinic Booking System** is a relational MySQL database designed to manage clinic operations such as booking appointments, registering patients, assigning doctors, and recording treatments.

This database supports the following features:
- Registration and management of doctors and their specialties.
- Registration and tracking of patient information.
- Scheduling and updating appointments between doctors and patients.
- Recording treatments administered during appointments.
- Capturing complex many-to-many relationships between appointments and treatments.

## 📚 Key Entities and Relationships

- **Doctors**  
  - Each doctor has a unique profile including name, contact info, and specialty.
  - One-to-Many relationship with Appointments.

- **Patients**  
  - Each patient record includes name, birth date, and contact information.
  - One-to-Many relationship with Appointments.

- **Appointments**  
  - Stores date/time, doctor, patient, and appointment status.
  - Many-to-One relationship with both Patients and Doctors.
  - Many-to-Many relationship with Treatments.

- **Treatments**  
  - Contains information about medical treatments provided by the clinic.
  - Linked to Appointments via a junction table.

## 🔗 Entity-Relationship Diagram (ERD)
included as a screenshot

