# Kanban Board Application

This Kanban board application allows users to manage tasks across various stages: **To Do**, **In Progress**, **Peer Review**, and **Done**. The application supports drag-and-drop functionality for task movement between stages and includes a search box for filtering tasks by title.

## Features

### 1. Kanban Board Layout
- **Columns for Task Stages**:
  - **To Do**: Tasks that need to be started.
  - **In Progress**: Tasks that are currently being worked on.
  - **Peer Review**: Tasks awaiting review.
  - **Done**: Completed and reviewed tasks.
- Each section displays tasks relevant to its stage.

### 2. Task Cards
- **Task Information**:
  - **Task Title**: Prominently displayed on the card.
  - **Task Description**: Displayed in a shortened form on the card.
  - **Draggable**: Tasks can be dragged and dropped between columns.

### 3. Drag and Drop Functionality
- **Drag-and-Drop**: Implemented using the React-DnD library.
- **Movement**: Tasks can be moved between columns.
- **Positioning**: Tasks can be reordered within a column.

### 4. Search Functionality
- **Search Bar**: Located at the top of the board.
- **Filtering**: Real-time filtering of tasks based on search input.
- **Matching Tasks**: Only tasks matching the search query are displayed.
- **Non-Matching Tasks**: Hidden from view if they don’t match the query.

### 5. Add New Tasks
- **Floating Button**: Opens a modal for creating new tasks.
- **Task Creation Form**:
  - **Task Title**: Input field for the title.
  - **Task Description**: Input field for the description.
  - **New Tasks**: Added to the **To Do** column upon creation.

### 6. Responsive Design
- **Responsive UI**: Adjusts layout for optimal usability on both desktop and mobile devices.

### 7. State Management
- **Redux**: Used for managing application state.
- **Actions and Reducers**: Organized to manage task data efficiently.

### 8. Styling
- **Material-UI**: Provides a consistent and modern look across components.
- **Custom Styles**: Additional styling ensures a polished and intuitive user experience.

### 9. Data Persistence
- **Local Storage**: Task data is saved to local storage, ensuring persistence across page reloads.

## Technologies Used

- **ReactJS**: For building the user interface.
- **Redux**: For state management.
- **React-DnD**: For drag-and-drop functionality.
- **Material-UI**: For component styling.
- **Local Storage**: For persisting task data.

## Getting Started

### Prerequisites
- **Node.js** and **npm** installed on your machine.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kaverimeka/kanban-board.git
   cd kanban-board
2. Install dependencies:
   ```bash
   npm install

## Usage

1. Start the Application:
  ```bash
  npm start
  ```
  The application will start on http://localhost:3000.

2. Creating a New Task:
  - Click the floating button to open the new task modal.
  - Enter the task title and description, then click Create to add the task to the To Do column.

3. Moving Tasks:
  - Drag a task card to move it to a different column.
  - Drop the task card in the desired column.

4. Searching Tasks:
  - Type in the search bar to filter tasks by title.
