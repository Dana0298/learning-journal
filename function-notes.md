Keywords:

- naming convention: name implies functionality or use one word - camelCase

- declaration: when the function is defined / when the logic is created / entire function created

- parameters: a special type of variable created and used in a specific function

- arguements: when you casll your function you pass values as arguements, and those arguements take the place of your parameters

- return statement: manages output

- local variables: variable declared INSIDE a function

- global variables: variables cfreated in the GLOBAL namespace, ot outside of functions

General: document.write() given for free. takes input, does some processing, returns output

when to use return. for now always, unless you know otherwise

Functions allow you to group a set of related statements together that represent a single task.

Functions can take parameters (information required to do their job) and may return a value. 

If your function is going to perfrom a task, then you need to give your function a name. It should describe the task it is performing. 

An annonymous function is executed as soon as the interpreter comes across them. These do not have names, so they cannot be called. 

A function declaration is when you give your function a name and then write the statements needed to achieve it's task inside the curly braces. 
* Example below,  sayHello is the function name:
```
function sayHello() {
    document.write('Hello!');
}
```

When you ask it to perform the task it is known as calling the function. 

When you write a function and you expect it to provide you with an answer, the response is called, return value.

Sometimes a function needs more information to perform it's task. In this case you would add a parameter after the function name and in parentheses. 
* Example:

```
 function getArea(width, height) {
    return width * height;
}
```

In the parentheses is where you specity the values it should use. The values are called arguments, and they can be provided as values or as variables. 

You can get single values out of a function. 

Using an array you can also get multiple values out of a function.
