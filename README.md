# 📝 Python CLI To-Do List App

A simple command-line based To-Do List application built using Python.
This app allows users to add, view, delete, and save tasks efficiently.

---

## 🚀 Features

* 📋 View all tasks
* ➕ Add new tasks
* ❌ Delete tasks
* 💾 Save tasks to file
* 🔄 Load tasks automatically on startup

---

## 🛠️ Technologies Used

* Python 3
* File Handling (`.txt` file)

---

## 📂 Project Structure

```
todo_app.py
tasks.txt   (auto-created)
```

---

## ▶️ How to Run

1. Make sure Python is installed
2. Run the script:

```
python todo_app.py
```

---

## 🧠 How It Works

* Tasks are stored in a list during runtime
* When exiting, tasks are saved to `tasks.txt`
* When restarting, tasks are loaded from the file

---

## 📌 Menu Options

```
1. View Tasks
2. Add Task
3. Delete Task
4. Exit
```

---

## 💡 Example Usage

```
Enter Choice : 2
Enter Task : Study Python
Task added ✔️

Enter Choice : 1
Your Tasks :
1. Study Python
```

---

## ⚠️ Error Handling

* Prevents invalid input (like text instead of numbers)
* Handles missing file safely

---

## 🔥 Future Improvements

* ✏️ Edit tasks
* ⭐ Add priority levels
* 🎨 Convert to GUI (Tkinter)
* 🗂️ Use JSON for better storage

---

## 👨‍💻 Author

Developed by you 😎

---

## 📜 License

This project is open-source and free to use.
