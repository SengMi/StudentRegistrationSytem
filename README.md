# Student Registration System

**Student Registration System** is a software application built to manage student records, course details, and teacher information. It provides an interface for administrators to add, modify, and view student data, courses, and teachers in an educational institution.

## Features

- **Admin Interface**: The system provides an administrative interface for managing students, teachers, and courses.
- **Course Management**: Admins can add, update, and remove courses.
- **Teacher Management**: Admins can manage teacher data and assign them to courses.
- **Student Registration**: Students can be registered into the system with their personal information.
- **Database Integration**: The system integrates with a MySQL database to store all records.

## Technologies Used

- **Java**: Used for building the backend and user interface.
- **FXML**: For designing the user interface in a declarative way.
- **MySQL**: Used for storing student, teacher, and course data.
- **TrayNotification**: For notifications within the application.
- **JavaFX**: For building the graphical user interface (GUI).

## Installation

### Prerequisites

- Java Development Kit (JDK) version 8 or higher.
- MySQL database server installed.

### Steps

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. **Setup the Database**:

   - Create a MySQL database and import the provided SQL file (`uiuStudentRecordSystem.sql`).
   - Set up the MySQL connection credentials in the application.

3. **Run the Application**:

   - Compile and run the Java application through your preferred IDE (e.g., IntelliJ IDEA, Eclipse).
   - Ensure that the TrayNotification library is included in the project dependencies.

4. **Login Credentials**:

   - You can find default login credentials in the `login credentials.txt` file.

5. **Customize**:

   - Update the `Admin.java`, `AdminCourse.java`, and other files with specific details about your institution or project.

## Usage

- **Admin Panel**: Log in with administrator credentials to manage student, course, and teacher data.
- **Course Management**: Admin can view all courses and manage them.
- **Teacher Management**: Admin can manage teacher assignments to specific courses.
- **Student Registration**: Admin can add new students and assign them to courses.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to all contributors and those who helped shape the project.
