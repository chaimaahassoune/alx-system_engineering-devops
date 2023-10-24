# API Python Scripting Project

## Introduction

This project focuses on utilizing Python scripting to interact with an API and perform various tasks related to employee data. It aims to familiarize you with API usage, Python scripting, and data export in different formats (CSV and JSON).
## Learning Objectives

By completing this project, you will gain knowledge in the following areas:

- Understanding when Bash scripting is not suitable
- Working with APIs, particularly REST APIs
- Familiarity with microservices
- Handling data in CSV and JSON formats
- Adhering to Pythonic naming conventions

## Tasks

1. **Gather data from an API**
   - Description: This script retrieves information about an employee's TODO list progress from the provided REST API.
   - Usage: `python3 0-gather_data_from_an_API.py <employee_id>`

2. **Export to CSV**
   - Description: This script extends Task 1 to export data in CSV format.
   - Usage: `python3 1-export_to_CSV.py <employee_id>`

3. **Export to JSON**
   - Description: This script extends Task 1 to export data in JSON format.
   - Usage: `python3 2-export_to_JSON.py <employee_id>`

4. **Dictionary of list of dictionaries**
   - Description: This script exports data for all employees in a JSON format.
   - Usage: `python3 3-dictionary_of_list_of_dictionaries.py`

## Directory Structure

- `0x15-api/`
  - `0-gather_data_from_an_API.py`
  - `1-export_to_CSV.py`
  - `2-export_to_JSON.py`
  - `3-dictionary_of_list_of_dictionaries.py`
  - `README.md`

## Requirements

- Allowed Editors: vi, vim, emacs
- Interpreted/Compiled on: Ubuntu 20.04 LTS with Python 3.8.5
- Libraries: urllib or requests (organized alphabetically)
- Code Style: PEP8 (use pycodestyle 2.8.*)
- File Execution: All files must be executable
- Module Documentation: `python3 -c 'print(__import__("my_module").__doc__)'`
- No Execution on Import: `if __name__ == "__main__":`
- Plagiarism: Strictly Forbidden

## License

This project is licensed under the [MIT License](LICENSE).
