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
document.getElementById('')
document.querySelector('')
```
- Multiple Nodes
```
document.getElementsByClassName('')
document.getElementsByTagName('')
document.querySelectorAll('')
```
- Traversing Between Element Nodes
.parentNode
.previousSibling
.nextSibling
.firstChild
.lastChild

#### Working with Elements
