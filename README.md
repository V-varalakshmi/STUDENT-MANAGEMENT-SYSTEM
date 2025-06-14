# STUDENT-MANAGEMENT-SYSTEM

#DESCRIPTION

The project starts by importing essential Python libraries, including Tkinter for developing the graphical user interface (GUI), SQLite for handling the backend database, CSV for enabling data export functionality, and Datetime for managing date-related operations such as attendance logging. The database, named `students.db`, is either created or connected to if it already exists. Within this database, two tables are set up: the `students` table stores comprehensive student details such as name, roll number, email, course, gender, date of birth, attendance count, and grade, while the `attendance_log` table keeps a record of attendance events by storing the student ID along with the corresponding date.

To ensure security, the application opens with a login screen that requires a predefined username and password. Only after successful login does the main interface load, and any incorrect credentials result in an error message. The main application window provides a well-structured interface, including input fields, operational buttons, and a TreeView widget for displaying data in a tabular form. It allows administrators to add new students by entering details in the form fields. Upon clicking the “Add Student” button, the data is validated and then stored in the database, with the display updating to reflect the changes.

Student records are presented in the TreeView table, showing key details like student ID, name, roll number, attendance, and grade. Attendance is managed through a simple feature where selecting a student and clicking a button increases their attendance count by one and logs the current date into the `attendance_log` table. Grades can be updated by entering a new value and clicking the “Update Grade” button, which modifies the record in the database and instantly reflects the changes in the display. The system also supports the deletion of student records, ensuring data is removed from both the main student table and the attendance log to maintain database consistency.

Searching for students is simplified with a roll number-based search function, which filters the displayed results to show only the relevant record. Furthermore, the application includes an export feature that allows all student data to be saved as a CSV file in a user-specified location, aiding in data backup or external analysis using software like Excel. The interface is clean and intuitive, with clearly labeled entry fields, action buttons, and a TreeView widget that provides an organized and interactive way to manage and review student information.

#OUTPUT

![Image](https://github.com/user-attachments/assets/71d69480-100a-4a1e-96a5-7ba89234d5df)
![Image](https://github.com/user-attachments/assets/f2a95daf-f4ba-4833-86f3-b09487af29f8)
![Image](https://github.com/user-attachments/assets/52737615-9623-4d6b-8ba9-54671dab246e)
![Image](https://github.com/user-attachments/assets/eb9e333f-f0d8-48a7-829f-c79780cd835a)
![Image](https://github.com/user-attachments/assets/ac89598a-8ec9-4915-bdfd-4dcccc63944e)
![Image](https://github.com/user-attachments/assets/d4caa8af-5c2c-439f-aad1-fa5078f885d0)
![Image](https://github.com/user-attachments/assets/54e4ea25-8cb2-4bb5-a6f7-b80615440746)
