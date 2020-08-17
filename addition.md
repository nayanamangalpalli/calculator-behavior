# Addition

## Scenario: Addition of two positive numbers

Given - A calculator is on and working properly
        working properly - screen and keys are working.

When - Enter a negative number, + , second negative number, and =.

Then - Displays result (positive number).

## Scenario: Addition of two negative numbers
  
Given - A calculator is on and working properly

When - I will enter a negative number, + , second negative number and =

Then - Displays result (negative number).

## Scenario: Addition of fractions(Positive or Negative)
  
Given - A calculator is on and working properly

When - I will enter a fractional number, +, another fractional number and =

Then - Displays result in fractional form.
  
## Scenario: Addition of positive and negative number

Given - A calculator is on and working properly

When - Enters positive number, +,negative number and press - 2 times,=

Then - Considers a latest - operation and displays positive or negative result.

## Scenario: Addition of decimals

Given - A calculator is on and working properly

When - I will enter decimal number, . 2 times, +, second decimal number, =

Then - Doesn't allow to enter . again and displays result in fraction.
  
## Scenario: Typing operator more than once

Given - A calculator is on and working properly

When - I will enter a number, + two times, second number and =

Then - Considers + only once and displays result.

## Scenario: Adding numbers where the result goes out of range

Given - A calculator is on and working properly

When - I will enter a large number, +, second large number and =

Then - Displays result from beginning and using left,right arrow we can scroll result.

## Scenario: 6+* is provided as input

Given - A calculator is on and working properly

When - I will enter a number, +*,second number,=

Then - Considers a latest operator and displays result.

## Scenario: Identity operation

Given - A calculator is on and working properly

When - I will enter number, +, 0 and = 2 times

Then - Considers = only once and displays result.

## Scenario: Converse operation

Given - A calculator is on and working properly

When - I will enter a number, +, second number,= or vice-versa

Then - Displays same result.
