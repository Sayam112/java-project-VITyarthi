Name: SAYAM KASHYAP
Registration number: 24BAI10591

Project: CAMPUS COURSE AND RECORDS MANAGER (CCRM)

Overview:

Campus Course & Records Manager (CCRM) is a Java SE console application that helps institutes manage:

-Students (create, update, deactivate, enrollments, transcripts)
-Courses (create, update, assign instructors, search/filter with streams)
-Enrollment & Grades (record marks, compute GPA, generate transcript)
-File I/O (import/export CSV, backups with timestamped folders, recursive utilities)

This project demonstrates Java OOP principles, advanced Java features, and design patterns in a real-world application.

How to Run:

1. Requirements-
         -JDK 11+ (tested with JDK 17)
         -IDE: Eclipse / IntelliJ IDEA
         - Git(for cloning repo)
2. Steps-
        - Import into Eclipse as an existing java project
        - Run main class
        - Follow menu driven workflow


Java on Windows:
1. Download JDK from Oracle.
2. Run installer and set environment variable-
   JAVA_HOME=C:\Program Files\Java\jdk-17
PATH=%JAVA_HOME%\bin
3. Verify installation-
   java -version

Eclipse Setup- 
Open Eclipse → File → New → Java Project.
Import existing source (src/edu/ccrm).
Set run configuration: Main class = edu.ccrm.cli.CCRMApp.
Run project → see menu-driven interface.

Project Structure: 

edu.ccrm
 ├─ cli/            # Menu-driven console UI
 ├─ domain/         # Person, Student, Instructor, Course, Enrollment, Enums
 ├─ service/        # StudentService, CourseService, EnrollmentService
 ├─ io/             # Import/Export (CSV), Backup utilities
 ├─ util/           # Validators, RecursionUtil, ConsoleUtil
 └─ config/         # AppConfig (Singleton)


Features Demonstrated: 

-Encapsulation → Student (private fields + getters/setters).
-Inheritance & Abstraction → Person → Student/Instructor.
-Polymorphism → toString() overrides, service interfaces.
-Immutability → CourseCode.
-Static Nested Class → Course.Builder.
-Inner/Anonymous Classes → ConsoleUtil.bannerPrinter().
-Interfaces → StudentService, CourseService.
-Enums → Semester, Grade (with points).
-Design Patterns → Singleton (AppConfig), Builder (Course).
-Exceptions → Custom (DuplicateEnrollmentException, MaxCreditLimitExceededException).
-Streams & Lambdas → Course search/filter, GPA reports.
-Recursion → RecursionUtil.totalSize().
-NIO.2 → Import/Export CSV, backup folders.
-Date/Time API → Enrollment dates, backup timestamps.


Usage Demo:

 ==== CCRM - Campus Course & Records Manager ====
1. Manage Students
2. Manage Courses
3. Enrollment & Grades
4. Import/Export
5. Backup & Size
6. Exit

Example:

Choose option: 1
Students: 1-Add 2-List 3-PrintProfile 4-Back
Choose: 1
RegNo: 23BCY10082
Full name: Somya Shekhar Tiwari
Email: somya@example.com
DOB (yyyy-mm-dd): 2004-05-18
Added: Student{id=..., regNo=23BCY10082, ...}

Acknowledgements:

-Oracle Java Documentation
-Java SE Tutorials (docs.oracle.com)
-StackOverflow discussions

   
  
