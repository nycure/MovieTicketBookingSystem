# To get this project or want a custom one made, DM me here. https://t.me/+jmiu8NOkjRthMGQ1
# Movie Ticket Booking System
  A comprehensive web-based movie ticket booking platform built with Java EE, offering a seamless cinema ticketing experience.
  A web-based application that allows users to browse movies and book tickets online. Built with Java Servlets, JSP, and MySQL.
  This repository hosts the code for an Online Movie Ticket Booking System built in Java. 
  This application allows users to browse movies, check available showtimes, and book tickets online. The project follows a structured MVC architecture and is designed to provide a seamless booking experience.



## 🎬 Features
### Both for Admin and User

- **User Management**
  - User registration and authentication
  - Profile management
  - Booking history
  - Admin Authentication
       - Admin Login
       - Admin Dashboard for management of movies, shows, theatres, users, and bookings

- **Movie Management**
  - Dynamic movie listings
  - Detailed movie information
  - Genre categorization
  - Release date tracking
  - Price management

- **Theatre Management**
  - Multiple theatre support
  - Screen management
  - Seat layout configuration
  - Theatre location tracking

- **Booking System**
  - Real-time seat selection
  - Multiple showtime options
  - Secure payment integration
  - E-ticket generation
  - Booking confirmation
    
- **Admin Dashboard**
   - Overview
   - User Management
   - Movie Management(Addition, Updation, Deletion)
   - Theatre Management(Addition, Updation, Deletion)
   - Shows Managament(Addition, Updation, Deletion)
   - Booking Management(Addition, Updation)

## 🛠️ Technology Stack

- **Backend**
  - Java EE
  - Servlets
  - JSP
  - JDBC
  - MySQL

- **Frontend**
  - HTML5
  - CSS3
  - JavaScript
  - Bootstrap 4
  - Font Awesome

- **Database**
  - MySQL 8.0

## ⚙️ Setup Requirements

- JDK 11 or higher
- Apache Tomcat 9.0 or higher
- MySQL 8.0
- Maven

## 🚀 Database Setup

 - **Create a new MySQL database:**
   - Follow schema.sql
                   
 - **Create the required tables:**
   - Follow schema.sql



## Installation & Setup
  - **Clone the repository:**
    - git clone: https://github.com/nycure/movie-ticket-booking-system.git

  - **Configure database connection:**
     - Open src/main/java/com/util/Constants.java
     - Update the database URL, username, and password according to yours

  - **Build the project:**
    
        - mvn clean install
       
  - **Deploy to Tomcat:**
     - Copy the WAR file from target/movie-ticket-booking-system.war to Tomcat's webapps directory
     - Start Tomcat server
       
  - **Access the application:**
    
        -  http://localhost:8080/movie-ticket-booking-system
 # 📁 Project Structure
       movie-ticket-booking-system/
       ├── src/
       │   ├── main/
       │   │   ├── java/
       │   │   │   ├── com/
       │   │   │   │   ├── controller/
       │   │   │   │   ├── booking/
       │   │   │   │   |  ├── model/
       │   │   │   │   |  ├── dao/
       │   │   │   │   ├── User/
       │   │   │   │   |  ├── model/
       │   │   │   │   |  ├── dao/
       │   │   │   │   ├── theatre/
       │   │   │   │   |  ├── model/
       │   │   │   │   |  ├── dao/
       │   │   │   │   ├── showtime/
       │   │   │   │   |  ├── model/
       │   │   │   │   |  ├── dao/
       │   │   │   │   ├── movie/
       │   │   │   │   |  ├── model/
       │   │   │   │   |  ├── dao/
       │   │   │   │   ├── filter/
       │   │   │   │   └── util/
       │   │   ├── webapp/
       │   │   │   ├── css/
       │   │   │   ├── js/
       │   │   │   ├── WEB-INF/
       │   │   │   └── *.jsp
       │   │   └── resources/
       │   └── test/
       ├── pom.xml
       └── README.md
