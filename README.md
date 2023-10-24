# Hostel-Management-System
Hostel Management system addresses the common issue of Allocation faced by hostels for initial allocation of students. It uses a menu driven program to systematically help in the process.
# Problem Statement:
In a college or university, it's common to have a hostel or dormitory where students live during their
academic years. Managing the accommodation for a large number of students efficiently can be
challenging. The Hostel Accommodation Management System is designed to address this problem by
providing a software solution to manage student accommodations within a college hostel. It uses the concepts of OOPS in C++.
It uses inheritance, polymorphism, abstraction and encapsulation.
Here’s the description of the problem it solves:<br />
● Student Allocation<br />
● Student Removal and Modification<br />
● Displaying Student Details<br />
● User Interface<br />
# Explanation:
The Hostel Accommodation Management System is designed to manage student accommodations
efficiently. It allows students to be added, modifying details, and later removing students from
their allocated rooms if necessary. The system distinguishes between students, keeping track of their names, roll numbers,
address and phone number. It simplifies the management of hostel accommodations, ensuring efficient allocation and tracking of resources.
The Hostel Accommodation Management System provides a software solution for managing student
accommodations efficiently. It includes the following components:<br />
This C++ program is a basic Hostel Management System. It consists of a class hostel that manages room bookings and student records.
Here's a concise breakdown:<br />
● Class hostel:<br />
1.Manages room details like number, student name, address, and phone number.<br />
2.Provides functions for operations like booking a room, displaying records, checking room availability, and editing records.<br />
● Menu Function (int hostel::menu()):<br />
1.Displays a menu with options to perform different tasks.<br />
2.Based on user input, it calls corresponding functions.<br />
● Add Room Function (int hostel::add_room()):<br />
Takes room details and checks availability before booking.<br />
● Display Room Function (int hostel::display_room()):<br />
1.Searches for a room's record and displays it.<br />
● Room Selection Function (int hostel::room_sel()):<br />
1.Lists all allocated rooms along with student details.<br />
● Edit Selection Function (int hostel::edit_sel()):<br />
1.Allows modifying or deleting customer records.<br />
● Check Availability Function (int hostel::check_avail(int r)):<br />
1.Determines if a room is already booked.<br />
● Modify Room Function (int hostel::modify_room(int room_)):<br />
1.Updates details of a booked room.<br />
● Delete Room Function (int hostel::delete_room(int r)):<br />
1.Removes a customer record.<br />
● Main Function:<br />
1.Creates an instance of hostel.<br />
2.Displays an initial message and waits for a key press to start.<br />
3.Calls the menu() function to begin the interaction.<br />
# Class Diagram: <br />
  +------------------------------------+<br />
  |              hostel                 |<br />
  +------------------------------------+<br />
  | - room_number: int                  |<br />
  | - name: char[50]                    |<br />
  | - address: char[50]                 |<br />
  | - phone_number: char[50]            |<br />
  +------------------------------------+<br />
  | - add_room(): int                   |<br />
  | - display_room(): int               |<br />
  | - room_sel(): int                   |<br />
  | - menu(): int                       |<br />
  | - check_avail(int): int             |<br />
  | - modify_room(int): int             |<br />
  | - delete_room(int): int             |<br />
  +------------------------------------+<br />
                   △<br />
                   |<br />
                   |<br />
                   |<br />
                   |<br />
                   |<br />
                   |<br />
  +------------------------------------+<br />
  |   menuclass (inherits from hostel)  |<br />
  +------------------------------------+<br />
  | - menu(): int (overrides)           |<br />
  +------------------------------------+<br />
