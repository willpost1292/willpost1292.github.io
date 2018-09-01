---
layout: essay
type: essay
title: JavaScript: A First Encounter
# All dates must be YYYY-MM-DD format!
date: 2018-08-30
labels:
  - Javascript
  - Software
  - Web Developement
  - Learning Experience
---

<img class = "ui medium left floated image" src="../images/Diving-Board.jpg">

  JavaScript is the native programming language of the internet. So when I first found out that we were going to learn JavaScript for part of my Software Engineering class, I was definitely excited. Having just completed the first JavaScript learning module for our class, I wanted to share my first impressions with the language, and what I hope to learn as the class progresses. 

## Background

  I am currently a junior in the B.S in Computer Science program at the University of Hawaii, Manoa. The programming languages we have used in my classes so far have mostly consisted of Java, C, and C++. For my personal projects I mostly stick the Python programming language. I have experimented with JavaScript a little bit, but I would consider myself a complete newbie.

## What is JavaScript?

  Javascript is a very high level, interpreted programming language that uses dynamic typing. What does that mean exactly? And how does these paradimes compare to other languages?

## Very High Level

  Most programming language we use today are “high level”. This simply means that the language uses enough abstraction so that one can write system dependent code. C is a high level language, while an assembly language is not. But JavaScript is often considered to be a“very high” level programming language, because the language uses even higher levels of abstractions. These abstractions allow for rapid development, because a developer doesn’t have to worry about lower level issues like garbage collection.

A "Hello World" program written in JavaScript displays this abstraction in action:

```javascript
console.log("Hello World");
```
So Simple! No need for import statements or main functions.

## Interpreted

 JavaScript is an interpreted programming language. This means that each line of code in a is “interpreted” at runtime, and does not need to be compiled to machine code before being executed. This can be contrasted with a language like C, which needs to be compiled before being executed. This is a bit of a misnomer. Programming language are just that: languages. It’s up to a compiler or an interpreter to translate the code to make it something a computer can execute. This means that many languages that are considered interpreted can actually be compiled, and vise-versa. An interpreted language is just typically interpreted. Some advantages of interpreting a language is that the code becomes very portable, and the type of variables can be determined at runtime. Some disadvantages of interpreted code is that execution is typically much slower than compiled code, and errors often pop up at runtime.
 
 ## Dynamic Typing
  Dynamically typed language determine the type of a variable at runtime. This is a common feature of interpreted languages. This allows for flexible and concise code. A disadvantage of dynamic typing is that it’s sometimes difficult to keep track what type a variable should be, such as what type of variable is expected in a function argument. 
 
Heres a personally legal function in JavaScript:
```javascript
function divide(dividend, divisor) {
  if(divisor == 0) return "Cannot divide by zero!";
  return dividend / divisor
  }
  
  divide(4/2) //returns 2
  divide(4/0) //returns "Cannot divide by zero!"
  ```
## Multi-pardigm
  JavaScript is a multi-paradigm language, which means it supports multiple programming design strategies, such as object oriented and functional. While the object oriented paradigm has been king for a while now, more and more developers are adopting a more functional approach. Functional programming breaks everything down into pure mathematical functions. A pure mathematical function simply takes arguments and returns a value.  

heres an example of a functional vs. a non-functional approach to a problem.

non-functional approach:
```javascript
let aList = [1,2,3]

function doubleList(list) {
  for(let i=0; i < list.length; i++) {
    list[i] = list[i] * 2; //value is edited in place 
  }
  return; //no value is returned
}
  
doubleList(aList); //the state of the var is changed 
```
Here's a more functional approach to the problem:

```javascript
const aList = [1,2,3]; 

function doubleList(list) {
  const newList = []
  
  for(let i=0; i < list.length; i++) {
    newList.push(list[i]);
  }
  
  return newList;
  
const newList = newList;
```
  Now there are way better ways to do this, but the C style of the for loop was used because that's what most people are familiar with. Also it is worth noting that this is not a purely functional style. In purely functional languages, arrays are immutable, while in JavaScript their values can be changed in place (Even with a const declaration). 

  A crucial element of functional programming is high order functions. A high order function is a function that takes either takes a function as an argument or returns a function. This allows function composition to solve problems in a flexible manner. 
  
## Overall Impressions

  JavaScript seems like an awesome language to develop with. It’s dynamic features and functional capabilities makes programming make writing in JavaScript a blast. The language does have its pitfalls and weird idiosyncrasies, but it more then makes up for it with it’s flexibility. 
  
## Looking Ahead

  JavaScript is definitely a different beast compared to the languages I’ve worked with. But it’s important for developers to get exposure to different programming concepts in order to broaden their perspective on how to solve a problem. I look forward to learn more about the language and to develop projects with JavaScript in the future. 



  

 
  
