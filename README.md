# Email-extractor-Task3-ALphacode
Extracts emails from designated folder
# Email Extractor — CodeAlpha Internship Task 3

This project was created for Task 3 of the CodeAlpha Python Internship program
It automates the process of extracting all email addresses from a `.txt` file and saves them to a new file

# Goal

Automate a small, real-life repetitive task using Python

Chosen Task:  
✔ Extract all email addresses from a `.txt` file and save them to another file


# Key Concepts Used

- `re` – Regular Expressions (for finding email patterns)
- `file handling` – Reading input and writing output
- `set()` – To remove duplicate emails

# How It Works

1. Asks the user to enter the name of a `.txt` file.
2. Uses a `regular expression` to search for valid email addresses
3. Removes duplicates
4. Saves the cleaned list of emails to `emails_found.txt`
5. Handles missing files with a message instead of crashing


# Example Input for filename

*"contacts.txt"*

## NOTE
For it to run you must place the `.txt` file in the same folder as this python script
