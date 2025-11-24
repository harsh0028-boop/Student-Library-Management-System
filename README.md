# Student-Library-Management-System
A Student Library Management System automates library operations. It features secure admin/student login, full book catalog management, efficient circulation (checkout/return), automatic fine tracking, and history viewing for users.
Project Title 
Student Library Management System 
This console-based software streamlines daily librarian tasks, replacing traditional manual record-keeping with an efficient digital system. Many school libraries still use bulky paper registers, making it difficult and error-prone to search for books or calculate fines. This project automates these processes, enabling the librarian to easily track which books are in stock, who has borrowed them, and their due dates. It acts as a centralized system ensuring timely book returns and maintaining up-to-date inventory.

Key Features:

Live Stock Tracking: The system maintains an accurate count of each book’s copies. For example, if there are 5 copies of Python Programming and one is issued, the available count instantly updates to 4.

Issue Management: It records the student’s name along with the exact date and time when a book is borrowed. It also prevents a single student from borrowing multiple copies of the same book simultaneously.

Automatic Fine Calculation: Upon return, the system compares the return date with the issue date. If the book is kept beyond 7 days, it automatically calculates and displays a fine of Rs 50.

Dynamic Database: New books can be added to the catalog at any time without restarting the program.

Validation Checks: The system prevents invalid operations, such as issuing out-of-stock books or returning books that were never borrowed.

Technologies & Tools Used:

Programming Language: Python 3.x, chosen for its readability and extensive libraries.

Core Concepts: Object-Oriented Programming (Classes and Objects) for modularity and dictionaries for efficient data handling.

Modules: The datetime module manages real-time date and time tracking for issue and return operations.

IDE: Developed and tested using Visual Studio Code but runs on any standard Python interpreter.

Installation & Execution Steps:

Ensure Python is installed by running python --version in your command prompt or terminal.

Save the source code as Library_management.py.

Open a terminal or command prompt and navigate to the saved file’s directory.

Run the program using the command: python Library_management.py.

Follow the on-screen menu by entering numbers (1-5) to interact with the system.

Testing Instructions:

Check Availability: Use Option 1 to display all books and their quantities. Note the count for “Harry Potter.”

Issue a Book: Choose Option 2 and borrow “Harry Potter” under your name. Confirm the quantity decreases by one using Option 1.

Test Out-of-Stock Handling: Attempt to issue a book with zero quantity; the system should deny the request politely.

Return & Fine Simulation: Use Option 3 to return the book. Since waiting 7 days in real-time isn’t practical for demos, temporarily modify the code to impose the fine immediately (set the overdue limit to 0) to observe the fine calculation.

Add New Stock: Select Option 4 to add new books and verify by listing them with Option 1
