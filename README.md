# Recipe Manager

## Project Overview
**Recipe Manager** is a web application that allows users to create, edit, and manage their favorite recipes. The application is built with a combination of HTML for structure, CSS for layout and design, and JavaScript to handle interactivity and logic.

Users can:
- Add new recipes (name, ingredients, steps, and category).
- View a list of all added recipes.
- Filter recipes by category (e.g., breakfast, lunch, dinner).
- Delete recipes they no longer want to keep.

## Purpose
This project serves as a learning exercise to practice working with forms, lists, and JavaScript arrays/objects. You will also get experience with the CSS Flexbox model for layout.

## Features
- **Recipe Input**: Users can add new recipes through a form.
- **Recipe List**: Display all added recipes dynamically on the webpage.
- **Filtering**: Users can filter recipes based on the selected category.
- **Delete Functionality**: Users can delete individual recipes.

## Design and Wireframe
The application consists of the following sections:
1. **Header**: Title of the application ("Recipe Manager").
2. **Recipe Form**: Form for adding a new recipe (name, category, ingredients, steps).
3. **Recipe List**: Displays a list of added recipes with filtering options.
4. **Footer**: Basic footer with optional navigation links.

### Wireframe:
---------------------------------
|           Header                |
|     [ Recipe Manager ]           |
 ---------------------------------
|         Recipe Form              |
|  [Recipe Name] [Dropdown: Category] |
|  [Ingredients] [Steps] [Submit]  |
 ---------------------------------
|        Recipe List               |
|  [Filter by Category Dropdown]   |
|  [Recipe 1]  [Delete]            |
|  [Recipe 2]  [Delete]            |
 ---------------------------------
|            Footer                |
|   Links to other pages (optional)|
 ---------------------------------

 ### File Structure:
recipe-manager/
│
├── index.html          # Main HTML file
├── styles.css          # CSS file for styling
├── script.js           # JavaScript file for functionality
├── images/             # (Optional) Folder for any images
└── assets/             # (Optional) Folder for external assets like fonts or icons


## Technologies Used
- **HTML**: Structure of the web pages, including forms and lists.
- **CSS**: Styling the application using Flexbox for layout.
- **JavaScript**: Handling the logic, dynamic HTML rendering, form processing, and array management.

## Key Concepts Applied
- **HTML**: Forms, Lists, Semantic HTML elements (e.g., `<section>`, `<header>`, `<footer>`, `<form>`).
- **CSS**: Box Model, Flexbox for aligning form and list elements.
- **JavaScript**: Arrays, Objects, Functions, DOM Manipulation, and Array Methods (`forEach`, `filter`, `push`, etc.).

## Project Challenges
- **Form Handling**: Collecting and storing recipe data from the form into an array.
- **Dynamic HTML Rendering**: Displaying the recipes dynamically using JavaScript.
- **Filtering Recipes**: Implementing the filter functionality based on recipe category.
- **Deleting Recipes**: Adding the option to delete individual recipes from the list.

## Running the Application
You can run this web application in any IDE or text editor that supports web development. Simply open the `index.html` file in your browser to interact with the Recipe Manager.

## License
This project is licensed under the [MIT License](LICENSE).
