# CloudTrail Log Analyzer

This project analyzes AWS CloudTrail logs using Python.

## What is this project?
AWS CloudTrail records all activities in an AWS account. This Python program reads a CloudTrail log file (JSON format) and shows important information like who did what activity.

## Files in this project
- `analyzer.py` - Main Python code
- `test-log.json` - Sample CloudTrail log file for testing
- `README.md` - Project details

## What does analyzer.py do?
1. It opens `test-log.json` file
2. It reads the `Records` from the log
3. It prints:
   - UserName - Kis user ne kaam kiya
   - EventName - Konsa kaam kiya (jaise ConsoleLogin, CreateBucket)

## How to Run?
1. Download both files `analyzer.py` and `test-log.json` in same folder
2. Open Command Prompt / Terminal
3. Run this command:
   python analyzer.py

## Example Output
User: Burhan
Event: ConsoleLogin

## Made By
Burhan
For Class Assignment
