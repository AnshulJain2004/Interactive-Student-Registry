# Interactive Student Registry

**Interactive Student Registry** is a simple Java-based console application that lets you manage student records. It demonstrates fundamental Object-Oriented Programming principles such as encapsulation, constructor chaining, and basic CRUD (Create, Read, Update, Delete) operations using an ArrayList to store student data.

## Project Structure

1. **Student.java**  
   - Represents a student entity with fields like PRN, Name, DOB, and Marks.  
   - Demonstrates constructor chaining by providing multiple constructors (with one, two, three, and four parameters).
   - Includes getters, setters, and an overridden `toString()` method for displaying student information.

2. **StudentFunctions.java**  
   - Contains the core functionality for managing students:  
     - **addStudent()**: Adds new student records by prompting user input.  
     - **printStudentDetails()**: Prints details of all students.  
     - **searchStu()**: Searches student(s) by PRN, Name, DOB, or Marks.  
     - **updateOrDelete()**: Allows the user to add a new student, edit an existing student, or delete a student record.  
     - **editStudent()**: Updates an existing student’s details based on PRN.  
     - **deleteStudent()**: Removes a student record based on PRN.

3. **StudentDemo.java**  
   - The main driver class with a simple menu-driven interface.  
   - Initializes the student list and repeatedly prompts the user for actions to perform until the user chooses to exit.

## Key Features

- **Add multiple student records** with PRN, Name, DOB, and Marks.  
- **Search student records** by different attributes (PRN, Name, DOB, Marks).  
- **Edit existing student data** such as name, date of birth, and marks.  
- **Delete student records** by specifying the student’s PRN.

## Getting Started

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/Interactive-Student-Registry.git
   ```
2. **Compile the Java Files**  
   Make sure you are in the correct directory, then compile:
   ```bash
   javac Student.java StudentFunctions.java StudentDemo.java
   ```
3. **Run the Application**  
   ```bash
   java StudentDemo
   ```
4. **Follow the On-Screen Menu**  
   - **1**: Display all students  
   - **2**: Search for a student  
   - **3**: Update / Edit / Delete student info  
   - **4**: Exit the application  

## Example Usage

After starting the program, you might see:

```
Enter Number of students: 2
Enter details for student 1 :
Enter prn:
101
Enter Name:
Alice
Enter DOB(dd/MM/yyyy):
01/01/2000
Enter marks:
85.5

Enter details for student 2 :
Enter prn:
102
Enter Name:
Bob
Enter DOB(dd/MM/yyyy):
05/06/1999
Enter marks:
90.0

Menu:
1. Display all students
2. Search Student
3. Update, Edit, or Delete Student info
4. Exit
```

You can choose the appropriate menu option to view, search, update, or delete students.

## Potential Enhancements

- **Persistent Storage**: Integrate with a database or save data to a file to retain records across sessions.  
- **Input Validation**: Add checks for valid PRN, name format, date parsing, etc.  
- **Better UI**: Build a graphical interface (GUI) for more user-friendly interactions.

---
