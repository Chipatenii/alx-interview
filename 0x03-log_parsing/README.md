

```markdown
# Log Parsing

This project involves parsing log files to extract, process, and compute metrics from log data streams. It covers several fundamental concepts in Python, including file I/O, signal handling, data processing, regular expressions, dictionaries, and exception handling.

## Concepts Covered

### 1. File I/O in Python
- **Objective:** Understand how to read data from `sys.stdin` line by line.
- **Key Resources:**
  - [Python Input and Output](https://docs.python.org/3/tutorial/inputoutput.html)
  
### 2. Signal Handling in Python
- **Objective:** Learn how to handle keyboard interruptions (CTRL + C) using signal handling.
- **Key Resources:**
  - [Python Signal Handling](https://docs.python.org/3/library/signal.html)

### 3. Data Processing
- **Objective:** Parse strings to extract specific data points and aggregate data to compute summaries.
- **Key Tasks:**
  - Extracting key information from each log entry.
  - Aggregating data to compute metrics like the frequency of status codes and total file sizes.

### 4. Regular Expressions
- **Objective:** Use regular expressions to validate the format of each line in the log file.
- **Key Resources:**
  - [Python Regular Expressions](https://docs.python.org/3/library/re.html)

### 5. Dictionaries in Python
- **Objective:** Utilize dictionaries to count occurrences of status codes and accumulate file sizes.
- **Key Resources:**
  - [Python Dictionaries](https://docs.python.org/3/tutorial/datastructures.html#dictionaries)

### 6. Exception Handling
- **Objective:** Handle exceptions that may arise during file reading and data processing.
- **Key Resources:**
  - [Python Exceptions](https://docs.python.org/3/tutorial/errors.html)

## Project Overview

### Log Parsing Functionality
- **Input:** Log entries via `sys.stdin`.
- **Output:** Computed metrics, including the frequency of status codes and total file sizes, output every 10 lines or upon keyboard interruption.

### Example Log Entry
```
127.0.0.1 - [2024-08-15] "GET /projects/260 HTTP/1.1" 200 1024
```
- **Data Points:**
  - IP Address
  - Timestamp
  - HTTP Method
  - URL Path
  - Status Code
  - File Size

### Expected Output
- Total File Size
- Count of Each Status Code (e.g., 200, 301, 404, etc.)

## Usage

To run the log parser, you can pipe a log file to the script or directly provide log data through `sys.stdin`:

```bash
cat log_file | ./log_parser.py
```

### Handling Keyboard Interruptions
The program gracefully handles keyboard interruptions (CTRL + C), ensuring that the current metrics are displayed before exiting.

## Conclusion

By mastering the concepts outlined in this README, you will be well-equipped to implement and extend the log parsing functionality in Python.
```

This `README.md` file provides an overview of the key concepts and instructions necessary for your log parsing project. Let me know if you need any modifications or additional information!
