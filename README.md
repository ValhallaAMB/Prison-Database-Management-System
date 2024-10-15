# Prison Management System

## Project Purpose
The main goal of this project is to create a reliable and scalable system for managing the operations of a prison facility. It focuses on organizing and handling crucial data effectively, ensuring streamlined operations within the prison. The system will allow administrators to manage prisoners, their labor assignments, cell assignments, and district organization efficiently.

The project involves a single database that contains four tables, each with specific fields and relationships:
- **Prisoners**: Manages prisoner information.
- **Labour**: Manages labor tasks assigned to prisoners.
- **Cells**: Manages different cell types and their assignments to prisoners.
- **Districts**: Organizes cells within specific districts.

## Project Structure
The project consists of controllers, repositories, and models for each core entity, following the MVC (Model-View-Controller) architecture:
- **Prisoner**
  - Prisoner Repository
  - Prisoner Controller
- **Labour**
  - Labour Repository
  - Labour Controller
- **Cell**
  - Cell Repository
  - Cell Controller
- **District**
  - District Repository
  - District Controller

## Technology Stack
The project uses **WampServer** to manage the database using **MySQL Workbench**, with **Spring Boot** as the backend framework. 

### Dependencies
1. **Spring Boot DevTools**: Provides live reloading and automatic application restart features for easier development.
2. **Spring Web**: Simplifies web development, handling HTTP requests and building RESTful services.
3. **Spring Data JPA**: Offers high-level abstraction for data access and database operations.
4. **MySQL Driver**: Facilitates data manipulation and retrieval between the Java application and the MySQL database.

## Database Setup
- The MySQL database is configured via the `application.properties` file. It uses **WampServer** to host the MySQL database locally, and the project establishes connections through Spring Boot.

## Future Enhancements
- Add additional tables for prison staff and incident reporting.
- Implement authentication and role-based access control for different user roles such as administrators and guards.
- Enhance the system by integrating reporting features and analytics.
