Oracle QA Automation Assignment



This repository contains the solution to the QA automation assignment:
- a data-driven CRUD microservice built with Node.js and SQLite3



Run Instructions:

Use the following terminal commands:
- npm install
- node server.js



Assignment considerations:

- ACTUAL_END_DATE and MODIFIED_BY are not part of the project creation form. Instead, they are only on update. This approach better suits the given scenario.
- Once a project is created, PROJECT_ID, CREATED_ON, CREATED_BY and MODIFIED_ON will be read-only in the table.
- User authentication feature (to avoid complexity) is simulated by the input fields: CREATED_BY and MODIFIED_BY.
- Date validation implemented for START_DATE with TARGET_DATE and START_DATE with ACTUAL_END_DATE.
- I used Bootstrap for the frontend.
- I added a function to reload a table, not the entire page, for accurate data.
- I implemented delete confirmation with alert.

- When creating a project, if the TARGET_END_DATE is imputed first and then a later START_DATE is inputed, START_DATE doesn't generate a field error, but an error alert is generated on submit.
- The frontend is not responsive. It works best on desktop.