#   Django Online Library Management System Project


The main objective of this project is to manage the details of the students, books and the issued books efficiently. This project helps to keep all the records of the library.

##  Project Prerequisites:

You must know the following languages required for this online library management system project:


-   HTML
-   CSS
-   Bootstrap
-   Django



##  Project Features:

### For admin

-   Admin can add new books
-   View the whole list of books and delete any book
-   View the whole list of students and delete any student
-   Issue a book to a student
-   View all the issued books


### For students

-   A student can see his/her profile
-   Edit their profile
-   Can change password
-   View the issued book by them


##  Description

-   On the homepage of the library management project, there are various options like student registration, student login and admin login. Students can register through register as student option. Then they can also login by clicking on student login. Admin can login through admin login.

-   After the admin login, the admin can add new books or delete a book. Admin just have to give the details of the book in a form and add that book.

-   As we have saved all the details of the book inside the book model, then from the book model we fetch all the data of the books and display it in the form of a table.

-   All the details of the registered students are displayed in the form of a table. The admin is able to see the students list.

-   Students can ask the admin whichever book they want to issue. Then the admin can issue a book to students by selecting the book and the student.

-   After issuing the books, the admin can view all the issued books by students. If the date of issue crosses 14 days then a fine of Rs 5 each day will also be shown. After returning the book the admin can delete the issued book details of the students.

-   After login, students can see their profile which contains all the details that they had entered while registration.

-   On clicking on the edit profile button on the profile page, students can edit some of the details from their profile.


##  Summary


With this project in Django, we have successfully developed an Online Library Management Project. We have used front-end (html, css, bootstrap) to design the pages and also back-end databases (Django) for storing and fetching data.