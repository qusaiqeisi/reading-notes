# Operators and Loops
**function , method & object**
> A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the outpu
> JavaScript methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition
> An object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method. In addition to objects that are predefined in the browser, you can define your own objects
   


   ## evaluating conditions & conditional satamant .
    1. evaluating conditions : which is return value  
    2. conditional satamant : which is return     

| Operator | Comparisons | Description |
| :---         |     :---:      |      
| Equal (==)   | 	x == y    | Returns true if the operands are equal.   |
|Strict equal (===)    | x === y       | Returns true if the operands are equal and of the same type.     |
| Not equal (!=)   | x != y     | Returns true if the operands are not equal.   |
| Strict not equal (!==)   | 	x !== y       | Returns true if the operands are not equal and/or not of the same type.
      |
| Greater than (>)  |x>ys     |Returns true if the left operand is greater than the right operand.    |
| Greater than or equal (>=)    | x>=y       | Returns true if the left operand is greater than or equal to the right operand.
      |
|Less than (<)   | 	x<y     | Returns true if the left operand is less than the right operand.    |
| Less than or equal (<=)   | x<=y       | Returns true if the left operand is less than or equal to the right operand.
      |


![for&whil](https://i.stack.imgur.com/Ovdg0.png)
1-  initialization
The initialization expression initializes the loop. The initialization expression is executed only once when the loop starts. You typically use the initialization is to initialize a counter variable. If you use the var keyword to declare the counter variable, the variable will have either function or global scope. In other words, you can reference the counter variable after the loop ends. However, if you use the let keyword to declare the counter variable, the variable will have a blocked scope, which is only accessible inside the loop.

2) condition
The condition is an expression that is evaluated once before every iteration. The statement inside the loop is executed only when the condition evaluates to true. The loop is terminated if the condition evaluates to false. Note that the condition is optional. If you omit it, the for loop statement considers it as true.

3) post-expression
The for loop statement also evaluates the post-expression after each loop iteration. Generally, you use the post-expression to update the counter variable

**he following example uses the for loop statement that shows the numbers from 1 to 5 in the Console window.**

## 
for (var counter = 1; counter < 5; counter++) {
    console.log('Inside the loop:' + counter);
}
console.log('Outside the loop:' + counter);

![tru](https://upload.wikimedia.org/wikipedia/commons/4/4a/Truth_table_for_AND%2C_OR%2C_and_NOT.png)

## chek your self

| Operator | Comparisons | Description |
| :---         |     :---:      |      
| Equal (==)   | 	........    | Returns true if the operands are equal.   |
|Strict equal (===)    | x === y       | Returns true if the operands are equal and of the same type.     |
| ................  | x != y     | Returns true if the operands are not equal.   |
| Strict not equal (!==)   | 	............       | Returns true if the operands are not equal and/or not of the same type.
      |
| Greater than (>)  |x>ys     |Returns true if the left operand is greater than the right operand.    |
| Greater than or equal (>=)    | x>=y       | Returns true if the left operand is greater than or equal to the right operand.
      |
|Less than (<)   | ......   | Returns true if the left operand is less than the right operand.    |
| Less than or equal (<=)   | x<=y       | Returns true if the left operand is less than or equal to the right operand.
      |