## Domain Modeling
- Object-oriented model: an entity that stores data in properties and encapsulates behaviors in methods
- a model describes the various entities, attributes, behaviors, and constraints that describe the problem domain as a whole
1. new keyword instantiates (creates) an object
2. constructors function initialize properties inside that object using `this.` variable
3. the object is stored in a variable for later use

<!-- referenced  comments section of: https://www.youtube.com/watch?v=4jb4AYEyhRc&ab_channel=TheNetNinja-->
- By using prototype property on the constructor function,  Prototype will enable us to easily define methods to all instances of the instances while saving memory. What's great is that the method will be applied to the prototype of the object, so it is only stored in the memory once, because objects coming from the same constructor point to one common prototype object. In addition to that, all instances of userOne or userTwo will have access to that method. Thus, we will be able to save quite a good amount of memory compared to the constructor approach. Apart from low memory usage, the prototype approach is obviously faster in execution when creating new object instances since no time is spent on re-declaring any methods.
- constructor first looks in constructor object, then looks in `__proto__`object
- takes longer to locate a method on prototype object, but is considered best practice
- "When a prototype is shared between two or more objects, those objects executre the same code when the generateRandom() method is called

<!-- tips referenced  https://github.com/codefellows/domain_modeling#domain-modeling-->
1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the new keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the this variable within methods so you can access the object's properties and methods from inside.

## HTML
### Ch 6. Tables
- represents information in a grid format
- `<table>` container
- `<th>` should be used as the most outer rows
  - th styles font with some CSS but should be styled wholly on css
- `<tr>` starts a row
- `<td>` opens a new cell
  - attribute `rowspan="#" and colspan="#"`
- `<thead>`
- `<tbody>`
- `<tfoot>`

## JavaScript
### Ch 3. Functions, Methods, and Objects

- object constructors can use a function for creating objects
- use of `this` keyword pertains to the new object you instantiate
- arrays are objects that utilize index number
- you can put objects in arrays and arrays in objects
- built in objects act as a toolkid for creatign interactive web pages
- an object model is a group of objects, each of which represent related things from the real world. together, they form a model of something larger
- 3 groups of build in objects
  1. Browser
    - ```
      window. document. history. location. navigator. screen.
      ```
  2. Document
    - `document.`
    - topmost object in document object and representes the page as a whole
  3. Global JavaScript
   - date math regex
   - strings numbers boolean
   - `hotel.toUpperCase()`
   - `Math.PI` returns value of pi
- `var variableName = new Date()`
  - Date is a object constructor and a new date is instantiated