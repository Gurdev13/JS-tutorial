# JAVASCRIPT

## Basics
- Javascript is very liberal (very less error throwing)
- it is used to make webpages interactive.
- ***NodeJs***  In order to use javascript outside the browser
- ***Raplit*** Web application for writing Javascript and many other languages online


## Variables in JavaScript
- var is defined globally and can be declared again and again.
- let is defined for or between the particular block only and is prefered, can't be redeclared(throws error).  
- const neigther be redeclared nor their values can be changed.  

## Primitive datatypes in js
- We have 7 primitive datatypes
- ***N*** Null (empty)
- ***N*** Number (33)
- ***S*** Symbol ("Anything")
- ***S*** String ("You are a sweet person")
- ***B*** Boolean (True/False)
- ***B*** BigInt (54449)
- ***U*** undefined (=0, intialized)

## Objects or Non-Primitive data types  
- Similar to dictionaries in pyhton.
- Multiple variables can declared in the object block.
- Can look up variables using key

```javascript
const item= {
  "Gurdev":true,
  "sharn":58,
  "harsh":undefined,
  "Taish":"Chhoti Bachi Ho Kya"
}
console.log(item)
``` 
## Operators
1. Arithmetic operators
   - +,-,*,/,**(exponantial),++(increament),--.
2. Comparison operators
   - ==,!=,<,>,===(compare datatypes even),!==,?(condition? true : false)
3. Logical operators
   - =,!

## Conditional Statements
- if,else-if,else

## Loops
- for(intialize; condition; updation)
  ```javascript
  for (let a in object){
    console.log(a) //prints keys of an object
  }
  ```
- for of loop
- ```javascript
  for (let a of object){
    console.log(a) //prints value of object
  }
  ```
- do while loop(executes atleast once)
  ```javascript
  do{
    statement
  }  
  while(condition)

## Functions
- ```javascript
  const name = (parameters) => {
    statements 
  }

## string Templates-Literals(string interpolation)
- Strings are immutable
- ```javascript
  let b1 = "harry"
  let b2 = "garry"
  let sentence = `${b1} is friend of ${b2}`

  b1.toUpperCase()
  b1.toLowerCase()
  b1.slice(0,4)
  b1.replace("har", "par")
  ```

##  Arrays
- muteable, a type of object  
