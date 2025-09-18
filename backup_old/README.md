# To-Do List Web Application

A modern, responsive To-Do list web application built with HTML, CSS, and JavaScript. This application allows users to manage their tasks efficiently with features like adding, editing, deleting, and marking tasks as complete.

## Features

- Add new tasks
- Edit existing tasks (double-click on task text or use edit button)
- Delete tasks
- Mark tasks as complete/incomplete
- Filter tasks (All, Active, Completed)
- Clear all completed tasks
- Persistent storage using localStorage
- Responsive design for mobile devices
- Task counter showing number of active tasks

## Technologies Used

- HTML5
- CSS3 (with animations and responsive design)
- JavaScript (ES6+)
- Font Awesome icons
- Local Storage API

## How to Run

1. Clone or download this repository
2. Open the `index.html` file in your web browser

Alternatively, you can use a local development server:

```bash
# If you have Python installed
python -m http.server

# If you have Node.js installed
npx serve
```

## Usage

- **Add a task**: Type in the input field and press Enter or click the + button
- **Edit a task**: Double-click on the task text or click the edit (pencil) icon
- **Delete a task**: Click the delete (trash) icon
- **Mark as complete**: Click the circle checkbox next to the task
- **Filter tasks**: Use the All/Active/Completed buttons
- **Clear completed**: Click the "Clear Completed" button

## Project Structure

```
todo-app/
├── index.html      # Main HTML structure
├── styles.css      # CSS styling
├── app.js          # JavaScript functionality
└── README.md       # Project documentation
```

## Future Enhancements

- Task categories/tags
- Due dates for tasks
- Priority levels
- Dark/light theme toggle
- User accounts with cloud sync
- Drag and drop reordering

## License

MIT