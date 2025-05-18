Use Case: Clinic Booking System
This system will help a clinic manage:

Patients

Doctors

Appointments

Treatments

Billing

Tables and Relationships Overview
Table Name	Description	Relationships
Patients	Stores patient info	1-to-Many with Appointments
Doctors	Stores doctor info	1-to-Many with Appointments
Appointments	Stores patient-doctor visits	Many-to-1 with Patients & Doctors
Treatments	List of treatments offered	Many-to-Many with Appointments
Bills	Billing info for each appointment	1-to-1 with Appointments
Appointment_Treatments	Junction table for M-M	Appointment 
