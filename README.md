# Library_System
###  C++ console project for library system to maintain information about books and users.
###  Description :    
It's a library system, which offer a lot of functions to manage the books and users as the following->
- Each book has: id, name, quantity.
- Each user has: id and name.
- System allows adding a book or a user by reading the above inforamtion.
- Books Operations:
    - List the books sorted either based on id or name.
    - Given a prefix, list all books with this prefix string.
    - Given a book name, list all users borrowed such a book.
- User Operations:
    - User can borrow or return a book.
    - List all system users with borrowed books IDs sorted.

### you can perform many functions by choosing different options as follow:
   1. To Add new book
   2. To search book with its prefix name
   3. Print the users who borrowed the book
   4. Print all books sorted by id
   5. Print all books sorted by name
   6. To Add user to the system
   7. To make a borrow book request for a user
   8. Return a book to the library
   9. Print all users with book's id
   10. Exit the program
* #### I used structures ("struct") to build my own data structure to store the data of the users and books (**struct User**, **struct Book**)
