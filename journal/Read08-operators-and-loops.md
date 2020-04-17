# Operators and Loops

## Operators

* Comparison Operators
* Logical Operators

## Comparison Operators

**Comparison Operators** compare a value in the script to what you might expect. The result will always be a **Boolean** (True/False).

### Types of Comparison Operators

* `==` = is equal to ("soft equal")
* `===` = is strict equal to ("strict equal")
* `!=` = is not equal to
* `!==` = is strict not equal to
* `>` = greater than
* `<` = less than
* `>=` = greater than or equal to
* `<=` = less than or equal to

**Structure of Comparison Operators:**

`(score >= pass)` (must have enclosing parentheses)

This is an **expression**, because it resolves into a *single value* of TRUE or FALSE.

## Logical Operators

**Logical Operators** usually return single values of TRUE or FALSE. They can compare the results of multiple operators.

## Loops

* **Loops** check a **condition**
* If TRUE, a code block runs, and then checks again
* If *still* TRUE, the code block runs again
* Loops will repeat until the condition returns FALSE

### Common Loop Types

* **For Loop**: Used to run code a **specific number of times**
    * Most common loop
    * Condition: Generally a counter telling it how many times to run
    * Good for using a known number of "things"

* **While Loop**: Used if you don't know how many times the code should run
    * Condition: Can be something other than a counter
    * Code will continue to loop as long as condition is TRUE
    * Good for an unknown number of "things"

### Loop Counters

* **Intitialization**: `var i = 0`
    * Create a variable and set it to 0
    * Commonly called '`i`', which acts as the counter
    * Created the first time the loop is run
    * Sometimes '`i`' is declared *before* the function

* **Condition**: `i < 10`
    * Loop should continue running until counter reaches a specific number
    * In `i < 10`, loop will run 10 times before stopping
    * May also hold a variable that in turn holds a number

* **Update**: `i = i + 1` OR `i++`
    * Every time the loop runs the statement in `{ }`, one is added to the counter
    * One is added to the counter with the increment `++` operator
    * Can also count downward using decrement `--` operator

### Assorted Notes

* When you use the `prompt` command, it evaluates *everything entered* as a **string**


Return to the [Table of Contents](https://alex-whan.github.io/learning-journal/)