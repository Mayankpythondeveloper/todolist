# 📝 Todo List Application

A beautiful, interactive todo list application built with vanilla HTML, CSS, and JavaScript. Organize your tasks efficiently with a clean, modern interface.

## Features

✨ **Core Features:**
- ✅ Add new tasks
- 🗑️ Delete tasks
- ✓ Mark tasks as completed
- 🔍 Filter tasks (All, Active, Completed)
- 💾 Persistent storage (saves to browser localStorage)
- 📊 Task counter showing remaining tasks
- 🎯 Clear all completed tasks at once

## Getting Started

1. Open `index.html` in your web browser
   - Double-click the file, or
   - Right-click → Open with → Browser, or
   - Drag and drop into your browser

2. Start adding tasks!
   - Type in the input field
   - Press Enter or click the "Add" button
   - Your tasks will be saved automatically

## How to Use

### Adding Tasks
1. Type your task in the input field at the top
2. Press Enter or click the "Add" button
3. Your task appears in the list

### Managing Tasks
- **Check off a task**: Click the checkbox to mark it complete
- **Delete a task**: Click the "Delete" button next to the task
- **Filter tasks**: Use the filter buttons to view All, Active, or Completed tasks
- **Clear completed**: Click "Clear Completed" to remove all finished tasks

### Storage
- All tasks are automatically saved to your browser's local storage
- Your tasks persist even after closing and reopening the browser
- Each browser/device maintains its own task list

## File Structure

```
todolist/
├── index.html           # Main HTML structure
├── script.js            # JavaScript functionality
├── css/                 # Organized CSS files
│   ├── global.css       # Global/base styles
│   ├── animations.css   # Keyframe animations
│   ├── navbar.css       # Navigation bar styles
│   ├── todo.css         # Todo list component styles
│   └── responsive.css   # Mobile responsive styles
└── README.md            # This file
```

## Browser Support

Works in all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## Customization

You can easily customize the app by editing:
- **Colors**: Modify the gradient colors in `css/todo.css` and `css/navbar.css` (look for `#667eea` and `#764ba2`)
- **Font**: Change the font-family in `css/global.css`
- **Layout**: Adjust container width or padding in `css/todo.css`
- **Animations**: Modify keyframes in `css/animations.css`
- **Responsive breakpoints**: Update media queries in `css/responsive.css`

### CSS File Organization

The styles are organized into separate files for better maintainability:

- **global.css** - Base styles (reset, body, font setup)
- **animations.css** - All @keyframes animations
- **navbar.css** - Navigation bar and branding
- **todo.css** - Todo list components (input, buttons, items, etc.)
- **responsive.css** - Mobile and tablet specific styles

## Tips

💡 **Pro Tips:**
- Use clear, actionable task names for better productivity
- Break large tasks into smaller subtasks
- Regularly clear completed tasks to keep your list fresh
- The task counter helps you track progress

## License

Free to use and modify for personal or commercial projects.

Enjoy organizing your tasks! 🚀
