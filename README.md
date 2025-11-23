Attendance Tool – Project Documentation

Identify a Real-World Problem or Need:
Manual attendance systems in schools, colleges, and small organizations are time-consuming, prone to human errors, difficult to update, and inefficient for long-term record maintenance. A digital attendance tool simplifies the process, enhances accuracy, and automates record keeping.
Define Clear Objectives and Expected Outcomes:
•	Develop a simple and efficient attendance tracking tool.
•	Allow users to quickly mark present/absent status.
•	Store attendance securely in an Excel file.
•	Ensure quick retrieval and modification of attendance data.
•	Apply software development concepts learned in the course.
Apply Concepts Learned in the Course
•	Use Python programming fundamentals.
•	Apply file handling and data manipulation concepts.
•	Use modular and structured programming.
•	Utilize external libraries like pandas and openpyxl.
•	Implement algorithms and flow-based problem-solving.
Use Appropriate Tools, Libraries, or Programming Techniques:
•	Programming Language: Python
•	Libraries: pandas, openpyxl, datetime
•	Tools: Excel for storing and viewing attendance
•	Concepts: modularization, functions, error handling
Problem Definition:
Design a Python-based tool to automate attendance marking and storage, reducing manual workload and errors while improving data accuracy and accessibility.
Requirement Analysis:
Functional Requirements:
•	System should load student data from an Excel sheet.
•	User must be able to input date and present students.
•	System must update attendance rows automatically.
•	Non-Functional Requirements:
•	Should be easy to use.
•	Must be reliable and error-free.
•	Data must be stored safely.
Top-Down Design / Modularization:
Main Modules:
•	load_attendance(): Load Excel file.
•	mark_attendance(): Mark present students for selected date.
•	save_attendance(): Save updated attendance.
•	main(): Overall workflow.
Algorithm Development:
1.	Start
2.	Load Excel file containing student list.
3.	Ask user for date.
4.	Ask user to enter IDs of present students.
5.	Add new date column if needed.
6.	Mark students as 'P' or 'A'.
7.	Save updated Excel file.
8.	End
Implementation:
The tool is implemented in Python using pandas and openpyxl. Functions are used to separate tasks such as loading files, marking attendance, and saving results.
Testing and Refinement:
•	Tested with various sample student lists.
•	Ensured accuracy of Excel updates.
•	Handled missing IDs and incorrect input.
•	Refined program for smoother user experience.
