# Product Explorer & Error-Resilient Logger (Part 3)

## Objective
In this assignment, I worked on file handling, APIs, and exception handling in Python.  
The goal was to understand how real-world applications deal with data, external APIs, and unexpected errors without crashing.

---

## What I Did

### Task 1: File Handling (Read & Write)
- Created a file `python_notes.txt` and wrote some basic Python concepts into it  
- Appended a few extra lines to the same file  
- Read the file and printed each line with numbering  
- Counted total number of lines  
- Added a small search feature where the user can enter a keyword and find matching lines  

---

### Task 2: API Integration
I used the DummyJSON API to work with real product data.

- Fetched product data using GET request and displayed it in a table format  
- Filtered products with high ratings and sorted them by price  
- Retrieved products from a specific category (laptops)  
- Made a POST request to simulate adding a new product  
- Printed API responses to understand how data is returned  

---

### Task 3: Exception Handling

#### Safe Calculator
- Created a function to safely divide two numbers  
- Handled division by zero and invalid input types  

#### Safe File Reader
- Built a function to read files safely  
- Handled cases where the file does not exist  
- Used `finally` to confirm the operation attempt  

#### API Error Handling
- Wrapped API calls in try-except blocks  
- Handled connection issues and timeouts  
- Added a general exception handler for unexpected errors  

#### Input Validation
- Created a loop to take product ID input from the user  
- Ensured only valid inputs are accepted  
- Handled cases where the product does not exist  

---

### Task 4: Error Logging
- Built a simple logger that writes errors to `error_log.txt`  
- Added timestamps to each log entry  
- Logged both connection errors and HTTP errors  
- Read and displayed the log file at the end  

---

## How to Run
- Make sure `requests` library is installed  

##**pip install requests**
- Run the Python file or notebook  
- Follow the prompts where input is required  

---

## Concepts Used
- File handling (`read`, `write`, `append`)  
- APIs using `requests`  
- Exception handling (`try-except-finally`)  
- Input validation  
- Logging using `datetime`  

---

## Files
- `part3_product_explorer.ipynb`  
- `python_notes.txt`  
- `error_log.txt`  

---

## Author
Bhoomi Solanki
