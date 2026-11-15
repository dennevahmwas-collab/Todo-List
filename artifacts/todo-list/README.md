# Todo List Web App

A simple and beginner-friendly Todo List web application built using HTML, CSS, and vanilla JavaScript.

The application allows users to add tasks, mark tasks as completed, delete tasks, and save their tasks using the browser's Local Storage.

## Features

- Add new tasks.
- Mark tasks as completed.
- Delete tasks.
- Save tasks in Local Storage.
- Automatically load saved tasks when the page refreshes.
- Simple and responsive user interface.
- No frameworks or external libraries required.

## Technologies Used

- HTML5 – Provides the structure of the application.
- CSS3 – Handles styling and layout.
- JavaScript – Handles application functionality.
- Local Storage – Stores tasks in the browser.

## Project Structure

```text
todo-list/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── SPEC.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/todo-list.git
```

### 2. Open the project folder

```bash
cd todo-list
```

### 3. Run the application

Open `index.html` in your web browser.

You can also use the Live Server extension in Visual Studio Code.

## How to Use

1. Open the Todo List application.
2. Enter a task in the input field.
3. Click the Add button or press Enter.
4. Click a task to mark it as completed.
5. Click Delete to remove a task.
6. Refresh the page to see your saved tasks.

## Data Storage

The application uses browser Local Storage to save tasks.

Tasks are stored under the key:

```javascript
tasks
```

Each task has the following structure:

```javascript
{
    name: "Learn JavaScript",
    completed: false
}
```

## Requirements

- A modern web browser.
- Basic HTML, CSS, and JavaScript support.
- No backend or database required.

## Limitations

- Tasks are stored only in the user's browser.
- Tasks do not synchronize between devices.
- Clearing browser Local Storage removes saved tasks.
- There is no user authentication.

## Future Improvements

- Add an edit task feature.
- Add task categories.
- Add task deadlines.
- Add filters for All, Active, and Completed tasks.
- Add a task counter.
- Add dark mode.

## License

This project is open-source and available for learning and educational purposes.
