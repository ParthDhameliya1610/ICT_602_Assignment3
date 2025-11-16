Project:

A comprehensive Java-based healthcare management system that enables patients to book appointments, doctors to manage schedules, and administrators to oversee the entire system.


System Requirements
Operating System: Windows 10/11, macOS 10.14+
Java Version: Java 8 or higher (Java 11+ recommended)
IDE: NetBeans 19 or higher

Download NetBeans 20:

Visit: https://netbeans.apache.org/download/nb19/
Download "Apache NetBeans 19" for your operating system
Or download from: https://archive.apache.org/dist/netbeans/netbeans/19.0/

Install NetBeans:

Windows: Run the .exe installer


Download Project zip file and Extract the ZIP file to your desired location

1. Launch NetBeans

Open the Project:

File --> Open Project (or press Ctrl+Shift+O)

Navigate to the extracted SmartHealthcareSystem folder

Select the folder (you should see the NetBeans project icon)

Click Open Project


2. Clean and Build:

Right-click on SmartHealthCareSystem project in Projects window

Select Clean and Build (or press Shift+F11)

Wait for "BUILD SUCCESSFUL" message in Output window

3. Run the Application:

Right-click on SmartHealthcareSystem project

Select Run

The application will start in the Output window



Sample Data and Pre-loaded Accounts

Default Admin Account

Email: admin@health.com
Password: admin123
Role: Admin

you can create another admin 

Doctor:
Name: Dr. Johnson
Email: johnson@hospital.com
Phone: 9876543210
Password: Johnson
Specialist: Cardiology


Patient:
Name: mawell
Email: mawell@email.com
Phone: 8451245123
Password: mawell
Date of Birth: 1985-03-15


Start The Application:
----------------------

run application in netbeans start --> run


Displayed Main Menu

Welcome to Smart Healthcare Appointment and Management System

Main Menu

1. User Sign up
2. User Log in
3. Exit Application

Enter Main Option: 


* Test invalid option 

enter 5 

Invalid main menu option. Please choose correct option

* User Register:

Enter 1 it will ask the user signup details once it is completed it will show successful message

User Successfully Registered: Doctor Name

* User patient

Enter 2 

User Successfully Registered: Patient Name

* Duplicate user registration

Try registering with the same email

Email already registered

* Admin Functionality Testing

Login as Admin:

Enter Main Option: 2
Enter Email Address: admin@health.com
Enter Password: admin123
User Successfully Logged In: System Admin (Admin)
View All Doctors:

Admin Menu
Enter Admin Option: 1
Expected: Display table with Dr. Sarah Johnson

Add Doctor Availability:

Enter Admin Option: 2
Enter Doctor Email: johnson@hospital.com
Enter Available Time (HH:mm): 10:00
Enter Available Date (yyyy-MM-dd): 2024-12-20
Availability added for johnson@hospital.com

View All Patients:

Enter Admin Option: 4
Expected: Display table with John Smith

View All Appointments:

Enter Admin Option: 3
No appointments found

Logout:

Enter Admin Option: 7
Expected: Admin logged out successfully


Phase 4: Patient Functionality Testing
Login as Patient:

Enter Email Address: john.smith@email.com
Enter Password: patient123
User Successfully Logged In: John Smith (Patient)

View Available Doctors:

Patient Menu
Enter Patient Option: 1
Display Dr. Johnson with availability

Book Appointment:

Enter Patient Option: 2
Enter Diagnose: Regular Checkup
Enter Doctor Name: Dr. Sarah Johnson
Enter Appointment Date (yyyy-MM-dd): 2024-12-20
Enter Appointment Time (HH:mm): 10:00
Appointment booked successfully with Dr. Sarah Johnson

View Appointment History:

Enter Patient Option: 3

Display the booked appointment in table format

View Profile:

Enter Patient Option: 4
Display patient information in table format



Edit Profile:

Enter Patient Option: 5
Enter new Email (or leave blank to keep): 
Enter new Phone (or leave blank to keep): 1234567899
Enter new Password (or leave blank to keep): 
Profile updated successfully

Phase 5: Doctor Functionality Testing

Login as Doctor:

Enter Email Address: johnson@hospital.com
Enter Password:Johnson
User Successfully Logged In: Dr. Johnson (Doctor)

View Patients:

Doctor Menu
Enter Doctor Option: 1
Display John Smith with appointment details

Add Prescription:

Enter Doctor Option: 2
Enter Patient Email: mawell@email.com
Enter Prescription: dolo 2mg
Prescription added/updated successfully for maxwell@email.com


Logout:

Enter Doctor Option: 3
Expected: "Doctor logged out successfully."


* Advanced Testing

Test Appointment Rescheduling (as Patient):

Enter Patient Option: 6
Enter Doctor Name of appointment to reschedule: Johnson
Enter new Date (yyyy-MM-dd): 2024-12-21
Enter new Time (HH:mm): 14:00


Test Appointment Cancellation (as Patient):

Enter Patient Option: 7
Enter Doctor Name of appointment to cancel: Johnson


Verify Data Consistency (as Admin):

Login as admin and check all appointments

Verify changes are reflected correctly




3. Exit Application

Enter 3

exit application

Display the Thank you for using Smart Healthcare Appointment and Management System



