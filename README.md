# Task-Practice Content


- Discussion in window
  - [Opener](#Opener)
  - [Console](#Console)
  - [Document](#Document)
    
 # The Table of Content in Function
- [Function](#Function)



### Opener
Discussion the window The window interface represents the Dom documents. window object supported all browsers. it represents the browser window.
The `window.closed` property indecats which window closed or open. it returns voolean value. Example JS
```js
if(window.opener && !window.opener.closed){
window.opener.location.href = "www.googletranslate.com"
}
```

 ### Console

The `console ` object shows browser debugging console. and this access is globally. the console has a different instance method. For Example: 
```js
console.log (For general output)
console.dir (displaying specfied js object)
console.count (showing the number of log how many line has been called)
```


### Document

  The `document` return the reference of the window. that's why we are showing title etc. For Example:

```js
  console.log(window.document.title)
```

### Function
The function object provides methods of functions. Mainly function use a organized to reusable code in a block quotation code and perform a single action. Different way to write function. Here i explained five ways to write a function. These are
```js
i. Function Declaration
ii. Function Expression
iii. Shorthand Method
iv. with Constructors
v. Arrow Functions

```
- Function Declaration
  
A Most common way to define a function in javascript. function declare includes declaring function keyword function name parameter brackets and pair curly brackets. For Example -

```js
function isEqual (num){
return num === 5;
}
```

- Function Expression
  
Function expressions are cloesly same as the function declaration. using var, let, const to follow a function. One of the main advantages of the function expression easy to debugging a function. when a function faces to  an error. For Example -

```js
  const Equal = function (a,b){
  if(a===b){
  console.log("All number is equal")
  }
  }
```

- Shorthand function
  
Shorthand syntax are introduced with ES2015. it is quite similar the getter and setter. shorthand function easier to read. For Example - 

```js
const obj = {
  items = [],
  get(index){
  return this.items[index]
},
      set(...elements){
        return this.items.push(...elements)
      }
}
items.add("foo", "bar")
items.get()
```

- Constructors

In Javascript constructor is a function create a object. Once of the most important part is the `this` and `new` keyword . here this keyword use when a object is created. and this object refer this. For Example -

```js
function shoes(size,color){
  this.size = size;
  this.color = color;
}

const newPerson  = new shoes(37, 'blue');
console.log(newPerson.size)
console.log(newPerson.color)

```

- Arrow Function

Arrow Function is one of the most important and usages features introduced on ES6. It is allows to developers to create a function and cleaner way to contrary to the function declaration. For Example - 

```js

let sum = (a,b)=> a+b

function sum(a,b){
return a+b
}

```

In this article, we learn the function of writing way. There are more ways to writing js function.


