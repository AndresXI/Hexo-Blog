---
title: The Execution Context
date: 2018-11-27 18:26:27
tags: execution context 
---

JavaScript is a dynamic and versatile language after all it can be used both on the frontend and the backend. You can create web apps, server backends, desktop apps, and mobile apps. That's why JavaScript is one of my favorite languages (it's always on the top 3 &#128515;). 

Although javaScript is pretty amazing it is a special breed on its own. JavaScript does not behave like other programming languages (Java, C++, Python, C# etc.). It is wierd. Like really weird. Well, we do have to understand that when we run javaScript code we run it on a widow in the browser. So what happens when we start executing code with javaScript? say hello to...
<br />

## The Global Execution Context
Whenever code is run by javaScript at the global level (meaning not inside a function) it is run inside an execution context. It is basically a wrapper that the javaScript engine creates to wrap your code into an execution context. When we look at a program what we are actually looking at is an execution context being created and run. 

This global execution context is our base execution context, it is accessible everywhere inside our code. So what does it do? First we have to understand that is it created by the javaScript engine, we never write any code to created it. It is part of the Javascript language. It creates two things for us:

- A global Object: A collection of value name pairs. It is always part of the window. Each window has its own execution context. 

- The keyword 'this': A special keyword that has been confusing developers since the creation of the universe

Here we have a window opened in the browser with an empty javaScript file and when we type window we get: 