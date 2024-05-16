# HAR: Homework and Assignment Recorder

Final Project ICT 10 / X - Andromeda / Members: Bantoto, Beira, Duhaylongsod, Librea, Abelgas, Tabara

Purpose:
HAR: Homework and Assignment Recorder is an application created with the help of Python with the main purpose of helping students manage their assignments. They can list down their assignments as well as the progress they have made on them while also setting which assignments have the most priority. This would encourage the student to be more productive as their to-do work is more organized.

Installation:
- Click the green button with the word code on it and download the HAR.py file
- Once Installed make sure it is in a folder since a new file would be created within it which would be the database for the assignments
- install the tkinter package, use the command: pip install tk
- Run the HAR.py file

Dependencies:
- Python 3.x
- Tkinter (for the graphical user interface)
- SQLite3 (for the database)

Features and Usage:
1. Add Assignment Function
- This part allows you to add an assignment with the following subject, project name, date, and priority
- Select the subject from the dropdown menu
- Enter the project name, and due date with the MM-DD format and enter the priority for the assignment
- Click the add assignment button

2. Update Progress
- This part allows you to update the progress of your assignments using a percentage
- Enter the assignment ID from the View Projects table, Enter the percentage from 1 to 100
- Click the update progress button

3. Remove Assignment
- This part allows you to remove an assignment whether you inputted wrong or the assignment was finished
- Enter the assignment ID from the View Projects table and then click the Remove assignment button

4. View Assignments
- This part allows the user to view his/her assignments as well as the additional information that was inputted by the user

5. Priority Highlighting
- The assignments with the priority of 1 are emphasized by making them bold


