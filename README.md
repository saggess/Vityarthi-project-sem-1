# Attendance Tool – Project Documentation

## 1. Identify a Real-World Problem or Need
Manual attendance systems used in schools, colleges, and small organizations are:

- Time-consuming  
- Prone to human error  
- Difficult to update  
- Inefficient for long-term usage  

A **digital attendance tool** solves these issues by improving accuracy, simplifying updates, and automating record-keeping.

## 2. Define Clear Objectives and Expected Outcomes

### Objectives
- Develop a simple and efficient attendance tracking tool.  
- Allow users to quickly mark Present/Absent.  
- Store attendance securely in an Excel sheet.  
- Enable easy modification and retrieval of attendance data.  
- Apply concepts learned in course modules.

### Expected Outcomes
- A working Python attendance application.  
- Accurate daily attendance stored in Excel.  
- Modular, error-free code design.  
- Improved user experience and reliability.

## 3. Apply Concepts Learned in the Course
This project uses:

- **Python programming fundamentals**  
- **File handling & data manipulation**  
- **Modular programming** using functions  
- **External libraries**: `pandas`, `openpyxl`  
- **Algorithmic & logical problem-solving`

## 4. Use of Appropriate Tools, Libraries, and Techniques

### Programming Language
- Python

### Libraries
- `pandas`  
- `openpyxl`  
- `datetime`

### Tools
- Excel (to store and view attendance)

### Techniques
- Modularization  
- Functions  
- Error handling  
- Data processing

## 5. Problem Definition
Develop a Python-based tool that:

- Automates attendance marking  
- Reduces manual workload  
- Eliminates human errors  
- Ensures safe and structured data storage  
- Improves accessibility and ease of use  

## 6. Requirement Analysis

### Functional Requirements
- Load student data from an Excel sheet  
- Accept date input  
- Allow user to mark present students  
- Automatically update attendance rows  

### Non-Functional Requirements
- Easy to use  
- Error-free and reliable  
- Secure data storage  

## 7. Top-Down Design / Modularization

### Main Modules
1. **load_attendance()** – Loads the Excel file  
2. **mark_attendance()** – Accepts date & IDs, marks attendance  
3. **save_attendance()** – Saves updated Excel file  
4. **main()** – Controls workflow and user interaction  

## 8. Algorithm Development
```
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
```

## 9. Implementation
- Python code written using `pandas` and `openpyxl`.  
- Functions used to separate tasks:
  - Loading the file  
  - Marking attendance  
  - Saving updates  
- Ensures readability and maintainability.

## 10. Testing and Refinement
- Tested using demo student lists  
- Verified Excel updates for multiple dates  
- Handled incorrect IDs and missing input  
- Improved user experience through refinements
