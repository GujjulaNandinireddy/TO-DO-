# TO-DO LIST
A dynamic and aesthetic To-Do List WebApp with customizable themes. This application allows users to add, mark as completed, and delete tasks. It also supports saving tasks to `localStorage`, so they persist even after refreshing the page.

🚀 Features :

➕ Add tasks: Users can enter new tasks and add them to the list.
❌ Delete tasks: Tasks can be deleted once completed or no longer needed.
✅ Mark tasks as completed: Users can mark tasks as completed with a simple click.
🌈 Theme toggle: Switch between three themes (Standard, Light, Darker).
💾 Persistent data: Tasks are saved in local storage so they remain even after refreshing the page.

📁 Project structure :

-> README.md         # Detail description about the project and usage manual

index.html ->       # The main HTML file defining the app structure.

 📁 CSS -> main.css # The main stylesheet for page layout and styling.
 
 📁 JS
   -> main.js         # The main JavaScript file for task functionality and theme management.
   ->time.js        # Script for displaying the current date and time.

 
DEMO OUTPUT :




https://github.com/user-attachments/assets/218bdca9-8221-447b-8832-cc2bc75417e4


views :

1. Default View (Standard Theme)


![Screenshot 2025-03-21 153054](https://github.com/user-attachments/assets/f6aff39a-1af5-4fc6-81e2-5b76c164c9bc)

Description: Default theme with the standard background, input, and task list.

2. Light Theme View

   ![Screenshot 2025-03-21 153111](https://github.com/user-attachments/assets/7a3ed71b-4912-4f58-822e-941cee58fd7b)


Description: Light theme with a soft background and light task items.

3. Darker Theme View

   
![Screenshot 2025-03-21 153127](https://github.com/user-attachments/assets/aebf20c2-dc4b-4b5c-8d4d-b84930ff4683)

Description: Darker theme with darker background and contrasting task items.

4. Adding a Task

Description: The input field for adding tasks with the "Add Task" button.

How It Works
1. HTML Structure
The app's structure is simple:

Header: Contains the title and theme-switching buttons.
Input Form: For adding tasks to the list.
Task List: Displays tasks that can be checked off or deleted.
Date & Time: Displays the current date and time, which updates every second.

2. CSS Styling
The app features responsive design with three themes:

Standard: A dark theme with deep contrasts.
Light: A lighter theme with soft pastel colors.
Darker: A deep, dark theme for a more intense experience.
Each theme is applied to various elements including the background, buttons, input fields, and task items. The styles are responsive to different screen sizes.

Key CSS Features:
Themes: Each theme is applied using CSS classes (standard, light, darker).
Animations: Smooth transition animations for tasks when added or deleted.
Responsive Layout: The app adjusts to different screen sizes, from large desktops to mobile screens.

3. JavaScript Functionality
The main JavaScript functionality is divided into several parts:

Task Management:
addToDo: Adds a new task to the list and stores it in localStorage.
deletecheck: Deletes tasks or marks them as completed based on user actions.
savelocal: Saves the tasks to `localStorage

 



