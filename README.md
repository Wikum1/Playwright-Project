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

## ▶️ How to Run the Project

Navigate to the project folder and run:


python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open


---

## Test Approach

50 negative test cases
Covers all 24 Singlish input types
Focuses on incorrect transliteration scenarios

---

##  Known Issue

Due to CORS restrictions, the application sometimes returns:
"Failed to fetch" instead of actual output.

---

## Files Included

test_automation.py
Assignment 1 - Test cases.xlsx
README.md
GitHub link
