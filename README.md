# UniversityTimetableManager
 University Timetable Manager — A C++ project implementing a Timetable Abstract Data Type (TTADT).   Load timetable data from CSV, search course schedules, find free classrooms, and display structured timetables using linked lists.

# TimetableADT

A simple yet powerful Timetable management system implemented in C++ using linked lists. This project allows you to load timetable data from a CSV file and perform various operations such as displaying the timetable, querying course information, finding free classrooms for a given timeslot, and printing timetables for specific sections.

---

## Features

- Load timetable data from a CSV file (`timetable.csv`).
- Store timetable entries organized by days, classrooms, and timeslots using linked list data structures (`DayNode` and `ClassNode`).
- Display the entire timetable grouped by day and classroom.
- Query detailed information for a specific course across all days and classrooms.
- Find free classrooms at a specified day and timeslot.
- Print the timetable for a particular section.
- Graceful cleanup of all dynamically allocated memory.

---

## CSV Format

The timetable CSV file should have the following columns (with header):

Day,Classroom,Time,Course,Section

---

## Menu Options

After running the program, you will see the following menu to interact with the timetable:

1. **Load Timetable from File**  
   Loads the timetable data from `timetable.csv`.

2. **Display Timetable**  
   Displays the entire timetable organized by day and classroom.

3. **Course Information**  
   Enter a course name to display all scheduled classes for that course.

4. **Finding Free Slot**  
   Enter a day and timeslot to find any free classrooms available.

5. **Print Timetable of Section**  
   Enter a section name to see the complete timetable for that section.

6. **Exit**  
   Exit the application.

---

## Example Interaction

======= Timetable Menu =======

Load Timetable from File

Display Timetable

Course Information

Finding Free slot

Print Timetable of Section

Exit
Enter your choice: 1
Timetable Loaded Successfully!

Enter your choice: 2
Day: Monday
Classroom: 0
Time: 08:30 AM -10:00 AM , Course: Math101, Section: A1
Time: 10:00 AM  -11:00 AM, Course: CS102, Section: A2

===========================================================================================

---

## Code Structure

- **ClassNode**: Represents a single class entry (time, course, classroom, section).
- **DayNode**: Represents a day in the timetable, linked to a list of ClassNodes.
- **TTADT**: Timetable Abstract Data Type class managing the linked list structure and providing methods for insertion, searching, displaying, etc.

---

## Author

Developed by Anosha Aamer 
Feel free to contribute!

---

## Acknowledgments

- Inspired by linked list data structures and basic file I/O in C++.
- Designed as a beginner-friendly project for learning data organization and retrieval.
