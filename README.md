# Hospital-Managment-System



🏥 Hospital Management System — Modules

1. 👤 Patient Management

Add patient
Update patient
Delete patient
Search patient
View patient details
Generate Patient ID

2. 👨‍⚕️ Doctor Management

Add doctor
Remove doctor
Search doctor
View doctor details
Doctor specialization
Doctor availability

3. 📅 Appointment Management

Book appointment
Cancel appointment
View appointments
Assign doctor to patient
Check doctor availability

4. 🏨 Admission Management

Admit patient
Assign room/bed
View admitted patients
Discharge patient
Update bed availability

5. 💊 Medicine Management

Add medicine
Search medicine
Update medicine stock
Remove expired medicine
View available medicines

6. 🧪 Test/Laboratory Management

Add test
Assign test to patient
Store test result
View test report
Test charges

7. 💰 Billing Management

Consultation charges
Room charges
Medicine charges
Test charges
Generate final bill
Payment status

8. 👩‍⚕️ Staff Management

Add staff
Remove staff
View staff
Staff role
Staff details

9. 🔐 Login & Authentication

Admin login
Doctor login
Receptionist login
Different permissions based on role

10. 📊 Reports

Patient report
Doctor report





# Arch of the git 


              HOSPITAL MANAGEMENT SYSTEM
                         │
                         ▼
                Receptionist Login
                         │
                    Username
                    Password
                         │
                         ▼
                  Login Successful
                         │
                         ▼
                  MAIN MENU
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
       ▼                 ▼                 ▼
    Patient            Doctor          Appointment
       │                 │                 │
       ▼                 ▼                 ▼
   Admission          Medicine        Laboratory
       │                 │                 │
       └─────────────────┼─────────────────┘
                         │
                ┌────────┴────────┐
                ▼                 ▼
             Billing           Staff
                │                 │
                └────────┬────────┘
                         ▼
                      Reports
                         │
                         ▼
                       Logout






          4. Complete Git structure

Your repository can look like:

main
 │
 └── develop
       │
       ├── feature/patient-management
       ├── feature/appointment-management
       ├── feature/medical-management
       │
       ├── feature/doctor-management
       ├── feature/admission-management
       ├── feature/test-management
       │
       ├── feature/staff-management
       ├── feature/report-management
       │
       ├── feature/billing
       └── feature/authentication




       
