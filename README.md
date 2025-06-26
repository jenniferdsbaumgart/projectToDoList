
# To Do List - Interactive Task List

This is a To-Do List project built with HTML, CSS, and JavaScript. It allows users to create, delete, and store tasks locally in their browser. The list is persistent even after the page is reloaded, thanks to the use of localStorage.

## Project Overview

The To-Do List project allows users to add tasks, view them, and delete them when completed. The tasks are saved in the browser’s local storage, ensuring that the list persists between page reloads.

## Features

- Add Tasks: Users can add tasks by typing into an input field and clicking the "Add" button or pressing the Enter key.
- Delete Tasks: Tasks can be deleted by clicking a "Delete" button next to each task.
- Persistent Data: Tasks are saved to localStorage, allowing the list to persist even after the browser is closed or refreshed.
- Interactive Interface: The interface updates dynamically when tasks are added or removed.
- 
## Tech Stack

**HTML**: For the structure of the webpage.
**CSS**: For styling and layout.
**JavaScript**: For the interactivity, such as adding tasks, deleting tasks, and saving them to localStorage.

## Code Explanation

JavaScript Logic

- Create Task: When the user enters a task, it creates an li element and appends it to the list.
- Delete Task: The delete button removes the task from the list when clicked.
- Save Tasks: All tasks are stored in localStorage so they persist between page reloads.
- Load Saved Tasks: When the page loads, previously saved tasks are loaded from localStorage.
- 
## Structure

- index.html: Main HTML file that contains the structure of the To-Do List.
- style.css: Styles for the To-Do List, including layout, buttons, and input fields.
- main.js: Contains the JavaScript logic to handle tasks, localStorage, and event listeners.

## License

This project is for educational purposes and is open to use or modify as needed.
