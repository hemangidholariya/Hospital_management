# Hospital_management

##Problem: 

  Hospitals struggle with double-booking doctors and tracking unpaid bills manually. This project builds a relational database to automate these processes.

##Solution: 

  I designed a normalized database (3NF) to manage patients, doctors, and appointments. I implemented automation using SQL logic to ensure data integrity and streamline billing.

##Key Features:

  Automated Billing: Used a TRIGGER to automatically generate invoices when an appointment is completed.
  
  Conflict Prevention: Wrote a STORED PROCEDURE to prevent double-booking doctors at the same time slot.

  Data Security: Used VIEWS to allow receptionists to see schedules without accessing sensitive patient medical history.

##Tech Stack:

  SQL Server (T-SQL)

##Concepts: 

  Joins, Aggregate Functions, Normalization, ACID Properties.
