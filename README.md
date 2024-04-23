# **Task Management Website**

## :blush: Introduction
In today's fast-paced world, staying organized and managing our daily tasks efficiently has become more crucial than ever. With numerous responsibilities demanding our attention, a well-structured to-do list has emerged as an indispensable tool for keeping track of our activities, boosting productivity, and maintaining a sense of accomplishment.
I harness the combined power of HTML, CSS, and JavaScript to craft a dynamic and user-friendly interface that not only captures and displays your tasks but also adapts intelligently to the screen size you're using.

## :pinched_fingers: Key features
An Immediately Invoked Function Expression (IIFE) is used to encapsulate the entire code block. This pattern is often used to create a private scope for variables, preventing them from polluting the global scope.
Inside the IIFE, several state variables and UI variables are declared and initialized:
- toDoListArray: An array that will store the To-Do list items.
- form, input, and ul: These variables are used to reference specific elements in the HTML structure. form refers to the HTML form element, input refers to the input field within the form, and ul refers to an unordered list where the To-Do list items will be displayed.

Four functions are defined within the IIFE:
1. addItemToDOM(itemId, toDoItem): This function creates a new list item element, assigns it a data-id attribute with the provided itemId, sets the inner text of the list item to the provided toDoItem, and appends the list item to the unordered list (ul).
2. addItemToArray(itemId, toDoItem): This function adds a new object to the toDoListArray array, where each object represents a To-Do item with its associated itemId and toDoItem text.
3. removeItemFromDOM(id): This function finds the list item element with the specified data-id attribute (id) and removes it from the unordered list (ul).
4. removeItemFromArray(id): This function filters the toDoListArray to exclude the object with the matching itemId, effectively removing the corresponding To-Do item from the array.

The IIFE is immediately invoked by enclosing the entire code block in parentheses and adding () at the end. This ensures that the code within the IIFE is executed as soon as the JavaScript file is loaded.
