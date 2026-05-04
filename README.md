IT23779402 – IT3040 Assignment 1
Project Title
Automated Functional Testing for Singlish-to-Sinhala Transliteration System

Project Structure
The following files are included in this submission:

it23779402_test_automation.py: The core Playwright automation script used to interact with the web translator.

it23779402_Test cases.xlsx: Excel workbook containing 50 negative test cases, expected results, and automated status updates.

it23779402_requirements.txt: Python dependency file including playwright, openpyxl, and pandas.

it23779402_README.md: Project documentation and execution guide.

Technologies Used
Python: Primary programming language.

Playwright: Framework for end-to-end UI automation and testing.

OpenPyXL: Library for reading and writing Excel (.xlsx) files.

How to Run the Project
Prepare Environment:
Open your terminal in the project directory and install the required libraries:
pip install -r it23779402_requirements.txt
playwright install

Execute Automation:
Run the following command to start the testing process:
python it23779402_test_automation.py --excel "it23779402_Test cases.xlsx" --url "[https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator)"

Test Case Overview
Total Test Cases: 50.

Test Strategy: Negative testing focusing on edge cases such as mixed-language inputs, technical digital terms (API, Viber), complex punctuation, and long-form paragraphs.

Strict Validation: The script performs an exact string comparison between the translator's output and the expected result. Failures are expected in scenarios where the transliteration engine cannot interpret highly casual slang or technical English insertions.

Student Information
Student ID: IT23779402

Module: IT3040 - Software Quality Assurance

Assignment: Assignment 1 (Option 1)

Final Status
✔ Automation script verified and functional.
✔ Excel-based validation covering 50+ diverse scenarios completed.
✔ All project files structured according to SLIIT standards.
