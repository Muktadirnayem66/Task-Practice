# Task-Practice
Task - Practice

- # Discussion in window
  - [opener](#opener)
  - [console](#console)
  - [document](#document)


### opener
Discussion the window The window interface represents the Dom documents. window object supported all browsers. it represents the browser window.
The `window.closed` property indecats which window closed or open. it returns voolean value. Example JS
```js
if(window.opener && !window.opener.closed){
window.opener.location.href = "www.googletranslate.com"
}
```

 ### console

The `console ` object shows browser debugging console. and this access is globally. the console has a different instance method. For Example: 
```js
console.log (For general output)
console.dir (displaying specfied js object)
console.count (showing the number of log how many line has been called)
```


### document

  The `document` return the reference of the window. that's why we are showing title etc. For Example:

```js
  console.log(window.document.title)
```
