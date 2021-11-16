# Calcy :earth_africa:
## A JavaScript Calculator

![js-calculator](https://github.com/aliabdellatif0/Calcy/blob/main/calculator.png)

## Design :art:
The *Calcy* Calculator was designed to be responsive by taking the approoach of designing the mobile version first and the tablet and desktop versions afterwards. Mobile version :point_down:

![js-calculator](https://github.com/aliabdellatif0/Calcy/blob/main/mobileCalcy.png)

## Logic :abacus:
The calculator consists of:
- _A display section_ where users will see there input and the ouputted result
- _Operators:_ Addition, Subtraction, Multiplication, Division & Percentage
- _Numbers_ from 0 to 9
- _Important buttons:_ 
    - _Equal_ button that will return the result of the operation inputted
    - _(.) button_ to allow for float operations
    - _AC_ button to reset the display

## The Code :computer:
The imortant part of the logical code is shown below. Whereby a switch flow is used to determine the operand and parse the input before and after the operand in order to perform a standard calculation.

```javascript
for (let i = 1; i<inTheDisplay.length; i++ ){
        let x = inTheDisplay.charAt(i)

        switch(x){
            case '+' :
                newLine.push(parseFloat(inTheDisplay.substr(0,i)) +
                parseFloat(inTheDisplay.substr(i+1, inTheDisplay.length)))
            break;
            case '-' :
                newLine.push(parseFloat(inTheDisplay.substr(0,i)) -
                parseFloat(inTheDisplay.substr(i+1, inTheDisplay.length)))
            break;
            case '/' :
                newLine.push(parseFloat(inTheDisplay.substr(0,i)) /
                parseFloat(inTheDisplay.substr(i+1, inTheDisplay.length)))
            break;
            case '*' :
                newLine.push(parseFloat(inTheDisplay.substr(0,i)) *
                parseFloat(inTheDisplay.substr(i+1, inTheDisplay.length)))
            break;
            case '%' :
                newLine.push((parseFloat(inTheDisplay.substr(0,i)))/ 100)
                
            break;
        }
```




