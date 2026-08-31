# To-Do List Application

A simple, elegant, and functional to-do list application with local storage functionality.

## Features

✅ **Add Tasks** - Easily add new tasks to your to-do list

✅ **Mark Complete** - Check off tasks as you complete them

✅ **Delete Tasks** - Remove tasks from your list

✅ **Filter Tasks** - View all tasks, active tasks, or completed tasks

✅ **Clear Completed** - Bulk remove all completed tasks

✅ **Local Storage** - All tasks are automatically saved to your browser's local storage

✅ **Responsive Design** - Works perfectly on desktop and mobile devices

✅ **Beautiful UI** - Modern and intuitive user interface

## How to Use

1. **Add a Task**: Type your task in the input field and click "Add Task" or press Enter
2. **Mark Complete**: Click the checkbox next to a task to mark it as complete
3. **Delete a Task**: Click the "Delete" button to remove a task
4. **Filter Tasks**: Use the filter buttons to view All, Active, or Completed tasks
5. **Clear Completed**: Click "Clear Completed" to remove all completed tasks at once

## Technology Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with animations
- **Vanilla JavaScript** - Pure JS without frameworks
- **Local Storage API** - Browser storage for persistence

## Local Storage

The application uses the browser's `localStorage` API to persist your tasks. This means:
- Your tasks are saved automatically
- Tasks persist even after closing the browser
- Data is stored locally on your device
- No server or database required

## File Structure

```
├── index.html      # Main HTML file
├── style.css       # Styling and animations
├── script.js       # JavaScript logic
└── README.md       # Documentation
```

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Any modern browser with LocalStorage support

## Features Breakdown

### Task Management
- Add, delete, and toggle task completion
- Tasks are stored with timestamps
- XSS protection with HTML escaping

### Filtering
- All: Shows all tasks
- Active: Shows only incomplete tasks
- Completed: Shows only completed tasks

### UI/UX
- Smooth animations and transitions
- Responsive design for all screen sizes
- Task counter for better tracking
- Empty state message when no tasks exist

## Future Enhancements

- [ ] Task due dates and priorities
- [ ] Task categories/tags
- [ ] Dark mode
- [ ] Export/Import tasks
- [ ] Recurring tasks
- [ ] Cloud sync

## License

MIT License - Feel free to use this project for personal or commercial use.

## Author

Created with ❤️ by smartdarshan574-ui
