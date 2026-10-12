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