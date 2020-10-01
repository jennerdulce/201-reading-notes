## HTML

### Ch 3. Lists
- `<ul></ul>` unorder
- `<ol></ol>` ordered
  - `<li></li>` list item

## CSS

### Ch 13. Boxes
- Widths
  - px, ems, and percentages
  - percentages is flexible across all diplays

#### box shadow
- `box-shadow: inset # # # # color` 
  - inset (optional) moves shadow **INSIDE** the box
  - 1st# num is horizontal axis ** can be negative **
  - 2nd# num is vertical axis ** can be negative **
  - 3rd# blur radius or size of the blur
  - 4th# when to start the blue
  - color you want
- you can **COMBIND** 2 shadows by separating with a comma
  - `box-shadow: 20px 20px 20px red, 30px 30px 30px black`

##### box shadow tips
- good all use setting `box-shadow: 0 5px 25px 0 rgba(0, 0, 0, .25);`
- lower opacity by choosing the color with `rgba(0, 0, 0, .25)`
- make a box look 'higher' by increase the blur (3rd number)

#### border radius
- `border-radius: #px`


## JavaScript

### Ch 2. Basic JavaScript Instructions
- Array Literal: `var colors = ['blue', 'red,' 'green]`
  - `colors[#]`
- `colors.length` will return the number of items that are in the array
- things in an array should relate to each other
- an array's name should be relevant to the content within the array

### Ch 4. Decisions and Loops

#### Switch statements
- begins with `switch (triggerHere)` {
  - the following keyword `case #:` which would trigger the code block within below the chose case

#### type coersion
- Javascript tries to make sense of an operation that it did not expect
  - can lead to unexpected values
- `===` 

#### truthy falsy

- 'falsy' *values* are treated as if they are false
  - `var x = false;` boolean false
  - `var x = 0;` the number 0
  - `var x = '';` an empty string
  - `var x = NaN;` not a number
  - `var x;` a variable with no value

- 'truthy' *values* are treated as if they are true
  - `var x = true;` boolean true
  - `var x = 1;` any number other than 0 
  - `var x = 'carrot';` string with content
  - `var x = 10/5;` number calculations

#### short circuit values
```
valueA = 0;
valueB = 1;
valueC = 2;

if (valueA || valueB || valueC) {
  // Do something here
}
```
- put values that return true **FIRST**
- OR put values that return false **FIRST**

#### loops

##### for loop
- a **for** loop uses a counter as a condition. This instructs the code to run a specificed number of times
- made up of 3 parts:
  1. initialization `var i = 0`
  2. condition `i < 10 `
  3. update `i++`

- break: stops a loop
- continue: stops the loop **but** continues on to the next iteration
- you can use a loop to loop through each item in an array

##### while loop
- uses
  - manually select how many times you want to loop
  - continuously loop until a certain condition is met

##### do while
- executes a while once even though the condtion has already been met


## Lecture