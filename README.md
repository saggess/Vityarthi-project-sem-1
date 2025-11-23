**Attendance Tool – Project Documentation**
@*Identify a Real-World Problem or Need*

Manual attendance systems used in schools, colleges, and small organizations are:

1.Time-consuming

2.Prone to human error

3.Difficult to update

4.Inefficient for long-term usage

A digital attendance tool solves these issues by improving accuracy, simplifying updates, and automating record-keeping.

@*Define Clear Objectives and Expected Outcomes*
Objectives

1.Develop a simple and efficient attendance tracking tool.

2.Allow users to quickly mark Present/Absent.

3.Store attendance securely in an Excel sheet.

4.Enable easy modification and retrieval of attendance data.

5.Apply concepts learned in course modules.

Expected Outcomes

1.A working Python attendance application.

2.Accurate daily attendance stored in Excel.

3.Modular, error-free code design.

4.Improved user experience and reliability.

@*Apply Concepts Learned in the Course*

This project uses:

1.Python programming fundamentals

2.File handling & data manipulation

3.Modular programming using functions

4.External libraries: pandas, openpyxl

5.Algorithmic & logical problem-solving

*@Use of Appropriate Tools, Libraries, and Techniques*
Programming Language

1.Python

Libraries

1.pandas

2.openpyxl

3.datetime

Tools

1.Excel (to store and view attendance)

Techniques

1.Modularization

2.Functions

3.Error handling

4.Data processing

*@Problem Definition*

Develop a Python-based tool that:

1.Automates attendance marking

2.Reduces manual workload

3.Eliminates human errors

4.Ensures safe and structured data storage

5.Improves accessibility and ease of use

*@Requirement Analysis*
Functional Requirements

1.Load student data from an Excel sheet

2.Accept date input

3.Allow user to mark present students

4.Automatically update attendance rows

Non-Functional Requirements

1.Easy to use

2.Error-free and reliable

3.Secure data storage

*@Top-Down Design / Modularization*
Main Modules

1.load_attendance()
Loads the Excel file.

2.mark_attendance()
Accepts date & IDs, marks attendance.

3.save_attendance()
Saves updated Excel file.

4.main()
Controls workflow and user interaction.

*@Algorithm Development*
Start
|
|-- Load Excel file containing student list
|-- Ask user for date
|-- Ask user to enter IDs of present students
|-- Add new date column if needed
|-- Mark students as 'P' or 'A'
|-- Save updated Excel file
|
End

*@Implementation*

1.Python code written using pandas and openpyxl.

2.Functions used to separate tasks:

a.Loading the file

b.Marking attendance

c.Saving updates

3.Ensures readability and maintainability.

*@Testing and Refinement*

1.Tested using demo student lists

2.Verified Excel updates for multiple dates

3.Handled incorrect IDs and missing input

Improved user experience through refinements
