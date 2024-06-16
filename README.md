
# Employee Payroll System

## Overview
The program allows an administrator to manage employee records, calculate salaries, generate reports, and print salary slips. It includes functionalities for adding, deleting, editing, and searching for employees, as well as calculating net salaries considering EPF (Employee Provident Fund) and ETF (Employee Trust Fund) deductions.

## Key Components

### Main Function
- Initializes the program and handles the main menu navigation.
- Validates the user’s password before allowing access to the menu options.

### File Handling
- Employee data is stored in `empdata.txt`, and temporary data manipulation is done using `tmpdata.txt`.

### Password Protection
- Ensures that only authorized personnel can access the system.

### Employee Management
- Add, delete, edit, and search for employee records.

### Payroll Calculation
- Computes net salary by considering basic salary, working hours, overtime, EPF, and ETF contributions.

## Functions and Their Roles

### welcome_message()
- Displays the welcome message when the program starts.

### get_password()
- Prompts the user to enter a password. The correct password is `anjula`.

### main_menu()
- Displays the main menu options.

### manage_employee()
- Provides a sub-menu for managing employees (add, delete, edit, search).

### add_employee()
- Collects employee details and appends them to `empdata.txt`.

### delete_employee()
- Deletes an employee record based on the provided employee ID.

### edit_employee()
- Edits the salary and hours worked for a specified employee ID.

### search_employee()
- Searches for and displays an employee’s details based on the employee ID.

### print_report()
- Generates a report of all employees, displaying their salary details and deductions.

### print_slip()
- Prints the salary slip for a specified employee ID.

### emp_menu()
- Displays the employee management sub-menu.

### exit_message()
- Displays a thank you message when exiting the program.

## Example of Program Flow

### Start the Program
- Displays the welcome message.
- Prompts for a password.

### Main Menu Options
- **Manage Employees**: Provides options to add, delete, edit, and search for employees.
- **Print Report**: Displays the report of all employees.
- **Print Slip**: Prints the salary slip for a specific employee.
- **Exit**: Exits the program.

---

**Note:** The program uses a simple text file-based storage for employee records. Make sure the `empdata.txt` file is in the same directory as the program executable.



