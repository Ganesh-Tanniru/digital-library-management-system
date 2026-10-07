#  Digital Library Management System

A simple web-based Digital Library Management System developed using Java, Spring Boot, MySQL, HTML, CSS, JavaScript, and Bootstrap.

##  Features

- User Registration
- User Login
- View Available Books
- Add Books
- Edit Book Details
- Delete Books
- Issue Books
- Track Book Availability
- Admin Dashboard

##  Technologies Used

- Java 25
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- HTML
- CSS
- JavaScript
- Bootstrap
- Maven
- Git & GitHub

##  Project Structure

```text
src/main/java/com/library/management
├── controller
├── entity
├── repository
└── service

src/main/resources/static
├── index.html
├── register.html
├── login.html
├── books.html
├── admin.html
└── manage-books.html
 How to Run
1. Clone the repository
git clone git@github.com:Ganesh-Tanniru/digital-library-management-system.git
2. Create MySQL Database
CREATE DATABASE library_db;
3. Configure MySQL

Create:

src/main/resources/application.properties

Add your local MySQL username and password.

Example:

spring.datasource.url=jdbc:mysql://localhost:3306/library_db
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

server.port=8081

application.properties is excluded from GitHub using .gitignore for security.

4. Run the Application

Run LibraryManagementApplication.java from Spring Tool Suite or Eclipse.

The application will start at:

http://localhost:8081
 Application Pages
Page	URL
Home	http://localhost:8081/index.html
Register	http://localhost:8081/register.html
Login	http://localhost:8081/login.html
Books	http://localhost:8081/books.html
Admin Dashboard	http://localhost:8081/admin.html
Manage Books	http://localhost:8081/manage-books.html
REST APIs
Book APIs
POST   /books
GET    /books
PUT    /books/{id}
DELETE /books/{id}
User APIs
POST /users
POST /users/login
GET  /users
Issue APIs
POST /issues
PUT  /issues/return/{issueId}
 Learning Outcomes
Developed REST APIs using Spring Boot
Implemented CRUD operations using Spring Data JPA
Connected Spring Boot with MySQL
Integrated frontend with backend REST APIs
Practiced Git and GitHub
Built a basic full-stack Java application
 Author

Ganesh Tanniru

B.Tech – Computer Science and Engineering
