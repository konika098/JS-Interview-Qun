# JS  Basic Interview Question
## 1. What is JavaScript?
**Ans:** JavaScript is a high-level, interpreted programming language primarily used to make web pages interactive. It enables dynamic content and client-side scripting in web browsers.
## 2. What are the key features of JavaScript?
**Ans:** Key features of JavaScript include:
--Dynamic typing,
--Prototype-based object-orientation,
--First-class functions,
--Closures,
--Asynchronous programming with callbacks (and Promises/Async-Await in modern JS)
## 3. What is the difference between let, const, and var in JavaScript?
**Ans:** **var** is function-scoped and can be redeclared.
**let** is block-scoped and can be reassigned.
**const** is block-scoped and cannot be reassigned after declaration.
## 4. Explain the concept of closures in JavaScript.
**Ans:** Closures refer to the ability of a function to remember and access its lexical scope even when it's executed outside that scope. This allows functions to encapsulate and "close over" variables from their outer scope.
## 5. What is the event loop in JavaScript?
**Ans:** The event loop is a mechanism in JavaScript that helps manage the execution of multiple code paths by handling asynchronous operations. It consists of a call stack, a callback queue, and an event loop. Asynchronous tasks, such as setTimeout or AJAX requests, are placed in the callback queue and executed in the order they are added, once the call stack is empty.
## 6. Explain the concept of prototypal inheritance in JavaScript.
**Ans:** JavaScript uses prototypal inheritance, where objects can inherit properties and methods from other objects. Each object has a prototype chain, and if a property or method is not found on the object itself, JavaScript looks up the prototype chain until it finds the property or reaches the end of the chain.
## 7. What is the purpose of 'this' keyword in JavaScript?
**Ans:** The 'this' keyword in JavaScript refers to the current execution context. Its value depends on how a function is called. In a method, it refers to the object the method was called on. In a regular function, it refers to the global object (window in browsers) or is undefined in strict mode.
## 8. What is the difference between == and === in JavaScript?
**Ans:** == is the equality operator, which performs type coercion if the operands are of different types. === is the strict equality operator, which checks both value and type without type coercion.
## 9 . Explain the concept of hoisting in JavaScript.
**Ans:** Hoisting is a JavaScript behavior where variable and function declarations are moved to the top of their containing scope during compilation. However, only the declarations are hoisted, not the initializations.
## 10 . What is the purpose of the bind method in JavaScript?
**Ans:** The bind method is used to create a new function with a specified value and, optionally, initial arguments. It is often used to bind a function to a specific context, ensuring that this inside the function refers to the desired object.
