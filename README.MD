
** CarePulse (Patient & Clinic Scheduling System)**
**Business Background**
CarePulse operates a network of urgent care clinics across the region. They require an integrated system to handle patient registrations, practitioner schedules, appointment bookings, and diagnosis/billing records while keeping track of medical specializations and internal doctor referrals.

**Requirements & Data Needed**

- Clinics: Clinic ID, facility name, address, emergency contact line, and operating hours.

- Medical Practitioners: Doctor ID, NPI (National Provider Identifier), full name, medical license state, primary specialty (e.g., Pediatrics, Cardiology), and primary Clinic assignment.

- Doctor Referrals: A practitioner can refer patients to another practitioner (a self-referencing relationship within the doctor entity).

- Patients: Patient ID, national identity number, full name, date of birth, biological sex, contact phone, and primary emergency contact info.

- Appointments: Appointment ID, appointment date/time, status (Scheduled, Completed, No-Show), assigned Doctor, attending Patient, and the specific Clinic location where the visit occurs.

- Prescriptions & Diagnoses: Following an appointment, zero or more medical diagnoses (ICD codes) and drug prescriptions (Medication Name, Dosage, Frequency, Duration) are linked directly to that specific appointment event.

**Task:**

- Identify entities, recursive/self-referencing relationships, ternary/multi-entity relationships (e.g., Appointment linking Doctor, Patient, and Clinic), and attributes.
- Draw the ER Diagram representing constraints clearly.
- Translate the ERD into a Relational Schema (3NF). Resolve any complex relationships into foreign key associations.
- Produce the Physical Model (SQL scripts) with appropriate foreign key referential integrity constraints (e.g., ON DELETE CASCADE / SET NULL).
