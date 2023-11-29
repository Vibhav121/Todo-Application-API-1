Todo Application
Given an app.js file and database file todoApplication.db with a table todo.

Write APIs to perform operations on the table todo, with the following columns,

Todo Table

Column	Type
id	INTEGER
todo	TEXT
category	TEXT
priority	TEXT
status	TEXT
due_date	DATE
Replace the spaces in URL with %20.
Possible values for priority are HIGH, MEDIUM, and LOW.
Possible values for status are TO DO, IN PROGRESS, and DONE.
Possible values for category are WORK, HOME, and LEARNING.
Use the format yyyy-MM-dd for formating with date-fns format function.
The user may request with due date value as 2021-1-21, format the date to 2021-01-21 and perform Create, Read, Update operations on the database.
Use date-fns format function to format the date. Refer to the documentation link for the usage of the format function.

Invalid scenarios for all APIs
Invalid Status

Response
Status code
400
Body
Invalid Todo Status
Invalid Priority

Response
Status code
400
Body
Invalid Todo Priority
Invalid Category

Response
Status code
400
Body
Invalid Todo Category
Invalid Due Date
