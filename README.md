# Student Management System (Core Java)

A console-based Student Management System built in Core Java. It demonstrates Object-Oriented Programming, the Collections Framework, custom exceptions, and file persistence, so student data is saved and reloaded between runs.

## Features

- Add a new student (ID, name, age, course, marks)
- View all students
- Search for a student by ID
- Update student details
- Delete a student
- Data is saved to a file and loaded automatically when the program starts
- Input validation with custom exceptions (for example: duplicate ID, student not found, invalid marks)

## Tech Stack

| Area | Technology |
| --- | --- |
| Language | Java 17 (Core Java) |
| Concepts | OOP (encapsulation, inheritance, abstraction), Collections Framework (`ArrayList` / `HashMap`), custom exceptions, File I/O |
| Storage | Local file (text / serialized) |
| Interface | Console (command line) |

## Project Structure

```
student-management-system-java/
├── src/
│   ├── Student.java              # Student model class
│   ├── StudentService.java       # Business logic (add, search, update, delete)
│   ├── StudentNotFoundException.java  # Custom exception
│   ├── FileHandler.java          # Saves and loads data from file
│   └── Main.java                 # Menu-driven entry point
├── students.dat                  # Data file (created on first run)
├── .gitignore
└── README.md
```

> Update the file names above so they match your actual project.

## How to Run

**Prerequisites:** Java JDK 17 or higher installed. Check with `java -version`.

1. Clone the repository:
   ```
   git clone https://github.com/Himabindu08888/student-management-system-java.git
   cd student-management-system-java
   ```
2. Compile the code:
   ```
   javac -d out src/*.java
   ```
3. Run the program:
   ```
   java -cp out Main
   ```

You can also open the folder in IntelliJ IDEA, Eclipse or VS Code and run `Main.java`.

## Sample Output

```
===== Student Management System =====
1. Add Student
2. View All Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit
Enter your choice:
```

> Replace this with a screenshot of your own program running: save the image in a `screenshots/` folder and add `![Menu](screenshots/menu.png)` here.

## What I Learned

- Designing classes with OOP principles
- Storing and managing data with Java collections
- Writing and throwing custom exceptions for error handling
- Reading and writing files so data persists between runs

## Future Improvements

- Connect to a database using JDBC and PostgreSQL
- Add unit tests with JUnit
- Build a web version with Spring Boot

## Author

**Himabindu Garinti**
[GitHub](https://github.com/Himabindu08888) | [LinkedIn](https://www.linkedin.com/in/himabindu-garinti-7b3905378)
