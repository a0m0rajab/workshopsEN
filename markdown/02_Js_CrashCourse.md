
# Javascript Crash Course 

{{quote {author: "Prophet Muhammad"}

"When a man dies, his deeds come to an end except for three things: Sadaqah Jariyah (ceaseless charity); a knowledge which is beneficial, or a virtuous descendant who prays for him (for the deceased)."

quote}}

- [Javascript Crash Course](#javascript-crash-course)
  - [Printing On Screen](#printing-on-screen)
  - [Variables](#variables)
    - [Variables Types](#variables-types)
  - [Mathematics Symbols](#mathematics-symbols)
  - [Assignment operators](#assignment-operators)
  - [Increment & decrement](#increment--decrement)
  - [Data Types](#data-types)
    - [Strings/Texts](#stringstexts)
  - [Conditions](#conditions)
    - [Comparing statements](#comparing-statements)
    - [Comparing shortcut](#comparing-shortcut)
    - [Logical](#logical)
    - [Binary](#binary)
    - [Switch](#switch)
  - [Loops](#loops)
  - [Data Structures](#data-structures)
  - [Arrays](#arrays)
    - [For each element](#for-each-element)
    - [For Of](#for-of)
    - [For in](#for-in)
  - [Maps](#maps)
  - [Sets](#sets)
  - [Other Assignment](#other-assignment)
  - [Functions](#functions)
  - [Built-in libraries](#built-in-libraries)
    - [Math](#math)
    - [Date](#date)
    - [built-in functions](#built-in-functions)
    - [Market Example](#market-example)
  - [Practice](#practice)
    - [Prime Number](#prime-number)
  - [Classes](#classes)
  - [Error types and reviewing (debugging)](#error-types-and-reviewing-debugging)
  - [Modules](#modules)
  - [Generators](#generators)
  - [Promises](#promises)
  - [Extras](#extras)

## Printing On Screen

```
console.log(34);
```

## Variables

```
x + y = 5 
x = 1 
y = ? 
```

```
x + y + z = 25
x = 10 
z =  y + y  
```

### Variables Types

```
let 
var
const
```

```
const x = 10; 
const y = 14;
x = 11;
console.log(x) 
```

```
let x = 2, y = 1;
console.log(x+y);
let z= 5;
let h= 20;
console.log(h/z)
```

```
var x = 10 
var y = 20 
console.log(x*y)
```
## Mathematics Symbols 


```
+
-
/
*
%
**
```

```
console.log(1+2)
console.log(4*5)
```


## Assignment operators

```
=
*=
/=
%=
+=
-=
```


```
let x =1
x += 1
console.log(x) 
x *= 4
```

Logical 

```
<<=
>>=
&= And
^= Exor 
|= Or
```
```
let x = 1 
console.log(x)
x &= 0
console.log(x)
```
## Increment & decrement

```
A++
A--
++A
--A
```

```
let x = 0
console.log(x)
console.log(x++)
console.log(++x)
```


## Data Types

```
undefined 
Boolean // True, False  
String   
Object
Function
Null    
```

```
let h = undefined
let t = true 
let x = "Hello"
let n = Null
let b = function (x) {return x*2}
let ob = {h:1,b:2}
```

Changing between types
The advantages of each type

```
Number // -(2^53 − 1) and 2^53 − 1).
+Infinity, -Infinity, and NaN
```

```
let x = 2 
let b = 0/0
let mi= -100/0
let pl= 100/0
```

```
BigInt
```

```
console.log(Number.MAX_VALUE)
// console.log(BigInt(Number.MAX_VALUE))
```

```
let x = 42;
console.log(typeof x)    
x   = 'bar'; 
x   = true;  
```

```
let x= "Hello";
console.log(result)
let y= "world"
console.log(x+y)
let z= 1;
console.log(x+y+z)
```

[Data Types](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)

### Strings/Texts

```
const string1 = "A string";
const string2 = 'Also a string';
const string3 = `another string`;
```

```
const string1 = `${1+2} = 3 , 1+1 = 2`;
```

## Conditions

```
if
ifelse 
switch
```

### Comparing statements

```
< 
<= 
>
>=
==
!=
```

```
console.log(1 < 3 )
```


```
let x= 2, y= 4;
if(x < y ){

}

if (x > y ){

}
```

```
if(){}
else{}
```

```
if(){}
else if(){}
else()
``` 

### Comparing shortcut

```
(condition)?ifTrue:ifFalse;
```

```
a = (4 > 5 )? true: false; 
console.log(a)
```

### Logical

```
&&
||
```

```
let x= (false&&true&&false)
console.log(x)
```

```
true,true
false,false
true,false
```

### Binary

```
&
|
^
```

Binary Numbers 

### Switch

```
let name = "Ahmad"
switch(){
    case "Ahmad":
          console.log("Ahmad is a loyal person")
        break;
    case "Sam":
          console.log("Sam is not home.")
        break; 
    case "Jhon":
          console.log("Jhon is still outside.")
        break;
    default:
      console.log("The name is not defined")

}
```
```
```

## Loops

```
for(){}
while(){}
do{}while()
```

```
break
continue
Label
```

```
for(let i=0; i< 10; i++){
    console.log(i)
}
```

```
let result =0;
for(let i=1; i< 20; i=i+1){
    if(x%2 == 0 ){
      console.log(i)
    }
}
console.log(result)
```

```
let x=0
let result1=0;
while(x < 150 ){
    if(x%5 == 0){
      x++
    }
}
console.log(x)
```

```
let result = 0;
for(let i = 0 ; i < 100 ; i ++ ){
  result += i;
}
console.log(result)
```

```
let n = 100
console.log((n*(n+1))/2)
```


## Data Structures

```
Array:Index
Map:Key-Value 
Set:Only one.
```

## Arrays

```
let ulama = ["ibn haytham" , "omar khayyam" , "al-battani" , "Al-harezmi" , "ibn-sina" , "ibn-nafis"]
console.log(ulama[1])
console.log(ulama.length)
```


### For each element

```
ForEach
```

```
let ulama = ["ibn haytham" , "omar khayyam" , "al-battani" , "Al-harezmi" , "ibn-sina" , "ibn-nafis"]
ulama.forEach(element => console.log(element));
```

### For Of

```
for..of
```

```
const Books = ['Book of Optics', 'Rubaiyat', `Kitab Al-Zij al-Sabi’`, "Algebra", `The Canon of Medicine` , `Al-Shamil fi al-Tibb`];
for (const element of Books) {
  console.log(element);
}
```
### For in

```
for..in
```

```
const scholarAndArea = { `ibn haytham`: `Optics`, `al-kharezmi`: `Algebra`, `ibn-sina`: `Medics` };

for (const property in scholarAndArea) {
  console.log(`${property}: ${scholarAndAreat[property]}`);
}
```

## Maps

```
let cities = new Map()
```

```
let cities = new Map()
cities.set('Sudan', "Khartom")
cities.has('Sudan') // true
cities.get('Jordan') // undefined
cities.set('Jordan', "Oman")
cities.get('Jordan') // "Oman"
cities.delete('Syria') // false
cities.delete('Sudan') // true
console.log(cities.size) // 1
```


## Sets

```
let myBooks = new Set()
```

```
let myBooks = new Set()
mySet.add("Sherlock")
mySet.add("Tantawi")
mySet.add("ibn Battuta")
mySet.add("Ali Omari")
mySet.add("Sherlock")
mySet.has("Sherlock")
mySet.delete("Sherlock")
mySet.size
```

## Other Assignment

```
[a, b] = [1, 2]
{a, b} = {a:1, b:2}
```

## Functions

```
function multiple2(x){
    return x*2
}

function halfOf(x){
    return x/2
}

const scholarAndArea = { `ibn haytham`: `Optics`, `al-kharezmi`: `Algebra`, `ibn-sina`: `Medics` };

function find(field,map){
for (const property in scholarAndArea) {
  if(scholarAndAreat[property] == field)
    return property
}
}
```

```
function multiplier(x){
    return function (y){
        return y * x
    }
}
```

## Built-in libraries


```
Math
Date
```


### Math 

```
function degToRad(degrees) {
  return Number.parseInt(degrees * (Math.PI / 180));
};

function radToDeg(rad) {
  return Number.parseInt(rad / (Math.PI / 180));
};

console.log(
Math.cos(degToRad(Math.PI)),
Math.sin(degToRad(Math.PI)),
Math.PI
)
```

```
var a, x, y;
var r = 10;

with (Math) {
  a = PI * r * r;
  x = r * cos(PI);
  y = r * sin(PI / 2);
}

console.log(a,x,y)
```

### Date

```
let h = new Date
console.log(h)
```

### built-in functions

```
getDate()
getDay()
getFullYear()
getHours()
getMilliseconds()
getMinutes()
getMonth()
getSeconds()
```


### Market Example

What is algorithms? 

Date checker algorithms
```{lang: "java"}
Go to market
pick a product 
Check date
Write the number of outdated products
Do that for all products.
```

```
let avai=[
2010,
2015,
2000,
2021,
2100,
1914,
2023,
1453
]
let year = new Date().getFullYear()
let count = 0;
for (let i = 0; i < avai.length ; i= i+1){
if(avai[i] <  year){
count ++ }
}
console.log(count)

```

## Practice

### Prime Number

{{index "triangle (exercise)"}}

Write a function that check if the number is prime or not. 

{{index [string, length]}}


{{if interactive

```
// Your program here.
```
if}}

{{hint

{{index "triangle (exercise)"}}

You can think about the rule of prime number which its a number that can not be divided but on itself and one. To check that we can use the Remainder symbol (%) and see if there is any remainder. 

You can use the [Loops](#loops) to check all numbers from 2 till the needed number and check if the reminder is zero - whcih means it accept it as divider, if that is the case then the number is not prime otherwise it's prime.

hint}}


## Classes

```
Class
```

```
class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
    // Getter
  get area() {
    return this.calcArea();
  }
  // Method
  calcArea() {
    return this.height * this.width;
  }
}
let x = new Rectangle(10,20)
console.log(x.area())
```

```
class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }
    // Getter
  get area() {
    return this.calcArea();
  }
  // Method
  calcArea() {
    return this.height * this.width;
  }
}

Class Square extends Rectangle{
    constructor(size){
        super(size,size)
    }
}
```

## Error types and reviewing (debugging)

1- Logical Error

2- Syntax Errore

3- Runtime Errors


```
debugger
try...catch
throw
Error
```

```
nonExistentFunction();
```

```
try {
  nonExistentFunction();
} catch (error) {
  console.error(error);
}
```

```
try {
  throw "The number is not wrttien yet."
} catch (error) {
  console.error(error);
}
```

```
let x = new Error("Learn from your mistakes")
```


```
class CustomError extends Error {
  constructor(place, ...params) {
    super(...params)
    if (Error.captureStackTrace) {
      Error.captureStackTrace(this, CustomError)
    }
    this.name = 'CustomError'
    this.place = place
    this.date = new Date()
  }
}

try {
  throw new CustomError('Erorr location', 'Try again!')
} catch(e) {
  console.error(e.name)    //CustomError
  console.error(e.place)     
  console.error(e.message) 
  console.error(e.stack)   
}
```

## Modules

type="module"

```
export
import
```

```
export const name = 'square';

export function draw( length, x, y, color) {
  return {
    length: length,
    x: x,
    y: y,
    color: color
  };
}
```

```
export { name, draw, reportArea, reportPerimeter };
```

```
import { name, draw, reportArea, reportPerimeter } from './modules/square.js';
```

## Generators

```
Generator
GeneratorFunction
AsyncGeneratorFunction
AsyncGenerator
```

```
function* generator() {
  yield 1;
  yield 2;
  yield 3;
}
const gen = generator(); 
console.log(gen.next().value); 
console.log(generator().next().value); 
console.log(generator().next().value); 
```

```
function* infinite() {
    let index = 0;

    while (true) {
        yield index++;
    }
}

const generator = infinite(); 
console.log(generator.next().value); 
console.log(generator.next().value); 
console.log(generator.next().value); 
```

## Promises

```
Promise
AsyncFunction
```

```
const CallServer = new Promise((resolve, reject) => {
  setTimeout(() => {
    resolve('You have done.');
  }, 300);
});

CallServer.then((value) => {
  console.log(value);
});

console.log(CallServer);
```

```
const CallServer = new Promise((resolve, reject) => {
  setTimeout(() => {
    resolve('You have done.');
  }, 300);
});

async function asyncCall() {
  console.log('calling');
  const result = await CallServer();
  console.log(result);
}

asyncCall()
```


## Extras

[Web reference](https://developer.mozilla.org/en-US/)

[Data types](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)

[JS reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)