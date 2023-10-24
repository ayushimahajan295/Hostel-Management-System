# Hostel-Management-System
Hostel Management system addresses the common issue of Allocation faced by hostels for initial allocation of students. It uses a menu driven program to systematically help in the process.
# Problem Statement:
In a college or university, it's common to have a hostel or dormitory where students live during their
academic years. Managing the accommodation for a large number of students efficiently can be
challenging. The Hostel Accommodation Management System is designed to address this problem by
providing a software solution to manage student accommodations within a college hostel. Here’s the
description of the problem it solves:
● Student Allocation
● Student Removal and Modification
● Displaying Student Details
● User Interface
# Explanation:
The Hostel Accommodation Management System is designed to manage student accommodations
efficiently. It allows students to be added, modifying details, and later removing students from
their allocated rooms if necessary. The system distinguishes between undergraduate and postgraduate
students, keeping track of their names, roll numbers, branches, and the number of beds they have been
assigned. It simplifies the management of hostel accommodations, ensuring efficient allocation and tracking of resources.
The Hostel Accommodation Management System provides a software solution for managing student
accommodations efficiently. It includes the following components:
This C++ program is a basic Hostel Management System. It consists of a class hostel that manages room bookings and student records.
Here's a concise breakdown:
● Class hostel:
Manages room details like number, student name, address, and phone number.
2.Provides functions for operations like booking a room, displaying records, checking room availability, and editing records.
● Menu Function (int hostel::menu()): 
1.Displays a menu with options to perform different tasks.
2.Based on user input, it calls corresponding functions.
● Add Room Function (int hostel::add_room()):
Takes room details and checks availability before booking.
● Display Room Function (int hostel::display_room()):
1.Searches for a room's record and displays it.
● Room Selection Function (int hostel::room_sel()):
1.Lists all allocated rooms along with student details.
● Edit Selection Function (int hostel::edit_sel()):
1.Allows modifying or deleting customer records.
● Check Availability Function (int hostel::check_avail(int r)):
1.Determines if a room is already booked.
● Modify Room Function (int hostel::modify_room(int room_)):
1.Updates details of a booked room.
● Delete Room Function (int hostel::delete_room(int r)):
1.Removes a customer record.
● Main Function:
1.Creates an instance of hostel.
2.Displays an initial message and waits for a key press to start.
3.Calls the menu() function to begin the interaction.
