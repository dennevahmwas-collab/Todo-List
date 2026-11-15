Todo List Web App
A simple and beginner-friendly Todo List web application built using HTML, CSS, and vanilla JavaScript.

The application allows users to add tasks, mark tasks as completed, delete tasks, and save their tasks using the browser's Local Storage.

Features
Add new tasks.
Mark tasks as completed.
Delete tasks.
Save tasks in Local Storage.
Automatically load saved tasks when the page refreshes.
Simple and responsive user interface.
No frameworks or external libraries required.
Technologies Used
HTML5 – Provides the structure of the application.
CSS3 – Handles styling and layout.
JavaScript – Handles application functionality.
Local Storage – Stores tasks in the browser.
Project Structure
todo-list/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── SPEC.md
Getting Started
1. Clone the repository
git clone https://github.com/yourusername/todo-list.git
2. Open the project folder
cd todo-list
3. Run the application
Open index.html in your web browser.

You can also use the Live Server extension in Visual Studio Code.

How to Use
Open the Todo List application.
Enter a task in the input field.
Click the Add button or press Enter.
Click a task to mark it as completed.
Click Delete to remove a task.
Refresh the page to see your saved tasks.
Data Storage
The application uses browser Local Storage to save tasks.

Tasks are stored under the key:

tasks
Each task has the following structure:

{
    name: "Learn JavaScript",
    completed: false
}
Requirements
A modern web browser.
Basic HTML, CSS, and JavaScript support.
No backend or database required.
Limitations
Tasks are stored only in the user's browser.
Tasks do not synchronize between devices.
Clearing browser Local Storage removes saved tasks.
There is no user authentication.
Future Improvements
Add an edit task feature.
Add task categories.
Add task deadlines.
Add filters for All, Active, and Completed tasks.
Add a task counter.
Add dark mode.
License
This project is open-source and available for learning and educational purposes.
