# Addition

## Scenario: Addition of two positive numbers

Given - A calculator is turned on,
        pressed keys displayed on screen and should be visible,
        numbers,+,-,= keys are working properly.

When - Enter a positive number,
       plus(+) symbol,
       another positive number,
       and result(=) symbol.

Then - A result will be displayed which is a positive number.

## Scenario: Addition of two negative numbers
  
Given - A calculator is turned on,
        pressed keys displayed on screen and should be visible,
        numbers,+,-,= keys are working properly.

When  - I will enter a negative number,
        plus symbol,
        another negative number,
        and result(=) symbol

Then  - The result will be displayed which is negative number.

## Scenario: Addition of fractions(Positive or Negative)
  
Given - A calculator is turned on,
        pressed keys displayed on screen and should be visible,
        numbers,+,-,/,= keys are working properly.

When  - I will enter a fractional number,
        plus symbol,
        another fractional number,
        and result(=) symbol

Then  - The result is displayed in fractional form.
  
## Scenario: Addition of +ve and -ve number
  
Given - A calculator is turned on,calculator working properly(typed keys displayed on screen and should be visible, numbers,+,-,/,= keys are working properly).

When  - I will enter positive number,
        +,
        negative number and presses - 2 times,
        = .

Then  - The latest - operation is considered and result is displayed which could be negative or positive.

## Scenario: Addition of decimals
  
Given - A calculator is turned on,
        Calculator working properly.
        
When  - I will enter decimal number and press . 2 times,
        +, 
        second decimal number,
        =

Then  - Calculator should npt allow me to enter . and result should be displayed in fraction.
  
## Scenario: Typing operator more than once

Given - A calculator is turned on,
        Calculator working properly

When  - I will enter a number, 
        + two times,
        second number
        and =
       
Then  - The + should be considered only once and result should be displayed.

## Scenario: Adding numbers where the result goes out of range

Given - A calculator is turned on,
        Calculator working properly

When  - I will enter a large number, 
        +, 
        second large number
        and =

Then  - The result is displayed from begining and using left,right arrow we can scroll result horizontally.

## Scenario: 6+* is provided as input?

Given - A calculator is turned on,
        Calculator working properly

When  - I will enter a number, 
        +*,
        second number,
        =

Then  - The latest * is considered and based on the operator the operation is performed.

## Scenario: Identify operation

Given - A calculator is turned on,
        Calculator working properly

When  - 

Then  - 

## Scenario: Converse operation

Given - A calculator is turned on,
        Calculator working properly

When  - 

Then  - 
