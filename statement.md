Problem Statement

Keeping track of books manually can be difficult, especially when the number of books increases. It can take a lot of time to find a particular book, change its details, or check how many copies are available.

The Book Inventory System is created to solve this problem by providing a simple computer-based way to manage book records. The system keeps basic information such as the book ID, title, author, and quantity in one place.

The main goal of this project is to make managing book records easier, quicker, and more organized.

Scope of the Project

This project focuses on the basic management of books in an inventory. Users can perform common operations such as adding, updating, deleting, searching, and viewing books.

The system can be used to:

Add new books to the inventory.

View all the books currently available.

Change the details of an existing book.

Remove books from the inventory.

Search for a book by its ID, title, or author.

Check that the information entered by the user is valid.

Refresh the table to see the complete inventory.

In the current version, the book data is stored temporarily using an ArrayList. This means that the data will be lost when the application is closed.

The project can be improved later by adding a database, login system, ISBN, price, category, and other useful book details.

Target Users

This system can be useful for:

Small bookshops that need a simple way to keep track of their books.

School and college libraries for maintaining basic book records.

Students who want to learn about Java, Swing, and CRUD operations.

Small organizations that need a simple local system for managing books.

The current version is mainly designed for small-scale use and learning purposes.

High-Level Features
Add Book

Users can enter the book ID, title, author, and quantity to add a new book to the inventory.

View Books

All books are displayed in a table, making it easy to see their ID, title, author, and available quantity.

Update Book

Users can select a book and change its title, author, or quantity.

Remove Book

Users can delete a book from the inventory. The system asks for confirmation before removing it.

Search Book

Users can search for a book using its ID, title, or author. The search also works regardless of whether uppercase or lowercase letters are used.

Input Validation

The system checks the information entered by the user. For example, it does not allow duplicate IDs, empty required fields, or negative quantities.

Refresh

The Refresh button displays the complete inventory again after a search or other operation.

Summary

The Book Inventory System is a simple project designed to make basic book management easier. It provides the main operations needed to maintain an inventory while keeping the interface simple and easy to understand.

The project also provides a good base for adding more advanced features, such as database storage and user login, in the future.
