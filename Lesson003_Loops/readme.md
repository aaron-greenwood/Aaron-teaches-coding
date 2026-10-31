#   Loops
Software is very good at repetitive tasks. One way to implement repitition is using loops. 


##  Exercise 1:
Review the [Exercise3_1.html](Exercise3_1.html) file.
1. Fix the code so that it displays 1st and 2nd instead of 1th and 2th.
2. Add a function that clears all the sentences from the section and a button that calls that function
3. Fix the script so that it continues to number the sentences with the correct numbers no matter how many times the button is clicked.

Things to note:
- For Loop


##  Exercise 2:
Review the [Exercise3_2.html](Exercise3_2.html) file.
1. Create a loop in "ListColors()" that lists all the colors.
2. Add a ClearColors() function that clears all the colors.
3. Add a button that calls the ClearColors() function.
4. Add a ListReverseColors() function that lists the colors in reverse order.
5. Add a button that calls the ListReverseColors() function.

Things to note:
- For Loop

##  Exercise 3:
Review the [Exercise3_3.html](Exercise3_3.html) file.
1. Add a second and third loop to create a second row using row2Colors and row3Colors.
2. Add a function to write one row of the table to the screen and use this function in the CreateTable function. Pass the array of colors into the function.
3. Add more arrays for the other rows of the table and write them to the screen.
4. Change the color pattern to create a different design.

Things to note:
- For Loop

##  Exercise 4:
Review the [Exercise3_4.html](Exercise3_4.html) file.
1. Add a loop outside the existing loop (nested loop) that will loop through the rows in the array so that three rows of cells will all be displayed.
2. Add rows to the array with colors. Your loops should be able to display all the new rows.
3. Change the colors to make a pattern. 

Things to note:
- Nested Loops

##  Exercise 5:
Review the [Exercise3_5.html](Exercise3_5.html) file.
1. Add a nested loop to create a table with x rows and y columns. Use the values from the text boxes for x and y.
2. Add an event listener to each cell that calls the SetCellColor function when the cell is clicked.
```cell.addEventListener("click", SetCellColor); ```
3. Modify the SetCellColor function to set the background of the target cell to the selected color.

Things to note:
- event listeners
- nested loops
- Numeric inputs
- Select Boxes