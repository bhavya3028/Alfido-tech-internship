# JavaScript Mini Project: To-Do List App

## 📌 Goal
Build an interactive to-do list application using vanilla JavaScript and DOM manipulation. Users can add, complete, filter, and delete tasks with persistent storage.

## 🛠️ Tech Used
- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- LocalStorage API (for persistence)

## ✨ Features
- **Add Tasks** — Type task and click "Add" or press Enter
- **Mark Complete** — Click checkbox to toggle task completion status
- **Delete Tasks** — Remove tasks with confirmation dialog
- **Filter Tasks** — View All, Active (pending), or Completed tasks
- **Persistent Storage** — Tasks saved to browser's LocalStorage, survive page refresh
- **Responsive Design** — Works on desktop, tablet, and mobile
- **Input Validation** — Prevents adding empty tasks
- **XSS Security** — HTML escaping to prevent injection attacks

## 📂 Project Structure
```
js_todoapp/
│
├── index.html          # Single file with HTML, CSS, and JavaScript
├── README.md           # This file
└── screenshots/        # Place your screenshots here
    ├── empty_app.png
    ├── tasks_added.png
    └── filtered_view.png
```

## ▶️ How to Run
1. **Open the file** — Double-click `index.html` or right-click → "Open with Browser"
2. **Or serve locally** (for better debugging):
   ```
   python -m http.server 8000
   # Then open http://localhost:8000 in browser
   ```

## 📖 How It Works
- **Add Task**: Type text in the input field and click "Add" or press Enter
- **Complete Task**: Click the checkbox next to a task to mark it done (strike-through effect)
- **Filter**: Click "All", "Active", or "Done" to filter the view
- **Delete**: Click the "Delete" button next to any task
- **Persistence**: All tasks are automatically saved to LocalStorage

## 🧠 Key Learning Concepts Demonstrated
- **DOM Manipulation** — Creating, updating, and removing elements dynamically
- **Event Listeners** — Handling click, input, and keypress events
- **Array Methods** — filter(), map(), findIndex() for data manipulation
- **LocalStorage** — Saving and retrieving data from browser storage
- **Functional Programming** — Pure functions for add/delete/filter logic
- **Security** — HTML escaping to prevent XSS attacks

