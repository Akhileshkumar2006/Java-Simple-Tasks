# Java-Simple-Tasks
Some Basic Java Tasks

# Task Manager (Java Console Application)
This is a simple **Task Manager** console application written in Java.  
It allows you to **add**, **delete**, **view**, and **exit** tasks interactively using a command-line menu.  

## Features
- **Add Task** → Enter a task description and add it to the list.  
- **Delete Task** → Select a task number to remove it from the list.  
- **View Tasks** → Display all the current tasks with numbering.  
- **Exit** → Close the program safely.  
- **Error Handling** → Prevents invalid inputs such as entering non-numeric values or invalid task numbers.
  
## Menu Option
When you run the program, a menu will appear:
 ----------TASKS-------------
Please enter your Task number

To Enter the Task
To Delete the Task
To See the Task List
To Exit from the Task

You can select an option by typing the corresponding number. 

## Example Usage
1. Choose `1` → Enter a task description (e.g., `Complete assignment`).  
2. Choose `3` → Displays your task list.  
3. Choose `2` → Deletes a task by its number.  
4. Choose `4` → Exits the application.  

### Sample Output
----------TASKS-------------
Please enter your Task number
To Enter the Task
To Delete the Task
To See the Task List
To Exit from the Task
1
Enter the Task Description
Complete Java Project
Task added Successfully

## Requirements
- **Java JDK 8 or higher**  
- Any IDE (IntelliJ IDEA, Eclipse, NetBeans) or terminal to run the program  

## Installation & Run Instructions
Compile the program:
javac Task1.java

Run the program:
java Task1

Project Structure
task-manager-java/
│
├── Task1.java        # Main source code
├── README.md         # Project documentation
└── LICENSE           # (Optional) License file

Author
Developed by AkhileshKumar Nalluri
