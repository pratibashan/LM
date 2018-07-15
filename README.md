# LIBRARY MANAGEMENT SYSTEM


### Overview 

It's a web portal that manages books and users. Users based on their authentication , they are determined as Admins and regular users. Library Admins can login and manage books and users.  Library users can register and login to the site. Users can view all available books and check-in and check-out books as well. 

---

### Technologies Used

* HTML5
* JavaScript
* CSS3
* Node.js
* Express.js
* PostgreSQL

---

### MVP

* Add,View, Modify and Delete Books
* Add,View, Modify and Delete Users
* User Registration
* User Login
* User Check-in Books
* User Check-out Books
* Search Books by Title

---
### Stretch Goals

* Add books using Google API
* Library Report

---

### Challenge and Solution
1. Google API have a limitation of hits per day. Instead of using Google API for each request using ISBN, we stored all books related info( Title, Author, Description,Book Images) in PostgreSQL.

2. Google API  supports only Hard-cover books which is a set back for us. So manually add books for non-Hard-cover books.

3. Books Description for too big to display , and solved my viewing this in tool-tip. 

---

