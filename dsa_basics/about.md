# Questions to solve 

## adding two integers

## Concatination (Relation between integer and string)
refers as adding an int and a string value in such a way that there type obtained is string
```javascript
    let a = 12;
    let b = "14"
    console.log(a+b) // 1214
    //type will be string
```

## sum of string and int
```javascript
let a = 10;
let b = 20;

console.log("The sum of a+b is: "+ a + b); // The sum of a+b is: 1020

```

## type Coersion
when calculation is done based on the operator
```javascript
console.log("1"+1) //11
console.log("1" - 1) // 0
console.log("1" * 1) // 1
console.log("1" / 1) // 1
```

## Accept and print the answer
```javascript
let age = prompt("Enter your age:");
console.log(age);
console.log(typeof(age)); //string
```
to change the type of prompt to number/int we do:
```javascript
let age = Number(prompt("enter your age")) // now the type will be number/int

```