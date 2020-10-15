## JavaScript
### Ch 3. Object Literals
- objects have properties and methods
- 
```
var objectName = {
  string: 'hi',
  number: 6,
  array: ['cat', 'dog'],
  boolean: true,
  methods: function() {
    return this.number
  }
};
```
- Ways to call using dot notation:
```
objectName.number
objectName.array[0]
objectName.methods()
```


### Ch 5. Document Object Model
- DOM specifies how browsers should create a model of an HTML page
- each object represents a different part of the page loaded
  - you will be able to updated contents of a webpage using selecting proper DOM elements and using Javascript
- 4 types of nodes:
  1. Document
  2. Element
  3. Attribute
  4. Text

#### Accessing Elements
- Individual Nodes
```
document.getElementById('id')
document.querySelector('css selector')[#]
```
- Multiple Nodes:  returns a **NODELIST**
  - acts like an array, access values using array[#] notation
```
document.getElementsByClassName('class name')[#]
document.getElementsByTagName('tag name')[#]
document.querySelectorAll('css selector')[#]
```
- Traversing Between Element Nodes
`.parentNode`
`.previousSibling`
`.nextSibling` 
`.previousElementSibling` skips text nodes
`.nextElementSibling` skips text nodes
`.firstChild` must be on parent node
`.lastChild` must be on parent node


#### Working with Elements
- Access/update text nodes
  - select li element
  - use firstChild property
  - use text nodes ONLY property `.nodeValue`
- working with HTML content
  - `.innerHTML`
  - `.textContent`
- access or update attribute values
```
.hasAttribute('attribute name')
.getAttribute('attribute name')
.setAttribute('attribute name', 'value)
.removeAttribute('attribute name')
.className = 
```

- STEPS
  1. choose inital node
  2. decide if you want to traverse the DOM
  3. choose how you want to change /remove that node

- creating new element/node
  1. create new element node
    - `document.createElement('tag')`
  2. create text node
    - `document.createTextNode('words')`
  3. append new element/node to DOM (typically parent)
    - `.appendChild(variable)`;

- removing element/node
  1. set variable to node you want to delete
  2. set another variable to the parent of that node
    - `.removeChild(variable of the node you want to delete)`