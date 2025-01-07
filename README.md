# Employee Management System (EMS)

The **Employee Management System (EMS)** is a simple Java-based console application designed to manage employee records. It allows you to add, view, update, and delete employee details while practicing object-oriented programming principles like encapsulation and modularity.

---

## Features

- **Add Employee**: Add new employee details, which are stored as individual files.
- **View Employee**: Retrieve employee details by ID.
- **Update Employee**: Modify existing employee details.
- **Remove Employee**: Delete an employee's record by ID.
- **Exit Portal**: Safely exit the application.

---

## Technologies Used

- **Programming Language**: Java
- **File Handling**: To save and retrieve employee data as text files.
- **Object-Oriented Programming (OOP)**: Used for modularity and scalability.

---

## Classes and Responsibilities

1. **MainMenu**: Displays the EMS menu and handles user navigation.
2. **Employee_Add**: Allows the user to add new employee details and save them in a file.
3. **EmployDetail**: Handles employee input details like name, ID, contact, and more.
4. **Employee_Show**: Retrieves and displays an employee's details from the file.
5. **Employee_Remove**: Deletes an employee's file from the system.
6. **Employee_Update**: Updates existing employee details in the file.
7. **CodeExit**: Exits the application with a farewell message.
8. **EmployManagementSystem**: The main class, which ties all functionalities together and manages user inputs.

---

## How to Run

1. Clone the repository to your local system:
   ```bash
   git clone https://github.com/yourusername/Employee-Management-System.git

2. Open the project in your favorite Java IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code).
3. Compile and run the EmployManagementSystem.java file.
4. Follow the menu options to interact with the application.

File Storage
Employee data is stored in text files in the format:
file<EmployeeID>.txt

Example:
text
Copy code
Employee ID:123
Employee Name     : John Doe
Father's Name     : Mark Doe
Employee Contact  : 9876543210
Email Information : john.doe@example.com
Employee position : Software Engineer
Employee Salary   : 60000
Screenshots
Main Menu

Add Employee

View Employee

Future Enhancements
Integration with a database for more secure and scalable data storage.
GUI-based application for a better user experience.
Role-based access control for administrative and user-level operations.
