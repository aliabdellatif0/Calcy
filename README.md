# Calculator

A calculator designed using HTML & SCSS, with JavaScript incorporated for its functional and interactive uses.

This calculator will take in basic inputs and perform operations on two separate numbers which will be treated as floats so YES you can use decimal points.

Errors will be alerted on screen and the calculator shall reset if you input a mathematically invlaid line.

Some complex mathemtical lines may still return a value however they will be incorrect due to the nature of the code

P.s. you can operate on the output provided to you as the answer on the display


//Testing ->

In regards to testing a cypress approach was taken where by the test file is included within the repo and by running the command 'npx cypress open' you can proceed with running the tests.

//Pseudocode below ->
Approach buttons using a css grid layout 

Buttons all laid out now; output bar at the top is done and a satisfactory colour scheme is included

Approach solution by assinging two inputs separated by operator to a variable through function on buttons.

Issue has arose given assinging of variables whereby tried to solve using boolean however too many bugs encountered

Taken a simplistic approach with many uses to for loop until operator found. 

split the string to before operator and after and use swith to go through what the operator was

through switch perform your calculation
# Calcy
