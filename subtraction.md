# Subtraction

## Scenario: subtraction of two negative numbers

Given - A calculator is on and working properly\
        working properly - screen and keys are working.

When - Enters a two negative number

Then - Converts a second negative number into positive number\
        and performs subtraction operation.

## Scenario: subtraction of two positive numbers
  
Given - A calculator is on and working properly

When - Enters a two positive numbers and after second number if presses -

Then - Ignores - after = and Displays result.

## Scenario: subtraction of fractions(negative or Negative)
  
Given - A calculator is on and working properly

When -  enters two fraction numbers
        (a/b-c/d)

Then -  performs division first and subtraction
  
## Scenario: subtraction of negative and positive number

Given - A calculator is on and working properly

When -  Enters positive and negative number and presses extra -\
        (a---b)

Then -  repetition of - in odd number considers b as negative\
        performs subtraction operation\
        repetition of - in even number considers b as positive\
        performs addition operation

## Scenario: subtraction of decimals

Given - A calculator is on and working properly

When - Enters two decimal number and . 2 times

Then - Doesn't allow to enter . again and displays result in decimal.
  
## Scenario: Typing operator more than once

Given - A calculator is on and working properly

When -  1. in subtraction of two positive numbers

Then -  1. converts second number to positive and performs addition\
        operation.

## Scenario: provides 6-* as an input

Given - A calculator is on and working properly

When -  Enters a number, -*,second number,=

Then -  Considers a latest * operator and performs multiplication,
        displays result.

## Scenario: Identity operation

Given - A calculator is on and working properly

When -  Enters number, -, 0 and = 2 times

Then -  Considers = once and displays result.\
        or repeats same operation twice and displays result

## Scenario: Converse operation

Given - A calculator is on and working properly

When - Enter a numbers a--b or -b-a

Then - Displays result same value but different sign.
