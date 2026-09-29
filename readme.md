Gym Membership Management:

Introduction-

Gym Manager is a simple Python-based console application designed to manage gym members. It allows the user to add new members, view all registered members, search for a specific member, and delete a member from the system.

This project is suitable for beginners who are learning Python programming and concepts such as lists, dictionaries, loops, conditional statements, functions, and user input.

Features-

The program provides the following options:

1-Add Member

2-Allows the user to enter a member's name.

3-Allows the user to enter the member's age.

4-Allows the user to enter the membership duration in months.

5-View Members

6-Displays all registered gym members.

7-Shows each member's name, age, and membership plan.

8-Search Member

9-Allows the user to search for a member by name.

10-The search is case-insensitive.

11-Delete Member

12-Allows the user to delete a member by entering their name.

13-Displays a confirmation message after successful deletion.

14-Exit

At last exits the program safely.

Features used while making this project:

1-Lists

2-Dictionaries

3-while loops

4-for loops

5-if-elif-else statements

6-User input

7-String methods

8-Data Structure

9-The program uses a list to store all members:

members = []


Each member is stored as a dictionary:

member = {"name": name,"age": age,"plan": plan}

For example:

{"name": "Rahul","age": "20","plan": "6"}

How to Run
Step 1: Install Python

Make sure Python 3 is installed on your computer.

Step 2: Save the Program

Save the Python code in a file such as:

gym_manager.py

Step 3: Run the Program

Open a terminal or command prompt and run:

python gym_manager.py


The Gym Manager menu will appear.

Example
GYM MANAGER
1. Add Member
2. View Members
3. Search Member
4. Delete Member
5. Exit

Enter choice: 1
Enter member name: Rahul
Enter age: 20
Enter membership duration (in months): 6
Member added successfully

Limitations

Member data is stored only while the program is running.

Data will be lost when the program is closed.

There is no database or file storage.

Age and membership duration are currently entered as user input without advanced validation.

Members are searched using their names.

Future Improvements

The project can be improved by adding:

File or database storage

Member ID

Membership expiry date

Payment tracking

Automatic age and input validation

Update member details

Different membership plans and prices

Login system for gym staff

Graphical user interface (GUI)

Author

Name:Keshav

Registration No.: 26MIP10022

Subject: Introduction to problem solving