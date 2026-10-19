#   Using Events and Input Fields
In order to make our pages interactive, we need a way to accept input from the user. Input can take the form of:
- Mouse movement and button clicks,
- Typing on the keyboard,
- Tapping a touch screen with fingers,
- Speech in a microphone, and much more.

Our code needs to be able to read and respond to all these types of input. 

Input fields like text boxes, check boxes, radio buttons, and buttons enable the user to provide specific types of input. 

When the user takes an action like clicking a button or editing text in a text box, the browser (e.g. Chrome) raises events that our JavaScript code can respond to. For example, a user could enter a phone number text into a text box. When the user clicks a button, our program could verify that the text was in the correct format for a phone numer (10 digits) and send it to a service to save it.  

##  Exercise 1:
Review the [Exercise2_1.html](Exercise2_1.html) file.
1. Add a text input and label below first name for last name. 
2. In the DisplayMessage function add the last name to the output message.
3. Add a few more flavor choices. 
4. Test to make sure that your program works for first name, last name and all the flavors.

Things to note:
- JavaScript functions - DisplayMessage()
- The onClick event on the button control.
- Raido button and text input controls
- Input control labels
- HTML Forms

## Exercise 2:
Review the [Exercise2_2.html](Exercise2_2.html) file.
1. Make the current 2 x 2 table a 3 x 3 table.
2. Change the current and non-current cell colors to something different than aqua and green.
3. Make table border thicker.
4. Change the table border color.
5. Change the table size using min hight and min width.

Things to note:
- HTML Tables, rows, and cells
- CSS Styles
- onMouseEnter and onMouseLeave events
- event object and target property

## Exercise 3:
Review the [Exercise2_3.html](Exercise2_3.html) file.
1. Make the current 2 x 2 table a 3 x 3 table.
2. Create a setToO function that will set the inner text of an element to "O".
3. Add a double-click handler (dblclick event) that calls the setToO(...) function to set the cell to the "O".

Things to note:
- Javascript functions
- click and dblclick events.
- more table styles

## Exercise 4:
This exercise, 2.4, will build on what you have done already for [Exercise2_3.html](Exercise2_3.html) file.

Review example 2.4 [Example2_4.html](Example2_4.html)first.

Our exercise 2.3 is starting to look like a tic-tac-toe game. We can set squares to X and O, but we are not tracking whose turn it is. We'll use a variable and a conditional statement (if-then) to fix that.

1. In the javascript section, outside any function, create a global variable curTurn and set it equal to "X". 
2. Create a new function: "SetForCurrentTurn(...)" that:
    - Sets the current square to the value of curTurn.
    - Sets curTurn to the the next turn (if "X" then "O"; if "O" then "X")
3. Add paragraph above and set the text to "Current Turn: X". Every time the SetForCurrentTurn function is set, change the text so that it shows whose turn it is. 

Things to note:
- If..then..else conditional statements
- Variables

## Exercise 5:
This exercise, 2.5, will build on what you have done already for [Exercise2_3.html](Exercise2_3.html) file.

The problem with our game now is that you can change a square that has already been set. In a real tic-tac-toe game, you would not be able to do that. To fix this we first need to check if the target cell already has an innter text value. 

- In the SetForCurrentTurn function, before doing anything, check to see if the current cell has an innertext that equals an empty string (""). 
    - If it is empty, the function should do what it currently does. 
    - If it is not empty, it should show an alert that says "This cell has already been used." The turn should not be changed, and the value in the cell should not be changed.

Things to note:
- If..then..else conditional statements
- Checking the state of the target
- Using alert("...")