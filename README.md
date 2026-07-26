## AI Test Case Generator

## Overview
This project automates the generation of software test cases from Jira User Stories using n8n and AI.

## Current Status
🚧 MVP (Minimum Viable Product)

## Technologies
- n8n
- Jira
- Google Sheets
- Gemini AI

## Current Workflow
1. User Story is created in Jira.
2. n8n workflow is triggered.
3. AI generates manual test cases. Refer to WF01 file
4. Test cases are stored in Google Sheets.  new test cases are created with Status = Draft and Version = 1
5. If same User story is updated, then existing User stories are still maintained with status= invalid + Version =1 and new test cases are created with Status = Draft and Version = 2. Refer to WF02 file

## Project Goal
Reduce the manual effort required to create software test cases while maintaining consistency and quality.

## Author
Tejal Jayakar
