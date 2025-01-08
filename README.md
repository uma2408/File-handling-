**Name:** UMA MAHESHWAR REDDY YATHAM

**Company:** CODTECH IT SOLUTIONS

**ID:** CT08EMS

**Domain:** Java programming

**Duration:** 17 DEC TO 17 JAN 2025

**Mentor:** N.SANTHOSH

**Overview of the Code:**

The program demonstrates basic file handling in Java, specifically how to write, read, and modify a text file. Here's a breakdown of the functionality:

**Key Functions and Their Purpose:**

writeToFile(String fileName, String content):

Purpose: Writes a string (content) to a file specified by fileName.

**How:**

Uses a BufferedWriter wrapped around a FileWriter to write the content.
Overwrites the file if it already exists.
readFile(String fileName):

Purpose: Reads the content of a file line by line and displays it on the console.

**How:**

Uses a BufferedReader wrapped around a FileReader.
Reads and prints each line until the end of the file.
modifyFile(String fileName, String oldText, String newText):

Purpose: Modifies specific lines in the file by replacing occurrences of oldText with newText.

**How:**

Reads all lines from the file into a List<String> using Files.readAllLines.
Iterates through the list, replacing lines containing oldText.
Writes the modified content back to the file using Files.write.
Flow of Execution

**Write to File:**

**Creates a new file named sample.txt and writes:**

scss
Copy code
This is a sample text file.
Line 2 of the file.
Read the File:

Reads and prints the current content of sample.txt:
scss
Copy code
This is a sample text file.
Line 2 of the file.
Modify the File:

Replaces the line "Line 2 of the file." with "This is the modified second line.".
Writes the modified content back to sample.txt.

**Read Modified Content:**

Reads and prints the updated content of sample.txt:
vbnet
Copy code
This is a sample text file.
This is the modified second line.
Core Java Concepts Demonstrated

**File I/O:**

BufferedWriter and BufferedReader for efficient reading and writing.
Files utility class from java.nio.file for working with file paths and content.

**Error Handling:**

Try-with-resources ensures that resources like BufferedWriter and BufferedReader are closed automatically.
IOException is caught to handle potential file operation errors gracefully.

**String Manipulation:** Uses String.contains and String.replace to locate and replace specific text.

**Collections:** Uses a List<String> to store and manipulate file content.

**Applications of the Code:**

File management tasks, such as creating logs, configuration files, or reports.
Text file processing, e.g., replacing placeholders in template files.
Learning foundational file handling techniques in Java.

![Screenshot (75)](https://github.com/user-attachments/assets/d670b768-1e80-4c9c-90cc-f1d0b97ac634)
