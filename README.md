Book Inventory System
Project Overview

The Book Inventory System is a simple desktop application made using Java Swing. The main purpose of this project is to make it easier to manage books in an inventory.

Through the application, users can add new books, update book details, remove books, search for a particular book, and view all the books available in the inventory.

The book details are stored in an ArrayList, so the data is available only while the application is running. Once the program is closed, the data will be lost.

Features

The application provides the following features:

Add Book – Allows the user to add a new book by entering its ID, title, author, and quantity.

Update Book – Allows the details of an existing book to be changed.

Remove Book – Removes a book from the inventory after asking for confirmation.

Search Book – Allows users to search for books using the ID, title, or author name.

View Books – Displays all the books in a table.

Refresh – Shows the complete inventory again after performing a search.

Input Validation – Checks for empty fields, duplicate IDs, invalid quantities, and negative quantities.

Easy Selection – Clicking on a book in the table automatically fills its details in the input fields.

Technologies and Tools Used

This project was created using:

Java – Main programming language

Java Swing – Used to create the graphical user interface

ArrayList – Used to store book information

JTable – Used to display the inventory

DefaultTableModel – Used to manage the data in the table

Java AWT – Used for layouts and GUI components

The project can be developed and run using any Java IDE, such as IntelliJ IDEA, Eclipse, NetBeans, or Visual Studio Code.

Project Structure

The main Java file contains the complete application, including the book class, GUI, inventory operations, validation, and main method.

Installation and Running the Project
Requirements

Before running the project, make sure Java is installed on your computer.

You can check this by opening a terminal or command prompt and typing:

java -version


You can also check the Java compiler using:

javac -version

Running from the Command Line

Create a folder for the project.

Save the Java code in a file named:

BookInventorySystem.java


Open the terminal inside the project folder.

Compile the program:

javac BookInventorySystem.java


Run the program:

java BookInventorySystem


The Book Inventory System window should now open.

Running Using an IDE

If you are using an IDE:

Create a new Java project.

Create a class named BookInventorySystem.

Copy the provided Java code into the class.

Save the file.

Run the main() method.

The application window will appear.

Sample Data

Some books are already added when the program starts so that the application can be tested easily.

ID	Title	Author	Quantity
B001	The Downpour	Andrew yadav	5
B002	Effective Java	Joshua Baloch	3
B003	Clean Code	Robert C. Martin	7
Testing the Application

The following steps can be used to check whether the main features are working correctly.

1. Check the Inventory

Start the application and look at the table.

Expected result:
The three sample books should be displayed.

2. Test Adding a Book

Enter the following details:

ID: B004
Title: Java Basics
Author: Test Author
Quantity: 5


Click Add.

Expected result:
The new book should appear in the table and the input fields should become empty.

3. Test Duplicate ID

Try adding another book using an existing ID, such as B001.

Expected result:
The program should show an error saying that a book with that ID already exists.

4. Test Invalid Quantity

Try entering a negative number such as -5 as the quantity.

You can also try entering text such as abc.

Expected result:
The program should display an error and should not add the book.

5. Test Updating a Book

Select a book from the table and change its title, author, or quantity.

Click Update.

Expected result:
The changes should appear in the table.

6. Test Removing a Book

Select a book and click Remove.

A confirmation box will appear.

Click Yes.

Expected result:
The selected book should be removed from the table.

If No is selected, the book should remain in the inventory.

7. Test Searching

Enter a book ID, title, or author name in the search box and click Search.

For example:

Clean


Expected result:
The table should show the matching book.

The search is not case-sensitive, so clean, Clean, and CLEAN should give the same result.

8. Test Refresh

After performing a search, click Refresh.

Expected result:
The search field should be cleared and all books in the inventory should be displayed again.

Limitations

There are a few limitations in the current version of the project:

The data is stored only in memory.

All book data is lost when the application is closed.

There is no database connected to the application.

There is no login or user authentication.

The application is intended for use as a simple local desktop system.

Future Improvements

The project can be improved in the future by adding:

MySQL or SQLite database support

File-based data storage

ISBN, price, category, and publisher fields

Sorting and filtering options

Inventory statistics

Login and user authentication

A more modern and attractive GUI

Conclusion

The Book Inventory System is a basic Java Swing project that demonstrates how a desktop application can be used to manage book records.

It covers the basic CRUD operations (Create, Read, Update, and Delete) along with search and input validation. The project is simple to use and can also be extended with features such as database storage and user authentication in the future.
