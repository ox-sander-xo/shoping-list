To complete the exercise, follow the steps below, and make sure that the list behaves as described above.

To start with, download a copy of our shopping-list.html starting file and make a copy of it somewhere. You'll see that it has some minimal CSS, a div with a label, input, and button, and an empty list and <script> element. You'll be making all your additions inside the script.

Create three variables that hold references to the list (<ul>), <input>, and <button> elements.
Create a function that will run in response to the button being clicked.
Inside the function body, start off by storing the current value of the input element in a variable.
Next, empty the input element by setting its value to an empty string — ''.
Create three new elements — a list item (<li>), <span>, and <button>, and store them in variables.
Append the span and the button as children of the list item.
Set the text content of the span to the input element value you saved earlier, and the text content of the button to 'Delete'.
Append the list item as a child of the list.
Attach an event handler to the delete button so that, when clicked, it will delete the entire list item (<li>...</li>).
Finally, use the focus() method to focus the input element ready for entering the next shopping list item.
