https://johanng-dev.github.io/t4skhub/
<img width="1838" height="872" alt="image" src="https://github.com/user-attachments/assets/1bad1bc3-485d-42c6-9e2f-a73483320bd0" />
<img width="346" height="767" alt="image" src="https://github.com/user-attachments/assets/04dfdedd-0437-4472-b040-2592d18ec484" />
<img width="345" height="770" alt="image" src="https://github.com/user-attachments/assets/5c14acc8-0dbf-43bc-84b3-65a779e3f0f5" />
<img width="346" height="771" alt="image" src="https://github.com/user-attachments/assets/8e0afa06-74d3-4fa7-bd99-fe8ea2071fb8" />
<img width="349" height="770" alt="image" src="https://github.com/user-attachments/assets/d68ca4d0-046c-4ef2-9903-759b9a823cd3" />
<img width="348" height="772" alt="image" src="https://github.com/user-attachments/assets/cbec3c41-f17a-48e2-a457-e8f013e8f67a" />
<img width="348" height="772" alt="image" src="https://github.com/user-attachments/assets/1fe36cea-de7a-4643-93c7-aa521d327361" />
# TaskHub

A lightweight, all-in-one productivity app with todo list, calendar, calculator, and notes—all in one place with zero setup.

## Features

- **📋 Todo List** — Create, edit, and manage tasks with one-click completion
- **📅 Calendar** — Visual month view with event management and task scheduling
- **🧮 Calculator** — Full arithmetic operations with history and formula display
- **📝 Notes** — Quick text area for jotting down thoughts and ideas
- **🕐 Clock** — Time display integrated into the app
- **💾 Auto-Save** — All data persists to browser localStorage automatically
- **🌙 Dark Theme** — Easy on the eyes with a cohesive color palette
- **📱 Responsive** — Works on desktop and mobile devices

## Tech Stack

- **React 18** (via CDN)
- **Babel Standalone** (JSX transpilation)
- **Font Awesome 6.4.0** (icons)
- **Vanilla CSS** (custom dark theme)
- **Browser localStorage** (data persistence)

## Quick Start

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd taskhub
   ```

2. Open `index.html` in your browser (no build step needed)
   ```bash
   open index.html
   ```

That's it! The app will load and create a localStorage database automatically.

## How to Use

### Todo List
- Type a task and press Enter to add
- Click anywhere on a task to mark it complete
- Use action buttons:
  - **📅** — Add to calendar with date/time
  - **✏️** — Inline edit
  - **🗑️** — Delete

### Calendar
- Navigate months with arrow buttons
- Click a date to view or add events
- Today is highlighted in blue
- Selected date is highlighted in purple

### Calculator
- Click buttons or use keyboard:
  - `0-9` — Numbers
  - `+`, `-`, `×`, `÷` — Operations
  - `Enter` or `=` — Calculate
  - `Backspace` — Delete last digit
  - `Escape` — Clear all

### Notes
- Type directly in the textarea
- Auto-saves every keystroke

## Project Structure

```
taskhub/
├── index.html        # Single-file app (React + CSS + JS)
├── README.md         # This file
├── CLAUDE.md         # Development guide
└── .git/             # Version control
```

## Data Persistence

All data is stored in browser localStorage under these keys:
- `todos` — Todo items with completion status
- `calendarEvents` — Events organized by date (YYYY-MM-DD)
- `notes` — Notes text
- `calcHistory` — Calculation history

Data persists across browser sessions automatically.

## Architecture

The app uses a **Repository Pattern** for data access, making it easy to migrate from localStorage to a backend API without changing component code. See `CLAUDE.md` for migration details.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Escape` | Clear calculator |
| `Backspace` | Delete last digit (calculator) |
| `Enter` | Calculate (calculator) |
| `0-9` | Numbers (calculator) |
| `.` | Decimal point (calculator) |

## Browser Compatibility

Works on all modern browsers with ES6 and React 18 support:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+

## Future Enhancements

- Recurring calendar events
- Task categories and tags
- Time-based notifications
- Dark/light mode toggle
- Export/import functionality
- Task search and filtering
- Currency converter
- Backup to cloud storage

## Development

All code is contained in a single `index.html` file using React via CDN. No build tools or dependencies to install.

### Adding Features
1. Edit `index.html`
2. Add React components using Hooks
3. Use the repository pattern for data access
4. Refresh browser to test (auto-reload on save if using a local server)

### Styling
Classes follow a dark theme with:
- Background: `#0a0e27`, `#0f1629`
- Accent: `#667eea`, `#764ba2`
- Text: `#e4e6eb`

## License

GNU General Public License (GPL)

## Contributing

This is a single-person project. Feel free to fork and create your own version!




