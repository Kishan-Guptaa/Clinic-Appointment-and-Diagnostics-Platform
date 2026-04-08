# Clinic-Appointment-and-Diagnostics-Platform
This repository contains the ER diagram for a clinic management system designed as part of the Web Dev Cohort 2026 – Database Assignment.

The goal of this design is to show how a clinic can digitally manage its daily operations like handling patients, doctors, appointments, consultations, diagnostic tests, reports, and payments in a clear and structured way.

### About the System

In a real clinic, patients first book appointments with doctors.

Some appointments turn into consultations. During consultations, doctors may prescribe diagnostic tests. After tests are completed, reports are generated and shared with patients. Payments are also recorded during this process.

This ER diagram represents that complete workflow step by step.

### Entities Used in the Diagram

The system includes the following main entities:

Patients – stores patient personal details

Doctors – stores doctor information and experience

Specialties – represents doctor specialization areas

Appointments – manages booking details between patient and doctor 

Consultations – represents actual doctor visits

Tests – stores available diagnostic tests

Consultation Tests – connects consultations with prescribed tests

Reports – stores generated diagnostic reports

Payments – records payment details for services


### Workflow Covered in the ER Diagram

The diagram supports the following clinic flow:

A patient books an appointment with a doctor

The appointment may result in a consultation

The doctor can prescribe one or more tests

Reports are generated after tests are completed

Payments are recorded for appointments or consultations


This structure allows one patient to visit multiple times and one doctor to treat many patients


### Relationships in the System

Some important relationships shown in the diagram:

One patient can book many appointments

One doctor can attend many patients

One appointment may lead to one consultation

One consultation can include multiple tests

Each prescribed test can generate a report

Payments are linked with appointments or consultations


### Design Highlights
Clear difference between appointment and consultation

Supports multiple visits per patient

Supports multiple tests per consultation

Reports are linked properly with diagnostic tests

Uses primary keys and foreign keys for proper connections

Simple, clean, and scalable database structure
