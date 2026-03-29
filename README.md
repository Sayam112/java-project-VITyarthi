Name: SAYAM KASHYAP
Registration number: 24BAI10591

Project: CAMPUS COURSE AND RECORDS MANAGER (CCRM)

Overview:

Campus Course & Records Manager (CCRM) is a Java SE console application that helps institutes manage:

1.Students (create, update, deactivate, enrollments, transcripts)

2.Courses (create, update, assign instructors, search/filter with streams)

3.Enrollment & Grades (record marks, compute GPA, generate transcript)

4.File I/O (import/export CSV, backups with timestamped folders, recursive utilities)

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
1.Open Eclipse → File → New → Java Project.

2.Import existing source (src/edu/ccrm).

3.Set run configuration: Main class = edu.ccrm.cli.CCRMApp.

4.Run project → see menu-driven interface.

Project Structure: 

1.edu.ccrm
. ├─ cli/            # Menu-driven console UI

. ├─ domain/         # Person, Student, Instructor, Course, Enrollment, Enums

. ├─ service/        # StudentService, CourseService, EnrollmentService

. ├─ io/             # Import/Export (CSV), Backup utilities

. ├─ util/           # Validators, RecursionUtil, ConsoleUtil

. └─ config/         # AppConfig (Singleton)


Features Demonstrated: 

1.Encapsulation → Student (private fields + getters/setters).

2.Inheritance & Abstraction → Person → Student/Instructor.

3.Polymorphism → toString() overrides, service interfaces.

4.Immutability → CourseCode.

5.Static Nested Class → Course.Builder.

6.Inner/Anonymous Classes → ConsoleUtil.bannerPrinter().

7.Interfaces → StudentService, CourseService.

8.Enums → Semester, Grade (with points).

9.Design Patterns → Singleton (AppConfig), Builder (Course).

10.Exceptions → Custom (DuplicateEnrollmentException, MaxCreditLimitExceededException).

11.Streams & Lambdas → Course search/filter, GPA reports.

12.Recursion → RecursionUtil.totalSize().

13.NIO.2 → Import/Export CSV, backup folders.

14.Date/Time API → Enrollment dates, backup timestamps.


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

1.Oracle Java Documentation

2.Java SE Tutorials (docs.oracle.com)

3.StackOverflow discussions


   
  
