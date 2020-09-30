## HTML
### Ch 2. Text
- `<p>` is a tag
- `<p>This is a whole element, it includes a tag and text</p>`
- 2 types of tags:
    - block: takes up the entire eidth of the container that it is housed in
        - Typically structural usage
    - inline: only takes up the space of the content itself
        - Used for content
- Semantic tags/structure help with SEO (Search Engine Optimization)
    - Helps locate within google search
    - Enables other developers to easily identify parts of the HTML 
- `<head>`
    - meta data
    - dependencies (Java/CSS) `<link>`
- `<body>` is where the content is shown
- http://placehold.it/dimensionxdimension/
- `&copy;` creates a copyright


## CSS
### Ch 10. Introducing CSS
`font-family: Arial` this a declaration
- a 'declaration' contains 2 parts
  1. Property - indicate aspects of the elements you want to change.
  2. Value - specify the settings you want to use for the chosen properties

- Multile ways to use CSS:
  1. Inline
  2. Internal
  3. External (most popular and most effective)

#### Selectors
- `color:blue !important;` !important will take precedence over all other selectors
- `p#intro {}` is more specific to a paragraph with a id

### Helpful tips
- ** use `<link rel="stylesheet" href="style.css">` to allow access to the CSS page you want to import**
- For the body/overall width of your page, use at least a 960 (previous standard) or 1024 is also good because it is easily divisible between other resolution
- `margin: auto` centers the content within the container
- `text-align: center` centers text
- `max-width: 960px;` is also good to add
- for lists and nav bars
    - `list-style-type: none`
    - `display: inline`
- use `border-radius: 100px` on borders and images to make them circular
- `clear: both` after `float: left | right`
- make sure to choose the correct selector `<a>` when removing underline properties from links
    - `text-decoration: none`
- HERO image    
    - all images start off as inline elements. Make sure you set your HERO pictures as a `display:block` so that it has it's own line
    - `margin: auto` to center within the body
- `&copy;` adds a copyright symbol
- You can create a list of images by putting an `<a href>` link inside a `li` tag

## JavaScript
### Ch 2. Text
- **`<script src="app.ks"></script> ` to allow access to the JavaScript page you want to import**
- A script is a series of instructions that a computer can follow one-by-one.
- Variables are used to store information for later use

#### Arrays
- special type of variable thats stores a **list** of variables
- can create arrays in 2 different ways:
    - `var list1 = ['a', 'b', 'c']` array literal
    - `var list2 = new Array(1, 2, 3)`
- `array.length` returns total number of items in the array

#### Expressions
- evaluates into a single value.
1. expressions that just assigns a value to a variable
2. expressions that use two or more values to return a single value

- AND = &&
- OR = ||
- Arithmetic: basic math
- String concatation: adding 1 or more strings together to form 1 string

### Ch 4. Decisions and Loops
- Scripts often need to behave differently depending upon how user interacts with web pages

- There are 2 componentes in making a decision:
  1. Evaluation of a condition
    - In order to make a decision,your code checkes the current status of the script. This is commonly done by comparing two values using a comparison operator which returns a True or False value
  2. Conditional statements: if/then/else
  
- a comparison operator usually contains 2 operands and a comparison operator: `(score >= pass)`
  - `var comparison = (score1 + score2) > (highScore1 + highScore2);` will display a True or False
  
 - **AND** statement `((2 < 4) && (3 >= 2))` 
  - if **both** expressions evaluate to true, then the expression returns true
  - if just **one** of these returns false, then the expression will return false
  - **false** && anything: there is no reason in continuing to determine the result because **both** have to be true
  
 - **OR** statement `((2 < 4) || (3 > 5))`
  - if **either** expression evaluates to true, then the expression returns true
  - **both** have to return false in order to return false.
  - **true** || anything : there is no reason in continuting because **one** expression evaluates to true
  
 - logical not `!(2 < 1)` operator takes a single boolean value and inverts it


#### Comparison and logical operators

##### for and while loops
- **for**: if you need to run a **specific** number of times, use a for-loop (this is the most common loop).
  - utilizes a **counter** to tell how many times the loop should run
- **while**: use a while loop if you **do not know** how many times the code should run.
  - the condition here can be something other than a counter, and the code will continue to loop for as long as the condition is true.
- **do while**: same as the while loop, will ALWAYS run what is inside the curly braces at least once

##### for loop
- the for loop _condition_ is made up of 3 statements: `for (var i = 0; i < 10; i++)
  1. initialization: acts as a counter `var i = 0`
  2. condition: the loop should continue to run until the counter reaches a specific number `i < 10`
  3. update: every time the loop has run the statements in the curly braces, it adds one to the counter `i++

#### if statesments
- if statements evaluate or checks a condition. If the condition evaluates to true, any statements in the subsequent code block are executed.

- if, else if, else if, else.

## Website tips
- Start your website with a wire frame
- Build code as clean and organized as possible
    - Utilize proper semantics
- Collaboration is key to becoming a successful designer

## Refresher

- GIT is VCS locally
- Github uses GIT technology
    - Stores/backups documents and files online and allows a group of programmers to collaborate on projects
- Process of GIT:
    1. git clone
    2. mkdir if you have to
    3. touch if you have to
    4. git add filename
    5. git status
    6. git push origin master
    7. git status


## Reflection
  
The studying before hand really did pay off. I felt confident on the topic of HTML , CSS and JavaScript.
Example
1. Header
    - Banner
    - Nav bar
2. Main
    - Hero
3. Footer
    - &copy;