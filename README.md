# Todo List Website

This is a simple Todo List application built using the Vite React framework, CSS, and JavaScript. The application allows users to add, toggle and delete tasks, with data persistence ensured through the browser's local storage.

## Features

- Add new tasks to the todo list.
- Toggle the tasks
- Delete tasks from the todo list.
- Persistent data storage using the browser's local storage.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher) or yarn (v1.22 or higher)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/saam-rgb/Todo-List.git
   cd Todo-List
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   ```

   The website should now be running at [http://localhost:3000](http://localhost:3000).

### Building for Production

To create a production-ready build, run:

```bash
npm run build
# or
yarn build
```

The output will be in the `dist` directory.

## Project Structure

```plaintext
.
├── src
│   ├── Components
│   │   ├── Assets
|   |   |    ├── cross.png
|   |   |    ├── not-tick.png
|   |   |    └── tick.png
│   │   ├── CSS
│   │   |    ├── Todo.css
|   |   |    └── TodoItems.css
│   ├   ├── Todo.jsx
│   ├   └── TodoItems.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── .gitignore
├── package.json
├── README.md
└── vite.config.js
```

## Components

### `Todo.jsx`

This component provides the input field and button to add new tasks.

### `TodoItem.jsx`

This component renders the list of todo items and represents a single todo item with the option to toggle and delete it.

## Styling

All styles are written in CSS and can be found in `Todo.css`, `TodoItem.css`and `index.css`.

## How to Use

1. **Adding a task**

   - Type the task description into the input field.
   - Click the "Add" button to add the task to the list.

2. **Deleting a task**

   - Click the "Delete" button next to a task to remove it from the list.

3. **Persistent Storage**
   - The tasks are saved in the browser's local storage. You can refresh the page, close the browser, and reopen it without losing your tasks.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Vite](https://vitejs.dev/)
- [React](https://reactjs.org/)

---
