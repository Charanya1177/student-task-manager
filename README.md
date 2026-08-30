# Student Task Manager

A responsive and interactive web application designed to help students efficiently manage academic tasks, submission deadlines, scheduled times, and reminders in one place.

---

## Overview

Student Task Manager provides a simple interface for organizing academic responsibilities. Users can create tasks with submission dates, submission times, and reminders, track pending work, and mark tasks as completed.

Completed tasks are automatically removed after 24 hours, keeping the task list focused on current activities.

---

## Key Features

### Task Management
- Create and add academic tasks.
- Specify submission dates and times.
- Add customizable reminders.
- Delete tasks when they are no longer required.

### Task Tracking
- View all pending tasks in a dedicated section.
- Mark tasks as completed using an interactive checkbox.
- Automatically move completed tasks to the Completed Tasks section.
- Move completed tasks back to Pending when required.

### Task Statistics
- Display the total number of tasks.
- Display the number of pending tasks.
- Display the number of completed tasks.
- Automatically update task counts whenever a task is added, completed, or deleted.

### Data Persistence
- Uses browser LocalStorage to preserve tasks.
- Tasks remain available after refreshing or reopening the browser.

### Automatic Cleanup
- Completed tasks are retained for 24 hours.
- Completed tasks are automatically removed after 24 hours.
- The application periodically checks for expired completed tasks.

### User Interface
- Clean and professional design.
- Light peach color theme.
- Responsive layout.
- Interactive buttons and checkboxes.
- Clear separation between pending and completed tasks.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure and content |
| CSS3 | Styling, layout, and responsive design |
| JavaScript | Application logic and interactivity |
| LocalStorage | Client-side data persistence |
| Git | Version control |
| GitHub | Source code management and project hosting |

---

## Project Structure

```text
student-task-manager/
│
├── index.html
├── style.css
├── script.js
└── README.md
