Library Management System

Overview

This Library Management System is designed to automate common library functions, streamlining book management, patron management, and the borrowing/returning process. Using a linked list data structure, the system efficiently handles dynamic data, making it easy for library staff to add, search, update, and delete records. This system also provides reporting capabilities to monitor library resources and track patron borrowing history, overdue books, and more.


Features

1. Book Management
   
Add New Books: Allows library staff to add new books with details including:
Unique Book ID
Title
Author
Genre
Year of Publication
Number of Copies Available

Search for Books: Search functionality enables staff to locate books by:
Title
Author
Genre
Book ID
Availability Status (available or borrowed)

Update Book Information: Modify book details or adjust the number of copies available.

Delete Books: Allows removal of books from the library collection, provided they are not currently borrowed by any patron.

2. Patron Management

Register New Patrons: Enables the registration of new patrons with necessary details:
Patron ID (unique)
Name
Contact Details (email and phone number)
Address
Library Card Status (active or inactive)

Search for Patrons: Locate patron records by:
Patron ID
Name
Email

Update Patron Information: Modify patron details like address and contact information.

Delete Patron Records: Delete patron records only if they have returned all borrowed books.

3. Borrowing and Returning
   
Borrow Books: Allows patrons to borrow books with conditions:
Patrons can borrow up to 3 books at a time.
The book requested must be available.

A borrowing record is created for each transaction, including:
Patron ID
Book ID
Date of Borrowing
Due Date (automatically calculated, e.g., 2 weeks from borrowing)

Return Books: When a book is returned:
The system updates the book’s availability.
The borrowing record is removed.

Track Overdue Books: Flags overdue books and provides a list of overdue books and their borrowers.

4. Reporting
Generate Reports: The system can generate the following reports, displayed in a readable format:

Books Currently Borrowed: A list of books currently checked out.

Books Available in the Library: A catalog of all books currently available for borrowing.

List of Overdue Books: A report of overdue books along with the borrowing patrons.

Borrowing History of Individual Patrons: Shows the borrowing history for each patron, including all books borrowed and return status.

Data Structure

The system leverages linked lists to handle dynamic data management efficiently, allowing fast and efficient insertion, deletion, and searching operations.


Usage

Initialize the system and begin by adding books and registering patrons.
Use search functions to locate books or patrons as needed.
Manage Borrowing and Returning to keep track of the library's books and update the records accordingly.
Generate Reports to monitor library resources and track overdue books and borrowing history.
This Library Management System provides essential features for efficiently managing a library and its resources, ensuring that library operations are streamlined and well-organized.






