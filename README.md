# Asclepius
## Description

Asclepius is a healthcare appointment system that allows faster scheduling of appointments between doctors and patients

## Features to Implement

**Login**
- Users can be both a patient and a doctor with/ the same account
- Being a doctor requires verification (Employee # DB)
- Admin Login (Admin is a special type of user, there can be multiple admin accounts)

**Sign Up**
TBD

**Book Appointments**
- Can be searched for by specialty
- Can be searched for by the doctor's first or last name
- Booking sends a request for an appointment to the doctor on the UI

**Admin View**
- Can Approve/Reject sign up requests
- Can Approve rejected requests
- Can terminate an account
- Rejected requests only store email after 30 days
    - Users cannot use the same email to sign up again after

**Modify Shifts**
- Cancel shift (No appointments on it)
- Blacklist Patients (Blacklist is for all times)
- Change date (No appointments)
- Reschedule shifts (Can have appointments, that become cancelled but a patient can accept the reschedule)

**Modify Appointments**
- Patient
    - Cancel Appointments not within the next 60 mins
    - Can reschedule appointment if a doctor has a shift on the new date
    - Can rate previous doctors (Rating )
- Doctor
    - Can accept/reject appointments
    - Can cancel an appointment
    - Can view additional patient info
    - Can set notes on a patient
    - Live chat