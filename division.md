# Division

## Scenario: Result underflow

Given - A calculator is on and working properly

When - enters a small numbers with large number after precision

Then - Calculator will display error message of too small number.

## Scenario: Signs of the numbers

Given - A calculator is on and working properly

When - 1. enters two positive numbers\
    2. enters two negative numbers\
    3. enters positive and other negative number

Then - 1. Result is positive number\
    2. Result is positive number\
    3. Result is negative number

## Scenario: Zero value division

Given - A calculator is on and working properly

When - enters number and -0

Then - considers -0 as 0 and displays error

## Scenario: division by 1

Given - A calculator is on and working properly

When - enters a number and -1

Then - displays a negative of above number.  

## Scenario: Decimal value division

Given - A calculator is on and working properly

When - enters two decimal number

Then - round off a result in case of numbers after precision exceeds limit\
or occurs underflow

## Scenario: Irrational value division

Given - A calculator is on and working properly

When - enters 2 times square root and value  

Then -  considers as roots of root for division

## Scenario: Simple division

Given - A calculator is on and working properly

When - Enters a any operator before =

Then - Ignores a operator before = and displays division of above numbers.

## Scenario: Rational division

Given - A calculator is on and working properly

When - enters two fraction numbers\
    (a/b/c/d)

Then -  leads to incorrect result\
    performs division of a/b and performs division with c\
    instead of performing c/d division first\
    Use different symbol for fraction(/) and division(horizontal modulo symbol)

## Scenario: Decimal & integer division

Given - A calculator is on and working properly

When - Enters decimal number,/, integer and =

Then - a result after precision is zero then displays integer\
    otherwise displays decimal

## Scenario: More than two numbers division

Given - A calculator is on and working properly

When - 1. Enters more than two numbers if unknowingly missed / operator\
        (a/b/cd)
    2. divides a result of previous division and next number.

Then - 1. leads to incorrect calculation\
    2. underflow may occur in case of samller values division.

## Scenario: Range of operand exceeds allowed limit

Given - A calculator is on and working properly

When - Enters large number for division

Then - Displays error of large numbers

## Scenario: Pressing divide operator more than once

Given - A calculator is on and working properly

When - 1. enters a / 2 times\
    (a//2)

Then - considers as / once and displays result

## Scenario: Interleaving operators (Press /, then press /, then press +, press -)

Given - A calculator is on and working properly

When - Enters a number, /,/,+,- second number and =

Then - considers second number as negative,\
        performs second latest + operation and displays result

## Scenario: Decimal value capping

Given - A calculator is on and working properly

When - division of numbers does not fit into screen

Then - rounding decimal value calculator displays result
