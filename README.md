# 📝 To-Do List Project

A simple, interactive to-do list built using **vanilla JavaScript**. This app allows users to add tasks with due dates and delete them dynamically. No external libraries or frameworks are required.

---

## 🚀 Features

- ✅ Add new tasks with a name and due date  
- 🗑️ Delete tasks from the list  
- 🔁 Task list updates automatically on changes  
- ⚡ Lightweight and fast — pure JavaScript

---

## 📸 Demo

![To-Do List Screenshot](screenshot.png) <!-- Optional: Replace with your actual image file or URL -->

---

## 🧠 How It Works

- All tasks are stored in a JavaScript array (`todoList`).
- The `renderTodoList()` function dynamically displays the task list and sets up delete functionality.
- The `addTodo()` function grabs input values, adds a new task to the list, and refreshes the view.

---

## 🏗️ File Structure

📁 your-project-folder/
├── index.html # HTML structure
├── script.js # JavaScript logic
└── style.css # (Optional) CSS styling

---

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

   Open index.html in a web browser.

Start adding and managing your tasks!

🧪 Sample HTML
Here's a minimal setup for the script to work properly:
```html
<input placeholder="Task name" class="js-name-input" />
<input type="date" class="js-due-date-input" />
<button class="js-add-todo-button">Add</button>

<div class="js-todo-list"></div>

<script src="script.js"></script>
```



