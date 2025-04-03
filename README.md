# SAMUEL EMMANUEL KIMARO
## WEEK_FOUR_PLP_PYTHON

## Description
This Python program reads a file, modifies its content by converting it to uppercase, and writes the modified content to a new file. It also includes error handling for missing or unreadable files.

## Features
Reads a user-specified file.
Converts the content to uppercase.
Saves the modified content to a new file.
Handles errors if the file does not exist or cannot be read.

## Structure:
Function for content modification
User input for filename
File handling (reading & writing)
Exception handling for errors

## Usage
Run the script.
Enter the filename of the file you want to read.
If the file exists, its content will be converted to uppercase and saved as modified_<filename>.
If the file does not exist or cannot be read, an error message will be displayed.

## Error Handling
- **File Not Found** → Displays: `"Error: The file does not exist."`

- **Read/Write Issue** → Displays: `"Error: The file cannot be read or written."`

## Implementation
The script modifies content using:
```python
def modify_content(content):
    return content.upper()
