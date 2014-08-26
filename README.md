# JSQuiz

JavaScript Test.  Clone this REPO and provide your answers.

### Tell me about strings in JavaScript
> your answer

### People say that almost everything in JavaScript is an object. What things are not objects?
> your answer

### How can errors be handled in JavaScript?
> your answer

### Why use strict mode?
> your answer

### Code an example of a for in loop?
> your answer

### Code an example of an object
> your answer

### Sort the following array by value:
```
var ar = [
    {text:"one", value:1},
    {text:"four", value:4},
    {text:"two", value:2},
    {text:"three", value:3},
    {text:"six", value:6}
];
```
> your answer

### In this code what is the resulting value of `a`?
```
    var a=1;
    delete a;
```    
> your answer

### In this code what is the resulting value of 'obj.x'?
```
	var obj = {x: 1};
	delete obj.x;
```
> your answer

### Write a program which given a list of name returns the total number of unique names.
#### For example: ['bob','jill','bill','bob','sue','jill'], should return 4.
> your answer

### Write an example of a self executing JavaScript module.
#### Also known as an iife (Immediately-invoked function expression)
> your answer

### What does the following code do?

```
function(array, obj, iterator, context) {
    iterator = lookupIterator(iterator);
    var value = iterator.call(context, obj);
    var low = 0, high = array.length;
    while (low < high) {
      var mid = (low + high) >>> 1;
      iterator.call(context, array[mid]) < value ? low = mid + 1 : high = mid;
    }
    return low;
  };
```
> your answer

### In the example above what is the role of: >>> 1
> your answer

#### What value will be displayed in the alert?

```
function() {
    if(true) {
        var a = 5;
    }
    alert(a);
}
```
> your answer

### What will alert display in this example?

```
function first() {
    window.a = 3;
}

function second() {
    alert(a);
}

first();
second();
```
> your answer

### What are the three numbers displayed using the code below?

```
var a = 6;
function test() {
    var a = 7;
    function again() {
        var a = 8;
        alert(a);
    }
    again();
    alert(a);
}
test();
​alert(a);​
```
> your answer

### What is the output below
```
function getFunc() {
    var a = 7;
    return function(b) {
        alert(a+b);
    }
}
var f = getFunc();
f(5);
```
> your answer
