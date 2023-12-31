
 STUDENT DATABASE MANAGEMENT  SYSTEM


1. Introduction
 The Student Database Management System (DBMS) is a Python application developed using the Tkinter library and SQLite database. The primary goal of the project is to provide a user-friendly interface for managing student records, allowing users to perform operations such as adding, viewing, updating, and deleting student information.

2. Features 
2.1 User Interface
2.1.1 Input Fields for Student Details 
The graphical user interface (GUI) of the Student Database Management System (DBMS) includes well-organized input fields to capture comprehensive student details. Each field corresponds to a specific attribute such as Student ID, Firstname, Surname, Date of Birth (DoB), Age, Gender, Address, and Mobile.  
Student ID: Allows entry of a unique identifier for each student.  
Firstname and Surname: Capture the first and last names of the student.  
Date of Birth (DoB): Records the date of birth of the student.
  Age: Automatically calculates and displays the age based on the entered date of birth.  
Gender: Specifies the gender of the student. 
 Address: Captures the residential address of the student.
  Mobile: Records the contact number of the student. 


 2.1.2 Buttons for Various Operations 
The GUI is equipped with a set of buttons to perform different operations on the student records.  
Add New: Adds a new student record to the database based on the entered details. 
 Display: Retrieves and displays all existing student records.
  Clear: Clears all input fields, allowing for the easy entry of new information. 
 Delete: Removes a selected student record from the database.  
Search: Enables users to search for specific student records based on various criteria.  
Update: Modifies the information of an existing student record. 
 Exit: Closes the application.  



2.1.3 Listbox for Displaying Records
 A listbox is integrated into the GUI to present the existing student records in a clear and organized manner. This listbox dynamically updates as the user performs operations such as adding, deleting, or updating records. 
 2.2 Database Operations 
2.2.1 Initializing the Database 
On application startup, the system checks for the existence of the student table in the SQLite database. If the table does not exist, it is created to store the student records.  
2.2.2 Adding New Records 
The application allows the addition of new student records to the database. The information entered through the GUI is inserted into the student table, and the listbox is updated to reflect the changes.  
2.2.3 Viewing Existing Records 
Users can retrieve and view all existing student records by clicking the "Display" button. The listbox displays the details of each student, providing a comprehensive overview.  
2.2.4 Deleting Records 
The system supports the deletion of specific student records based on the selected entry in the listbox. The "Delete" button triggers this operation, and the listbox is promptly updated. 
2.2.5 Searching for Records 
The application enables users to search for student records using various criteria, such as Student ID, Firstname, Surname, Date of Birth, Age, Gender, Address, or Mobile. The search results are displayed in the listbox.  
2.2.6 Updating Records 
Users can modify the information of an existing student record by selecting the record in the listbox, making the necessary changes in the input fields, and clicking the "Update" button.


3. Code Structure 
The code is organized into frontend and backend sections.
3.1 Frontend (Tkinter GUI) 
The GUI is created using Tkinter, with entry fields, buttons, and a listbox organized within frames. 
Functions are defined to handle various GUI operations, such as adding, displaying, updating, and deleting records.
3.2 Backend (SQLite Database Operations) 
The dbbackend.py module contains functions for initializing the database, adding records, viewing records, deleting records, searching for records, and updating records.



4. Conclusion
The Student Database Management System provides a basic yet functional platform for managing student records. The combination of Tkinter and SQLite allows for a simple and intuitive interface. As the project continues to evolve, additional features and improvements can be incorporated.
