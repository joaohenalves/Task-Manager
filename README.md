# 📝 Task Manager — C

A simple task management application developed in **C**, using a **Binary Search Tree (BST)** to organize and manage tasks.

## 📌 About the Project

The application provides a command-line interface for managing tasks, each containing a name, priority level, and due date.

Tasks are stored in a Binary Search Tree, ordered by name, and saved to a text file for persistence between executions.

## ⚙️ Features

- **Add Tasks:** Create tasks with a name, priority, and due date.
- **Delete Tasks:** Remove existing tasks.
- **Update Tasks:** Modify task priorities and due dates.
- **Search Tasks:** Find tasks by name.
- **List Tasks:** Display all tasks in alphabetical order.
- **File Persistence:** Load and save tasks using a text file.

## 🛠️ Technologies and Concepts

- **C Programming Language**
- **Binary Search Trees (BST)**
- **Dynamic Memory Allocation**
- **Recursion**
- **File Handling**

## 🚀 How to Run

Compile the program using GCC:

```bash
gcc tarefas.c -o tarefas
```

Run the executable:

```bash
./tarefas
```

The application uses the `tarefas.txt` file to load and save tasks.

## 📁 Repository Structure

- **`tarefas.c`** — Source code containing the application logic and BST implementation.
- **`tarefas.txt`** — File used for task storage.

## 🎓 Academic Context

Developed as the final project for the **Data Searching and Sorting** course, as part of the **Computer Science** undergraduate program.
