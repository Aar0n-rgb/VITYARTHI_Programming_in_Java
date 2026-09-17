Problem Statement

Maintaining records of books by hand or spreadsheet can be tedious, especially as the number of books increases. It can also take a long time to search for a particular book, edit its details, or know how many copies are in stock.

The Book Inventory System is developed to address this issue by providing a simple computer-based solution to maintaining book records. This system stores information such as book ID, title, author, and quantity in one place easily.

The idea of the project is to provide a convenient way of managing book records.

The Scope of the Project

The project focuses on managing books in the inventory at a fundamental level. This implies that the system allows the users to carry out the following operations:

• Adding a book

• Viewing books

• Updating a book

• Deleting a book

• Searching for a book

• Validating the input

• Refreshing the table

The scope does not include advanced concepts such as a database, login interface, or other features that would be covered in more complex projects. In the current version of the system, the record of the book is temporarily stored in a java.util.ArrayList. This means that the information will be deleted when the application is closed. However, the system can be enhanced to include features such as a graphical user interface, database, login system, ISBN, and price.

Target Users

This project would benefit several users such as:

• Small-scale bookshops that need a record of the books they have in stock.

• School and college libraries that require a system to manage the book inventory.

• Students studying computer science who need to develop skills in Java, Swing, and simple CURD operations using Java.

• Small organizations that need to manage their book inventory system locally.

The current scope of the project is geared towards small-scale organizations and students.

High-Level Features

The Book Inventory System has the following features:

Add Book

This feature enables the user to add a book to the system by providing the relevant book information.

View Books

This option allows the user to view all the books in the inventory. The book details such as the book ID, title, author, and quantity are extracted and displayed in a table.

Update Book

This functionality allows the user to update the book details by specifying the book ID.

Remove Book

This feature allows the user to remove a book from the inventory. The user gets a warning before the book is permanently deleted.

Search Book

This option allows the user to search for a book by title, book ID, or the author. It also ignores the case of the characters when the search is being performed.

Input Validation

This system ensures that the user provides correct input. It detects some errors such as repeated book IDs, leaving no input in the text fields, and negative quantity.

Refresh

This button is used to refresh or reload the table when a search or any other operation has been performed.

Summary

The Book Inventory System is a small project that aims to provide a convenient way of managing book records. Apart from providing the basic operations of managing a book inventory, it also serves as a good starting point for more advanced projects. The system includes a set of basic functions that can be used to develop skills in Java Swing and CURD operations. Advanced functions such as a database can be added to enhance the system further.
