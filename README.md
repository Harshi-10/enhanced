# Enhanced Todo List (L1)

## Overview
This is an enhanced Todo List application built for the Masai L1 assignment.  
Features:
- Add tasks
- Mark tasks as completed (visually indicated)
- Remove tasks
- Real-time search to filter tasks
- Persistent storage using `localStorage` (tasks saved as a JSON array)

Each task stored in `localStorage` has this structure:
```json
{ "id": "uniqueId", "text": "task text", "completed": false }
