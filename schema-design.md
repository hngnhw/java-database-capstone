# Database Schema Design

## Tables
- **Doctor**: id, name, specialization, email
- **Patient**: id, name, dob, email
- **Appointment**: id, doctor_id, patient_id, date, status
- **Admin**: id, name, email, role
