# TODO List with Redux
## Project Overview
This project involves converting an existing React dynamic TODO list to use Redux for state management. The main goal is to implement a Redux store that manages the state of TODOs, filters, and queries. The app will load TODO items on page load, with state changes for filtering by completion status and title search. It is designed to function identically to the original version but with Redux for managing state and ensuring scalability.

## Demo
You can view the final product and explore it here: [Demo Link](https://taniabarkovskya.github.io/todo-list-redux/)

## Technologies
- React
- Redux
- TypeScript
- React-Redux
- State Management
- SCSS for styling

## Features Implemented
#### Redux Store:
Centralized state management for the application, handling an array of todos, the query for title search, and the filter status (all, completed, or active).

#### Dynamic Filtering:
Users can filter todos based on their completion status, choosing between all, completed, or active tasks. Additionally, todos can be filtered by title using a search input, allowing for quick access to specific tasks.

#### App Initialization:
On page load, the app fetches a list of todos from the API and updates the Redux store with the data. This ensures that the app is ready for interaction as soon as it's opened.

#### Interactive Modals:
Clicking on any todo item opens a modal that displays detailed information about the selected task, such as its title, completion status, and associated user details. The modal can be closed easily using a close button.

#### User Data:
When viewing a specific todo in the modal, the app fetches and displays additional information about the user responsible for the task, enriching the user experience with more context.

## Getting Started
- Clone the repository.
- Install dependencies with npm install.
- Run the app using npm start.
- Visit http://localhost:5173 in your browser.
