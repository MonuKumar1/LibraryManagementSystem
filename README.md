# Library Management System
 A local library is in dire need of a web application to ease their work. The library management system must allow a librarian to track books and their quantity, books issued to members, book fees.
 For the sake of simplicity, you don't have to implement sessions and roles, you can assume that the app will be used by the librarian only.

# The following functionalities are there in  application:

 Base Library System
 Librarians must be able to maintain:

 Books with stock maintained
  Members
  Transactions
 The use cases included here are to:

 Perform general CRUD operations on Books and Members
 Issue a book to a member
 Issue a book return from a member
 Search for a book by name and author
 Charge a rent fee on book returns
 Make sure a member’s outstanding debt is not more than Rs.500


# Overview
### Home page
 * The Home page covers all the books that are currently in the inventory, if the Librarian wishes to add more books, 
they can go to the add books page and search using the keywords of the book. 

* The home page also provides the option to rent out a book, it redirects to the rent-out page from where the Librarian can select from the list of available members, if the user wants to add new members, they can move to the members page where they can add the member's name and their initial balance. 

##### Home Page
 


##### Add Books Page
 


#####  Rent Out Page


#####  Add Members Page

* Disabled Delete buttons implies that the member has taken a book and the member cannot be deleted until they have returned the book.



### Return Book Page

* If the member wants to return the book the librarian can head to the return book page and click on return, after return a summary page is displayed which shows the current balance of the user and the total amount paid to the library, the fees for renting a book is calculated by the formula => 500₹ (initial charges) + 10₹ X (The number of days for which the book was issued) 

#####  Return Page



#####  Summary Page


### Transactions Page

* To see the transaction history the Librarian can head to the transactions page which shows the transactions arranged from most recent to least recent, A transaction in which the book was rented is shown by red color and a transaction in which the book was returned is shown by green color. 

#####  Transactions Page



### Analytics Page

* The Analytics Page shows the top 5 books which were issued the greatest number of times and the top 5 spenders who have spent the most amount of money in the library. 



