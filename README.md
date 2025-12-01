<h3>📝 Todo List App (React + LocalStorage)H</h3>

This is a simple and clean To-Do List application built using React.
It allows users to add tasks, mark them as complete, delete tasks, and automatically saves all todos in localStorage so the data remains even after refreshing the page.

🚀 Features

➕ Add new tasks
✔️ Mark tasks as complete / incomplete
❌ Delete tasks
💾 Auto-save todos in browser localStorage
🎨 Minimal and responsive UI

⚡ Fast rendering using reusable components

🛠️ Tech Stack

React.js
JavaScript (ES6+)
Tailwind CSS
LocalStorage API

📂 Project Structure

/src
    ├── components
    │    ├── Todo.jsx
    │    ├── TodoItem.jsx
    │├── assets
    │    └── todo_icon.png
    │
    ├── App.jsx
    ├── index.js
    └── index.css


🧠 How It Works

1. Add Todo
The user types a task → clicks ADD → a new todo object is created and added to the todoList state.

2. Toggle Todo
When the user clicks the tick button, the isComplete property flips between true and false.

3. Delete Todo
Removes the item from the todoList using .filter().

4. Save to LocalStorage
Using useEffect, todoList is saved automatically whenever it changes.
