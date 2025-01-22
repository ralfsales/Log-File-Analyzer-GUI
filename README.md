# Log File Analyzer GUI #

The Log File Analyzer GUI is a Python-based desktop application that allows users to analyze log files for insights such as log entry counts, filtering by keywords, and viewing detailed log content. The application is built using the Tkinter library for a user-friendly graphical interface.

Features
File Selection:
Easily select a log file using a built-in file dialog.
Log Summary:
Displays the total count of log entries.
Categorizes logs by severity levels: INFO, WARNING, and ERROR.
Keyword Filtering:
Allows users to filter logs based on specific keywords.
Displays all matching log entries in a scrollable output area.
Intuitive GUI:
Clean and user-friendly interface with buttons, labels, and a text area for results.
Technologies Used
Python: Core programming language.
Tkinter: For building the graphical user interface.
How to Use
Run the Program:
Execute the script:
bash

python LogFileAnalyzer.py
Select a Log File:
Use the "Select Log File" button to open a log file (e.g., example.log).
Analyze Logs:
Click "Analyze Logs" to view a summary of the log file, including the counts of INFO, WARNING, and ERROR entries.
Filter Logs:
Enter a keyword (e.g., ERROR) and click "Filter Logs" to see all matching log entries.
Example Log File
A sample log file, example_log.log, is included for testing. It contains entries such as:

yaml

[2025-01-22 12:00:00] INFO: Application started

[2025-01-22 12:01:00] WARNING: High memory usage

[2025-01-22 12:02:00] ERROR: Unable to connect to the database

