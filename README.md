# Calculator DOM Exercise

Clone this repository to your local machine
- git clone https://github.com/vlino2015/calculator.git 
- cd into the calculator directory
- work with your classmates to build a calculator
- hint1: Don't place an event listener on each individual button. Instead, use addEventListenter and attach a listener to a group of buttons.  Use the event object to determine which button was clicked.
- hint: use *slice* and *splice* instead of push and pop

Create a Calculator using HTML/CSS/JS

1. Add click handlers to the number buttons
   - Create an array of the numbers clicked, in order
1. Add click handlers to the calculation buttons
   - Create an array of the operators
   - Don't let a user start with an operator
   - Don't let a user type multiple operators (i.e. you can't type '--' or '++' or "\*+")
1. Add click handler to the 'equals' button
1. The 'equals' button needs to trigger a few events (**NOTE:** These will be functions)
   - Loop through the array of numbers (**NOTE:** These are currently strings)
   - Convert the strings to integers
   - Write a new array of integers
   - Get an array of the operators
   - Perform each math operation (**NOTE:** We'll use 4 `while` loops)
1. Add click handler clearing the input on press of clear
