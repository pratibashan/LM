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
<img width="1436" alt="screen shot 2018-07-14 at 8 26 51 pm" src="https://user-images.githubusercontent.com/38846724/42729670-db000a22-87a4-11e8-9ef4-21b1b87f3417.png">

<img width="1440" alt="screen shot 2018-07-14 at 8 27 29 pm" src="https://user-images.githubusercontent.com/38846724/42729674-133386ee-87a5-11e8-8df1-3a9bb7d58e83.png">

<img width="1439" alt="screen shot 2018-07-14 at 8 28 26 pm" src="https://user-images.githubusercontent.com/38846724/42729680-561d6164-87a5-11e8-8c57-0b6c7a92204e.png">



