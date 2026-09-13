# Simple Tkinter Projects

A growing collection of simple desktop applications built with **Python** and the **Tkinter** GUI framework, created as part of a daily learning challenge.

## Projects

| File | Application |
|------|-------------|
| `day32.py` | Drawing Pad — draw freely on a canvas with custom colors and brush size |
| `Simple_Login_System.py` | Login System — username and password authentication |
| `Simple_To-Do_list.py` | To-Do List — add, delete, and clear your tasks |

## Features

### day32.py — Drawing Pad
- Draw on a canvas by holding the left mouse button
- **Choose Color** — pick a color from the color picker dialog
- **Thickness** slider — adjust brush thickness from 1 to 10
- **Clear Canvas** — wipe the drawing board

### Simple_Login_System.py — Login System
- Login form with username and password fields (password is masked)
- Predefined credentials:

  | Username | Password |
  |----------|----------|
  | `admin`  | `admin123` |
  | `user`   | `user123` |

- **Login** validates credentials and shows a success/error message
- **Clear** empties both fields
- **Exit** closes the application

### Simple_To-Do_list.py — To-Do List
- **Add Task** — add a new task to the list (empty tasks are rejected)
- **Delete Task** — remove the currently selected task
- **Clear Tasks** — remove all tasks at once
- Scrollable task list with a built-in scrollbar

## Requirements

- [Python 3](https://www.python.org/downloads/) (3.x)
- Tkinter — included with the Python standard library on most installations

## How to Run

Clone the repository and run any script:

```bash
git clone https://github.com/Plabon-Basak/Simple_tkinter_projects.git
cd Simple_tkinter_projects

python day32.py
python Simple_Login_System.py
python Simple_To-Do_list.py
```

## Components

1. Python
2. Tkinter Framework Library