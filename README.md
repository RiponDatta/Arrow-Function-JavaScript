# Arrow Function JavaScript

## Named function
```
function sum (x, y) {
    return x + y;
}
console.log(sum(2, 3));
```
## Anonymous function
```
var sum1 = function (x, y) {
    return x + y;
}
console.log(sum1(2, 3));
```
## Arrow function structure
(parameters) => {statements}

## Arrow function
```
var asum = (x, y)  => x + y;

console.log(asum(2, 3));

var asum1 = x  => {
    x = x + 10;
    return x;
}

console.log(asum1(2));
```
## Arrow function with object literal
```
var myObject = (firstName, lastName) => (
    {
        firstName: firstName,
        lastName: lastName,
        fullName: firstName + ' ' + lastName
    });

console.log(myObject("Ripon", "Datta"));
```