# User Login, Booking a ticket and Download Ticket.
 - **Click on login at top right of the page.**
  ![Login](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399908175-13a71504-bdea-4cc8-9058-533f5e4e4374.png)
 - **Login page will appear Enter your email and password**
   ![Login page](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399908707-1e516cc6-85f8-4ee8-b9bd-3f60d3420ca5.png?raw=true)
 - **Then select the movie which you want to book.**
   ![Screenshot 2025-01-03 141018](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399909148-d5a2588b-718c-4d7c-b5a2-8695a7392a86.png?raw=true)
 - **Then all the showtimes will appear related to that movie, Select any of them which you want.** 
    - click Book Now
   ![Screenshot 2025-01-03 141026](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399909390-14825502-77cb-4e14-a709-99f31eda5224.png?raw=true)
 - **Then select the seats which you want to book.**
   ![Screenshot 2025-01-03 141044](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399909862-94be0877-876b-4357-92c7-0355ab37ba63.png?raw=true)
 - **Then do the payment.**
   ![Screenshot 2025-01-03 141103](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399910086-83527b5f-1cf8-4dec-b024-7ee7cab04c6a.png?raw=true)
 - **After that booking succesful message will appear and your ticket will be genrated.**
   ![Screenshot 2025-01-03 141109](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399910220-42ba3c2d-8827-47ff-a422-991831dbda7f.png?raw=true)
 - **Download Your Ticket.**
   - Note:user can download his ticket from my booking section also if he lost his ticket and also can see his past bookings.
   ![Screenshot 2025-01-03 141120](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399910646-5df0196b-ad3f-4ae4-8dd2-4ebb61c0607c.png?raw=true)
 - **Sample Downloaded Ticket**
   ![high-quality-image (8)](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399911003-30ed1b9b-bdf8-4f61-be99-f0bedf3e7c88.jpg?raw=true)
# Admin Login and Management.
  - **Admin Login.**
   ![Screenshot 2025-01-03 141325](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399912827-9a2fa5f0-6442-4689-84b1-8e8216b4145b.png?raw=true)
  - **Admin Dashboard.**
   ![Screenshot 2025-01-03 151934](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399914890-f7b42c4d-200c-4654-904f-2dda7f23c274.png?raw=true)
  - **Movie Management.**
   ![Screenshot 2025-01-03 141347](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399915215-f20c1ed8-a5f0-4bd4-b832-ce49d3576a97.png?raw=true)
  - **Show Management.**
   ![Screenshot 2025-01-03 141354](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399915378-0253cae9-77d7-4628-aecf-5a53964b6fe6.png?raw=true)
  - **Booking Management.**
   ![Screenshot 2025-01-03 141403](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399915522-51216da3-68b7-499a-9d4c-1656ee4ca1f1.png?raw=true)
  - **User Management.**
   ![Screenshot 2025-01-03 141410](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399915652-f8cae0e6-0335-4d74-a754-f8ed71de8f29.png?raw=true)
  - **Theatre Management.**
   ![Screenshot 2025-01-03 141421](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399915773-efa1f417-5108-46bc-a3e4-c4e0102f3a7d.png?raw=true)

# All other  pages.
 - **Homepage**
   ![Screenshot 2025-01-03 140859](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399916397-f068a6e4-4356-4458-ae2f-fb83bfd43a13.png?raw=true)
 - **Movies Page**
   
   ![Screenshot 2025-01-03 140658](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399916675-76c42a3c-23db-4cb7-96ff-f90568c665b1.png?raw=true)
 - **Showtimes Page**
   ![Screenshot 2025-01-03 140922](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399916936-aa5d2409-42ec-410b-9832-392dba0979b9.png?raw=true)
 - **User Profile page**
   ![Screenshot 2025-01-03 140942](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399917243-b10b376f-44c3-43ef-a63d-80791311f886.png?raw=true)
 - **My Bookings**
   ![Screenshot 2025-01-03 140954](https://github.com/nycure/MovieTicketBookingSystem/blob/main/images/399917316-2a11c437-34d7-41b8-af46-114ee62742e5.png?raw=true)

## 📧 Contact
- Author: Nitin Yadav
- Email: forwork.nitinyadav@gmail.com
