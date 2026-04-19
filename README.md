# Lost and Found Management System (Java)

## Description

This is a console-based Java application that helps manage lost and found items in a centralized system.
Users can report lost or found items, search for items, and update their status.

The system uses a menu-driven interface and stores data temporarily using a HashMap for efficient access.

---

## Features

* Report a lost item
* Report a found item
* View all items in the system
* Search items using keywords (name, description, or location)
* Mark items as claimed
* Delete items from the system
* Unique ID assigned to every item
* Input validation for numeric entries

---

## How It Works

* Each item is stored as an object with attributes like name, description, location, date, and contact
* Items are stored in a HashMap for fast lookup using ID
* A menu-driven loop allows users to interact with the system
* Search is performed using keyword matching across multiple fields
* Status of items can be updated from "Open" to "Claimed"

---

## Tech Used

* Java
* OOP Concepts (Encapsulation, Classes, Methods)
* Collections Framework (HashMap)

---

## How to Run

1. Compile the program:
   javac LostAndFoundPortal.java

2. Run the program:
   java LostAndFoundPortal

---

## Sample Output

=================================
LOST & FOUND MANAGEMENT
=======================

1. Report Lost Item
2. Report Found Item
3. View All Items
4. Search Item
5. Mark Item as Claimed
6. Delete Item
7. Exit

Enter your choice: 1

--- Report Lost Item ---
Enter item name: Wallet
Enter description: Black leather wallet
Enter location: Library
Enter date (YYYY-MM-DD): 2026-03-31
Enter contact info: 9876543210

Lost item reported successfully with ID: 3

---

## Limitations

* Data is not stored permanently (no database)
* Console-based interface only
* No authentication system

---

## Future Improvements

* Add database integration (MySQL / MongoDB)
* Build a GUI (JavaFX / Swing)
* Add user login system
* Implement filtering by date or location
* Deploy as a web application

---

## Author

Charan
