
# Programming Crash Course with JS 

{{quote {author: "prophet muhammad"}

Ask Allah(God) for beneficial knowledge and seek refuge with Allah from knowledge that is of no benefit.

quote}}

## Printing On Screen

```
console.log(34);
```

## Variables


```
let x = 2, y = 1;
console.log(x+y);
let z= 5;
let h= 20;
console.log(h/z)
```

## Controllers

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

## Functions

```
function sum(x,y,z){
    return x+y+z 
}

function average(x,y,z){
    return (x+y+z)/3
}


function smaller(x,y){
    if(x<y){
        return x;
    }else {
        return y
    }
}
```
## Math 

[General Approach](../extras/index.html)

Second Degree Factor

x^2 + 4x + 4 = 0  

```
function delta(a,b,c){
    return Math.sqrt((b*b)-(4*a*c))
}
```
x^2 + 4x + 4 = 0 

```
function quadraticZero(a,b,c){
    return -b/2*a
}

function quadraticMinus(a,b,c){
    return -b/2*a
}

function quadraticPlus(a,b,c){
    return -b/2*a
}
```
## Data Types

```
let x= "Hello";
console.log(result)
let y= "world"
console.log(x+y)
let z= 1;
console.log(x+y+z)
```

## Loops

```
let result =0;
for(let i=5; i< 20; i=i+1){
    result = i + result;
}
console.log(result)

let x=5
let result1=0;
while(x < 20 ){
    console.log(x)
    x=x+5;
}

for(let i=0; i< 10; i++){
    console.log(i)
}
```

## Matrices

```
let x =["a","b","c","d","e","f"]
console.log(x[1])
```
```
let x =["a","b","c","d","e","f"]
console.log(x.length)
```

### Market Example
Choclate algorithm

```{lang: "java"}
Go to Market,
Search for Choclate
Get the choclate 
```

```
let req="Choclate"
let avai=[
"Rice",
"Meat",
"Onion",
"Falafel",
"Carrot",
"Potato",
"Tomato",
"Choclate"
]
for (let i = 0; i < avai.length ; i= i+1){
if(avai[i]==req){
console.log("Get Choclate")
}
}

```

## Ready to use Libraries
Math 

```
console.log(
Math.cos(Math.PI),
Math.sin(Math.PI),
Math.PI
)
```

## Exercise
### Drawing triange

{{index "triangle (exercise)"}}

Write a loop that calls `console.log` seven times to draw the following triangle:


```{lang: null}
#
##
###
####
#####
######
#######
```

{{index [string, length]}}


{{if interactive



```
// Write your program here.
```
if}}

{{hint

{{index "triangle (exercise)"}}

You can start by printing the numbers from 1 to 7 after that you can modify the program.
You can do this by following the loops example in the file.

You can think about the relation between each square and the numbers that we have and add it to the result. To Add square to the base variable you can use this style: (`+= "#"`)

You can check data types in the page as well to find extra information!

hint}}

## Resources
[MDN](https://developer.mozilla.org/en-US/)
