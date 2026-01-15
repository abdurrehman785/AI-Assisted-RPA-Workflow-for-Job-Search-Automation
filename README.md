# AI-Assisted-RPA-Workflow-for-Job-Search-Automation
A robotic process automation that automates the process of finding new jobs and changing your CV
# Job Application Automation using UiPath

## Overview
This project automates the job application process by:
- Collecting job listings from LinkedIn
- Matching keywords with a candidate’s CV
- Automatically tailoring CV according to requirement
- Sending confirmation emails

## Tools & Technologies
- UiPath Studio
- Gmail integration
- Web automation (selectors)

## Process Flow
1. Read job data from LinkedIn (Real-Time)
2. Copy Required Data
3. Prompt LLM to Create a tailored Professional Summary for Resume
4. Make Changes to Word Document
5. Save to Gmail Draft 
6. Alert User

## Key Features
- Exception handling
- Retry mechanism
- Loop mechanim for multiple jobs ( Looping in search of new job enteries)
- Config-driven automation
- Logging

## Screenshots
Getting data from Linkedin through Data Table and Multiple Pages based on provides Job Title 
<img width="1139" height="912" alt="image" src="https://github.com/user-attachments/assets/e3f69d5c-ed11-40b4-92d8-cced55a4cc15" />

Bot prompting ChatGPT without using any API keys and creating a summary 
<img width="667" height="593" alt="image" src="https://github.com/user-attachments/assets/0f079a2e-8b4f-44cb-83ec-8f59e6259f7a" />

Making changes to the Word Document(CV)
<img width="638" height="604" alt="image" src="https://github.com/user-attachments/assets/50fd36e5-129d-4d47-b82f-93f836143d06" />

Sending through Gmail(set to my personal one just for presenting purpose)
<img width="736" height="615" alt="image" src="https://github.com/user-attachments/assets/95296318-f034-4eda-8c83-e0bc627825c5" />



## Learning Outcome
- Built end-to-end RPA solution
- Learned selector handling and debugging
- Implemented reusable workflows
