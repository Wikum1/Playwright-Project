# IT23650220 - ITPM Assignment 1

## Project Title

Frontend Test Automation using Playwright

---

## Student Details

Name: Your Name
Student ID: IT23650220

---

## Project Description

This project tests the accuracy of Singlish to Sinhala transliteration using automated frontend testing with Playwright.

---

## Installation (One-Time Setup)

Run the following commands in Command Prompt:


pip install -U pip
pip install playwright openpyxl
playwright install


---

## How to Run the Project

Navigate to the project folder and run:


python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open


---

## Test Approach

50 negative test cases
Covers all 24 Singlish input types
Focuses on incorrect transliteration scenarios

---

## Known Issue - CORS Error

During automation testing, the target web application did not return the Sinhala transliteration output.

The browser console showed a CORS/API fetch error, and the Excel file recorded the actual output as:

Failed to fetch

This happened because the frontend could not access the backend translation API due to a CORS policy restriction. Therefore, the automation correctly captured the system failure in the Actual Output column.

All test cases are marked as FAIL because the expected Sinhala transliteration output was not returned by the application.

---

## Files Included

test_automation.py
Assignment 1 - Test cases.xlsx
README.md
GitHub link
