### Comparison Operators

Comparison operators usually return single values of true or false.

- ```==``` Is equal to
- ```===``` Strict equal to 
- ```!=``` Is not equal to
- ```!==``` Strict not equal to
- ```>``` Greater than 
- ```- >=``` Greater than or equal to
- ```<``` Less than
- ```<=``` Less than or equal to 

### Logical Operators

Logical operators allow you to compare the results of more than one comparison operator. 

- ```&&``` Logical and
- ```||``` Logical or
-```!``` Logical not

### Loops

3 common types of loops:    

- **For loops**: This instructs the code to run a specified number of times.
```
for (var i = 0; i < 10;i++) {
        console.log(i);
}
```
 -    **While loop**: As long as there's an empty string (as shown below), we are stuck in the while loop doing the same thing. 

 ```
 while (name === '') {
     name = prompt('What's your name darnit!?');
 } 
 ```

 You can also use a while loop to count. Console.log(i); will print value of. And i++; will increment i, add 1 to i each time. The example below will count from 0-8. 

 ```
 var i = 0;
 while (i < 9 ){
     console.log(i);
     i++;
 }
 ```
 - **Do While**: similar to while loop except the do while will always run the statements inside the curly braces at least once, even if the condition evaluates to false. 