# Task Manager CLI

A simple command-line task manager built with **Node.js** to manage your tasks efficiently.

## Features

- Add new tasks
- List all existing tasks
- Remove tasks by their number
- Stores tasks persistently in a JSON file (`tasks.json`)

## Usage

### Add a task
```bash
node taskManager.js add "Buy groceries"
Task added successfully!

node taskManager.js list
1: Buy groceries
2: Finish homework

node taskManager.js remove 1
Task removed successfully!
