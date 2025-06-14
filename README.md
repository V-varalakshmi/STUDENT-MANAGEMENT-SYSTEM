# STUDENT-MANAGEMENT-SYSTEM

#DESCRIPTION

The project starts by importing essential Python libraries, including Tkinter for developing the graphical user interface (GUI), SQLite for handling the backend database, CSV for enabling data export functionality, and Datetime for managing date-related operations such as attendance logging. The database, named `students.db`, is either created or connected to if it already exists. Within this database, two tables are set up: the `students` table stores comprehensive student details such as name, roll number, email, course, gender, date of birth, attendance count, and grade, while the `attendance_log` table keeps a record of attendance events by storing the student ID along with the corresponding date.

To ensure security, the application opens with a login screen that requires a predefined username and password. Only after successful login does the main interface load, and any incorrect credentials result in an error message. The main application window provides a well-structured interface, including input fields, operational buttons, and a TreeView widget for displaying data in a tabular form. It allows administrators to add new students by entering details in the form fields. Upon clicking the “Add Student” button, the data is validated and then stored in the database, with the display updating to reflect the changes.

Student records are presented in the TreeView table, showing key details like student ID, name, roll number, attendance, and grade. Attendance is managed through a simple feature where selecting a student and clicking a button increases their attendance count by one and logs the current date into the `attendance_log` table. Grades can be updated by entering a new value and clicking the “Update Grade” button, which modifies the record in the database and instantly reflects the changes in the display. The system also supports the deletion of student records, ensuring data is removed from both the main student table and the attendance log to maintain database consistency.

Searching for students is simplified with a roll number-based search function, which filters the displayed results to show only the relevant record. Furthermore, the application includes an export feature that allows all student data to be saved as a CSV file in a user-specified location, aiding in data backup or external analysis using software like Excel. The interface is clean and intuitive, with clearly labeled entry fields, action buttons, and a TreeView widget that provides an organized and interactive way to manage and review student information.

#OUTPUT

