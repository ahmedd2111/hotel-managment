Description
This project is a Hotel Reservation System designed to serve both customers and hotel managers. It provides an interactive interface where customers can register their personal details, view room availability, check room types and pricing, and log out when finished.

For managers, an admin page is accessible through a password, enabling access to financial reports, billings, employee records (names, departments, wages), room service status, and inventory management for cleaning supplies.

UML Class Design
The system is built using Object-Oriented Programming (OOP) principles in C++, with the following classes:

Customer Class
Represents the customer with attributes like name, email, phone number, and an associated reservation. It supports getters, setters, a constructor, and a display() method to show customer details.

Reservation Class
Represents a hotel reservation with details such as guest name, room type, number of guests, and reservation dates. It includes overloaded operators (+ and -) for date manipulation, along with the standard getters, setters, and a display() method.

Room (Abstract Base Class)
Defines a base structure for different room types, holding room number, type, and cost. It supports standard getters, setters, and a virtual display() method for polymorphism.

StandardRoom & Suite Classes
Derived from Room, these classes represent specific room types. They inherit from Room and override the display() method to customize output.
