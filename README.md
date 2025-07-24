## Step 1: Project Initialization  
Created a new React project using `create-react-app` and set up the basic folder structure.

## Step 2: Created ToDoList Component  
Built a functional React component named `ToDoList` to manage and display tasks.

## Step 3: Used useState for State Management  
Initialized two state variables using `useState`: one for the task list and another for new task input.

## Step 4: Built Task Input Section  
Added an input field and "Add" button to allow users to type and add new tasks.

## Step 5: Implemented Add Task Functionality  
Created the `addTask()` function to add non-empty tasks to the list and clear the input afterward.

## Step 6: Implemented Delete Task Feature  
Built the `deleteTask()` function to remove a task based on its index using `.filter()`.

## Step 7: Added Move Task Up/Down  
Added logic in `moveTaskUp()` and `moveTaskDown()` functions to reorder tasks by swapping array elements.

## Step 8: Rendered Task List with Buttons  
Mapped over the `tasks` array to display each task in an ordered list with "Delete", "Up", and "Down" buttons.

## Step 9: Styled Components  
Applied basic styling using class names for buttons, inputs, and task text for better UI clarity.

## Step 10: Final Testing and Debugging  
Tested all features (add, delete, reorder), ensured input clearing works, and verified React component updates properly.
