# Scope

It only has lexical scope. This means that variables declared inside a block such as an if statement or loop will actually be accessible to the entire enclosing function:

```javascript
function scopeDemo() {
    if (true) {
        var foo = "I know what you did last summer!";   
    }
 
    alert(foo); // totally exists!
}
scopeDemo();
```
