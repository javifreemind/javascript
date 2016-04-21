# Events

HTML events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can "react" on these events.

Event         | Description
------------- | -------------
onchange      | An HTML element has been changed
onclick       | The user clicks an HTML element
onmouseover   | The user moves the mouse over an HTML element
onmouseout    | The user moves the mouse away from an HTML element
onkeydown     | The user pushes a keyboard key
onload        | The browser has finished loading the page  

ELEMENT.addEventListener(EVENT, CODE);

```javascript
myElem.addEventListener("click", myFunction);       
myElem.addEventListener("click", getClickPosition);
myElem.addEventListener("click", function(){...});
```
Event handler: normal function

```javascript
function myFunction()
{
	...
}
```

Event handler: with the event parameter

```javascript
function getClickPosition(e)
{
	var xPosition = e.clientX;
	var yPosition = e.clientY;
}
```