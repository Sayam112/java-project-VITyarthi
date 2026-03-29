##RUNNING MAIN PROGRAM


Run te main class:
```
java edu.ccrm.cli.CCRMApp
```

Menu will appear:
```
==== CCRM - Campus Course & Records Manager ====
1. Manage Students
2. Manage Courses
3. Enrollment & Grades
4. Import/Export
5. Backup & Size
6. Exit
```

##Student Management:
##Add student-
```
Choose option: 1
Students: 1-Add 2-List 3-PrintProfile 4-Back
Choose: 1
RegNo: 23BCY10082
Full name: Somya Shekhar Tiwari
Email: somya@example.com
DOB (yyyy-mm-dd): 2004-05-18
Added: Student{id=S1, regNo=23BCY10082, ...}
```

##List student-
```
Choose: 2
Student{id=S1, regNo=23BCY10082, ...}
```

##print student profile and transcript-
```
Choose: 3
Student id: S1
Profile: Student{id=S1, regNo=23BCY10082, ...}
Transcript:
Enrollment[studentId=S1, course=CS101, marks=95.0, grade=S]
GPA: 10.00
```

##Course Management:
##Add a course-
```
Choose option: 2
Courses: 1-Add 2-List 3-SearchByInstructor 4-Back
Choose: 1
Course code: CS101
Title: Introduction to Programming
Credits: 4
Department: CSE
Added: Course{code=CS101, title=Introduction to Programming, ...}
```

##list courses-
```
Choose: 2
Course{code=CS101, title=Introduction to Programming, credits=4, semester=FALL, dept=CSE}
```

##Enrollment and Grading:
##Enroll students-

```
Choose option: 3
Enrollment: 1-Enroll 2-Unenroll 3-RecordMarks 4-Back
Choose: 1
Student id: S1
Course code: CS101
Enrolled
```

##record marks-
```
Choose: 3
Student id: S1
Course code: CS101
Marks: 95
Recorded
```

##Import/Export:
##export students and courses-
```
Choose option: 4
Choice: 1
Exported to /home/user/ccrm-data/export
```

generated files-
```
ccrm-data/export/students.csv
ccrm-data/export/courses.csv
```

##import students and courses-
```
Choose option: 4
Choice: 2
Imported sample files (if present)
```

student.csv and courses.csv must use provided test-data.

##Backup and size:
##create backup-
```
Choose option: 5
Backup created at: /home/user/ccrm-data/backup_20250924_153000
Total backup size bytes: 1523
```

##exit-
```
Choose option: 6
Config: AppConfig[dataFolder=..., startedAt=..., maxCredits=24]
Exiting... goodbye
```

##Quick Demo Flow:
1. Import students.csv and courses.csv
2. List students and courses.
3. Enroll a student in a course.
4. Record marks and view transcript.
5. Export data.
6. Create a backup.
7. Exit program.


