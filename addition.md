# Addition

## Scenario: Addition of two positive numbers

Given - A calculator is turned on and working properly

        working properly - screen and keys are working.

When - Enter a positive number, + , second positive number, and =.

Then - A result will be displayed which is a positive number.

## Scenario: Addition of two negative numbers
  
Given - A calculator is turned on and working properly

When  - I will enter a negative number, + , second negative number and =

Then  - The result will be displayed which is negative number.

## Scenario: Addition of fractions(Positive or Negative)
  
Given - A calculator is turned on and working properly

When  - I will enter a fractional number, + symbol,another fractional number and = 

Then  - The result is displayed in fractional form.
  
## Scenario: Addition of +ve and -ve number

Given - A calculator is turned on and working properly

When  - I will enter positive number, +, negative number and presses - 2 times, = .

Then  - The latest - operation is considered and displays either +ve or -ve result.

## Scenario: Addition of decimals

Given - A calculator is turned on and working properly

When - I will enter decimal number, . 2 times, +, second decimal number, =

Then - Doesn't allow to enter . again and displays result in fraction.
  
## Scenario: Typing operator more than once

Given -A calculator is turned on and working properly

When  - I will enter a number, + two times, second number and =

Then  - The + should be considered only once and result should be displayed.

## Scenario: Adding numbers where the result goes out of range

Given - A calculator is turned on and working properly

When  - I will enter a large number, +, second large numberand =

Then  - Displays result from begining and using left,right arrow we can scroll result.

## Scenario: 6+* is provided as input?

Given - A calculator is turned on and working properly

When  - I will enter a number, +*,second number,=

Then  - The latest * is considered and based on the operator the operation is performed.

## Scenario: Identity operation

Given - A calculator is turned on and working properly

When  - I will enter number, +, 0 and = 2 times 

Then  - The result is displayed and = consideres only once

## Scenario: Converse operation

Given - A calculator is turned on and working properly

When  - I will enter a number, +, second number,= or vice-versa

Then  - Displays same result. 
