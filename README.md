# Assignment 1 – Transliteration Accuracy Testing

## Student ID:

IT23650220

## Description:

This project tests the accuracy of the Sinhala chat transliteration system using 50 negative test cases.

## Requirements:

* Python 3.11+
* Playwright
* Openpyxl

## Setup:

pip install playwright openpyxl
python -m playwright install

## Run:

python test_automation.py --excel "IT23650220_Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"

## Notes:

All test cases are negative scenarios where the system fails to correctly translate Singlish to Sinhala.
