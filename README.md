# MovieTicketBookingSys
This repository contains a JavaFX-based Clinic Appointment Booking System designed to streamline the process of scheduling medical appointments. The application provides a user-friendly interface for patients to book appointments with doctors, while also offering robust backend functionality for managing appointments, patients, and payments.
# Project Structure
The project follows a well-organized MVC (Model-View-Controller) architecture:
src/├── main/│   ├── java/│   │   ├── com.example.clinicappointmentsystem/│   │   │   ├── AppointmentsAndEntities/ - Core domain classes│   │   │   │   ├── Appointment.java│   │   │   │   ├── BaseEntity.java│   │   │   │   ├── Doctors.java│   │   │   │   └── Patient.java│   │   │   ├── Payment/ - Payment processing classes│   │   │   │   ├── CashPayment.java│   │   │   │   ├── CreditCardPayment.java│   │   │   │   └── Payment.java│   │   │   ├── SimilarModules/ - Utility classes│   │   │   │   ├── Check.java│   │   │   │   ├── CrudOperations.java│   │  │   │   ├── DetailsLoader.java│   │   │   │   └── FileManager.java│   │   │   ├── AppointmentView.java - Appointment view controller│   │   │   ├── HelloApplication.java - Main application class│   │   │   └── HelloController.java - Main controller│   ├── resources/│   │   ├── com.example.clinicappointmentsystem/│   │   │   ├── Appointment-view.html - Appointment management UI│   │   │   └── hello-view.html - Welcome screen│   │   └── images/ - Application images└── module-info.java - Java module configuration
# Key Features
1. Doctor Listing & Appointment Booking: 
View prestigious doctors with their specialties

See available time slots for each doctor

Simple "Get Appointment" button to initiate booking process

2. Comprehensive Appointment Management:

Create new appointments

Search existing appointments

Update appointment details

Delete appointments when needed

3. Flexible Payment Options:

Support for both cash and credit card payments

Extensible payment system architecture

4. Data Persistence:

File-based data storage system

CRUD operations for all entities

User Interface
5. The application features two main screens:

Welcome Screen: Displays available doctors with their specialties and available time slots

Appointment Management Screen: Allows users to insert, search, delete, and update appointment details after selecting a date and time slot

# Technologies Used
Java

JavaFX for the user interface

HTML for view templates

File-based data storage

# How to Use
Run the application to see the list of available doctors

Select your preferred doctor and time slot

Click "Get Appointment" to proceed to the booking screen

Fill in patient details and confirm the appointment

Use the management interface to view, edit, or cancel appointments as needed

This system is ideal for small to medium-sized clinics looking to digitize their appointment booking process while maintaining simplicity and efficiency.
