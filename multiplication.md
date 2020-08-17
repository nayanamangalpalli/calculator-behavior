# Multiplication

## Scenario: Result overflow

Given - A calculator is on and working properly

When - enters a large number, *, second large number and =

Then - Calculator will display error message of too large numbers.

## Scenario: Signs of the numbers

Given - A calculator is on and working properly

When - 1. enters two positive numbers\
       2. enters two negative numbers\
       3. enters positive and other negative number

Then - 1. Result is positive number\
       2. Result is positive number\
       3. Result is negative number\

## Scenario: Zero value multiplication

Given - A calculator is on and working properly

When - enters number, *, 0 and =

Then - Result is zero

## Scenario: Multiplication by 1

Given - A calculator is on and working properly

When - enters a number and 1

Then - Result is entered number

## Scenario: Decimal value multiplication

Given - A calculator is on and working properly

When - enters  decimal number,*, second decimal number and =

Then - a result is rouded off in case of numbers after precision exceeds limit.

## Scenario: Irrational value multiplication

Given - A calculator is on and working properly

When - enters 2 times square root and value  

Then -  considers as roots of root for multiplication

## Scenario: Simple multiplication

Given - A calculator is on and working properly

When - Enters a any operator before =

Then - Ignores a operator before = and displays multiplication of above numbers.

## Scenario: Rational multiplication

Given - A calculator is on and working properly

When - enters two fraction numbers\
       (a/b*c/d)

Then - leads to incorrect result - a/b division is performed and multiplied with\
        instead of performing c/d divsion first\
        Use different symbol for fraction(/) and division(horizontal modulo symbol)

## Scenario: Decimal & integer multiplication

Given - A calculator is on and working properly

When - Enters decimal number,*, integer and =

Then - a result after precision is zero then displays interger\
       otherwise displays decimal

## Scenario: More than two numbers multiplication

Given - A calculator is on and working properly

When - 1. Enters more than two numbers if unknowingly missed * operator\
       2. Result of previous multipication is multiplied with new entered number.

Then - 1. leads to incorrect calculation\
       2. overflow may occur in some cases if larger values are multiplied.

## Scenario: Range of operand exceeds allowed limit

Given - A calculator is on and working properly

When - Enters large numbers for mutiplication

Then - Displays error of large numbers

## Scenario: Pressing "multiply button" multiple times

Given - A calculator is on and working properly

When - enters a number, * more than once, number and =

Then - considers * once and displays result performing multiplication

## Scenario: Interleaving operators (Press *, then press /, then press +)

Given - A calculator is on and working properly

When - Enters a number, *,/,+, second number and =

Then - considers latest + operator and performs addition, displays result

## Scenario: Decimal value capping

Given - A calculator is on and working properly

When - multiplication of numbers does not fit into screen

Then - rounding decimal value calculator displays result
