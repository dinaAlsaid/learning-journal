[previous](https://dinaalsaid.github.io/learning-journal/reading07) [Home](https://dinaalsaid.github.io/learning-journal/)

# Operators and loops 

## Logical operators 
The logical operators are :
* `==` :equal to.
* `!=` :not equal.
* `===` :strict equal (checks the value and the type).
* `!==` :strict not equal.
* `>` , `<` :greater than **and** less than.
* `>=` , `<=` :greater than or equal **and** less than or equal.
* `&&` :AND.
* `||` :OR.
* `!` :NOT.

you can combine these operators to create more complex logical expressions ( note that the whole expression returns a single value true or false)

### short circuit evaluation
When evaluating logical expressions start from left to right. 
if the first condition can provide enough info 
to get answer, there is no need to evaluate second condition
(ex: if first condition is zero ANDed with anything the answer 
is zero )

## loops
### for loops

For uses a counter as a condition
to run code a number of times until the 
condition is false.

````
for (initialize, condition, update){}
````


### while loop 

````
while (condition){}
````

while runs the code block until the condition is false.
It does not initialize or update the loop 
counter (unless you write the initialization and update 
by yourself in the code block).




