# test_automation
# Playwright Automation Project

## Requirements
- Python 3.11 or higher

## Install Dependencies
pip install playwright openpyxl
python -m playwright install

## Run the Script
python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
