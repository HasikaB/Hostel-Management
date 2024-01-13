# Hostel-Management

The Hostel Management System is a console-based application developed in C programming language. It serves as a tool for managing student data within a hostel, offering features that include adding new student entries, updating information, viewing student details, and more.

FEATURES:
New Entry: This feature allows users to add new students to the system. Users are required to input various details, including roll number, name, date of birth, age, city, phone number, email, father's name, father's phone number, room number, and hostel name.

Update Information: Users can modify the information of existing students. The system supports changes to room numbers and phone numbers.

View Details: Users can view the details of a specific student by searching either by roll number or name.

View All Students in a Hostel: This feature displays a list of all students in a particular hostel.

Remove Student Entry: Users can delete a student's record from the system using their roll number.

View All Students List: This feature enables users to view a list of all students currently stored in the system.

Exit: This option allows users to close the application.

HOW TO USE:
Run the program.
Enter the provided username and password to access the system.
Navigate through the menu using numeric options.
Follow the prompts to perform various operations.

FILE STRUCTURE:
main.c: This file contains the main program logic.
record.dat: Data file storing student records.
H-1.dat, H-2.dat, H-3.dat, H-4.dat: Files storing hostel-wise student lists.
README.md: Documentation file.

EXPLANATION:

HEADER FILES:
stdio.h, stdlib.h, string.h: Standard C libraries for input/output, memory allocation, and string operations.

GLOBAL VARIABLES:
i, j, main_exit: Global integer variables.

FUNCTION DECLERATIONS:

void menu(): Displays the main menu and redirects to various functions based on user input.
void new_entry(): Adds a new student's data.
void edit(): Updates information for an existing student.
void view_list(): Displays a list of all students.
void erase(): Removes an existing student's data.
void see(): Displays details of a specific student.
void sorter(): Displays a list of students in a particular hostel.
void closer(): Displays credits and exits the program.

STRUCTURES:
struct date: Represents a date with month, day, and year.
An unnamed structure is used to store student data, including roll number, name, date of birth, age, city, phone number, email, father's name, father's phone number, room number, and hostel name.

MAIN FUNCTION (main()):
Calls the pass() function for authentication.
Calls the menu() function to display the main menu.

menu() Function:
Displays the main menu with options for various operations.
Calls corresponding functions based on user input.

OTHER FUNCTIONS:
new_entry(): Adds a new student's data to the system, storing in both a general record file (record.dat) and a specific hostel file.
edit(): Allows editing student information such as room number or phone number.
view_list(): Displays a list of all students.
erase(): Removes a student's data from the system.
see(): Displays details of a specific student based on roll number or name.
sorter(): Displays a list of students in a particular hostel.
closer(): Displays developer credits and exits the program.
pass() Function:
Provides a simple login authentication mechanism before allowing access to the main program. The username is "user" and the password is "pass".
























