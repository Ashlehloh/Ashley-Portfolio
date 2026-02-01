Projects:

Flight Information Display System (FIDS): https://github.com/allergictoshellfishh/S10266970_PRG2Assignment

This duo group project is a console-based Flight Information Display System (FIDS) developed for my Programming 2 module assignment.
The system simulates the operations of Terminal 5 at Changi Airport, allowing airport staff to manage daily flight information, boarding gate assignments and airline billing using Object-Oriented Programming (OOP) principles.
The application loads flight, airline and boarding gate data from CSV files and provides an interactive menu-driven interface for managing flights throughout a single operational day.

Project Objectives

The goal of this assignment was to:
Design and implement a multi-class object-oriented system
Apply relationships between classes such as association and aggregation
Handle real-world constraints such as:
Unique flight numbers per day
Limited boarding gates
Special boarding requirements
Perform validation for all user inputs
Implement sorting, collections and file handling

Key Features

Basic Features
Load airlines, flights and boarding gates from CSV files
Display all flights and boarding gates
Assign boarding gates to flights
Create, modify and delete flight records
Display full flight details by airline
Display all scheduled flights in chronological order
Input validation for all user actions

Advanced Features
Automatically assign unassigned flights to suitable boarding gates in bulk
(based on availability and special request requirements)
Compute daily airline fees and promotional discounts, including:
Arrival and departure fees
Boarding gate base fees
Special request code fees
Stackable promotional discounts

🛠️ Technical Highlights

Implemented using C# console application
Designed using an object-oriented architecture based on a provided class diagram

Uses:
dictionaries and collections for fast lookups
queues for bulk flight processing
file I/O for loading and appending CSV data
Flights implement IComparable<T> to support chronological sorting

🧩 System Capabilities

The system supports:
Tracking flight information (flight number, airline, origin, destination, time, status)
Managing boarding gates and their supported special request codes
Assigning gates manually and automatically
Maintaining consistency such as:
One boarding gate per flight
One flight per gate per day
Generating a detailed billing breakdown for each airline, including total fees and discounts

👩‍💻 What I Learned

Through this project, I strengthened my understanding of:
Object-oriented design and class responsibility separation
Data validation and defensive programming
Collection-based data management
Implementing real-world business rules in code
Building maintainable and extensible console applications

▶️ How to Run

Open the solution in Visual Studio
Ensure the CSV files (airlines.csv, flights.csv, boardinggates.csv) are present in the project directory
Run the console application
Follow the interactive menu to manage the system

This project was completed as part of a graded Programming 2 assignment and demonstrates my ability to design and implement a structured object-oriented system with real-world operational logic.
