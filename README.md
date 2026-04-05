
📝 Abstract

This project implements a simple ticket reservation system using the C programming language.
It demonstrates the use of dynamic memory allocation, 
structures, and menu-driven programming to perform CRUD (Create, Read, Update, Delete) operations. 
The system allows users to book tickets, view existing reservations, update ticket details,
and cancel bookings, providing a practical example of managing records in memory.

📖 Introduction

Ticket reservation systems are widely used in transportation, entertainment, and event management industries.
This project aims to simulate a basic reservation system that can handle multiple ticket records dynamically.
By using structures to represent tickets and dynamic memory allocation (malloc, realloc, free),
the program avoids fixed-size limitations and adapts to user input. The menu-driven interface ensures ease of
use and provides clear options for managing reservations.

⚙️ Methodology

The system is built around the following components:
- Data Structure
- A struct Ticket holds ticket details: ID, customer name, and number of seats.
- An array of struct Ticket is dynamically resized using realloc.
- Operations (CRUD)
- Book Ticket (Create): Adds a new ticket record by reallocating memory and storing user input.
- View Tickets (Read): Displays all existing reservations in a formatted list.
- Update Ticket (Update): Searches for a ticket by ID and modifies its details.
- Cancel Ticket (Delete): Removes a ticket by shifting array elements and resizing memory.
- Memory Management
- Dynamic allocation ensures scalability.
- Memory is freed upon program exit to prevent leaks.
- User Interaction
- A loop-driven menu provides options until the user chooses to exit.
- Input validation and feedback messages improve usability

<img width="342" height="259" alt="Screenshot 2026-04-05 173351" src="https://github.com/user-attachments/assets/68bcbdee-0f90-4ace-b36b-57d9aa82fdd6" />
<img width="456" height="273" alt="Screenshot 2026-04-05 173413" src="https://github.com/user-attachments/assets/860f4c8d-4781-491d-baee-fd98e34a39c9" />
<img width="341" height="280" alt="Screenshot 2026-04-05 173433" src="https://github.com/user-attachments/assets/55e36751-2962-4c40-a15f-2714f67046a3" />
<img width="579" height="222" alt="Screenshot 2026-04-05 173443" src="https://github.com/user-attachments/assets/ad61f487-b202-4810-94ec-e2019499616d" />
<img width="522" height="178" alt="Screenshot 2026-04-05 173451" src="https://github.com/user-attachments/assets/cd3d3d83-2e2c-4a5c-ab2c-ed6140db0262" />

✅ Conclusion

The ticket reservation system successfully demonstrates how C can be used to implement a practical record management application.
It highlights key programming concepts such as structures, dynamic memory allocation, and menu-driven design.
While simple, the system can be extended with features like file storage, duplicate ID checks, and input validation for real-world use.
Overall, this project serves as a foundational example of applying C programming to solve everyday problems in reservation management.
















