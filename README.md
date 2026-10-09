# Simple Kanban Board

A simple and interactive Kanban Board built using HTML, CSS, and JavaScript. It allows users to drag and drop task cards between different task-status columns.

## Features

- Three task columns: To Do, In Progress, and Done.
- Drag and drop task cards between columns.
- Visual highlight when dragging a card over a column.
- Interactive cursor and card effects.
- Responsive layout for smaller screens.
- Clean and simple user interface.

## Technologies Used

- **HTML5** — Structure of the Kanban board.
- **CSS3** — Styling, layout, hover effects, and responsiveness.
- **JavaScript** — Drag-and-drop functionality using the HTML Drag and Drop API.
- **Google Fonts (Poppins)** — Typography.

## Project Structure

```text
kanban-board/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How It Works

1. Each task card is made draggable using the HTML `draggable` attribute.
2. JavaScript handles the `dragstart` and `dragend` events.
3. The `dragover` event allows a column to accept a dragged card.
4. The `drop` event moves the selected card into the target column.
5. A CSS class highlights the column while a card is dragged over it.

## How to Run Locally

1. Keep `index.html`, `style.css`, and `script.js` in the same folder.
2. Open `index.html` in your web browser.
3. Select any task card.
4. Drag it into another column and release it.

No additional installation or build tools are required.

## Current Limitations

- Tasks cannot currently be added or deleted through the interface.
- Tasks are not saved after the page is refreshed.
- The board currently uses predefined task cards.

## Future Improvements

- Add new tasks dynamically.
- Delete or edit existing tasks.
- Save tasks using Local Storage.
- Add task descriptions, priorities, and deadlines.
- Improve accessibility and mobile interactions.

## License

This project is created for learning and practice purposes.