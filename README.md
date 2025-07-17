# Codemify-QA-Testing
Manual QA project for testing the user interface and form validation of Codemify Website

📌 Project Overview
This project involves performing manual QA testing on the Codemify website. The focus was on verifying redirections, form validation, and identifying UI/UX bugs.

✅ Tasks Performed
Checked all button redirections on the homepage and subpages

Tested the Contact Us form for input validations

Reported issues with input field validations and improper redirections

🐞 Bugs Reported
1. Incorrect Redirection on “Try Intro Week” Button
Page: Student Reviews & Testimonials

Bug: Button redirects to paid course instead of Intro Week course

Expected: Should redirect to Intro Week Course



2. Invalid Inputs Allowed in Contact Form
Page: Contact Us

Bug:

Phone field allows alphabets

Name field accepts numbers

No real-time error shown

Expected:

Phone: only numbers

Name: only alphabets

Real-time validation for all fields



📂 Project Structure
vbnet
Copy
Edit
📁 codemify-qa-testing/
│
├── 📄 QA_Report.pdf         → Detailed test case & bug report
├── 📄 README.md             → Project summary and structure
└── 📁 screenshots/          → Screenshots (optional)
🛠 Tools Used
Jira (for test case management and bug tracking)

Browser (Manual testing)

