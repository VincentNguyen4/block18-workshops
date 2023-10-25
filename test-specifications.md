# Block 18 Test Specifications

## Unit Tests:

1. A function called "multiplication" that returns the product of two input numbers.
+ expect the input to be two numbers
+ expect the output to be a number
- expect an error if the input contains a nonnumber 
- expect an error if there are fractions as strings




2. A function called "concatOdds" takes two arrays of integers as arguments.  It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.

+ expect the output to be a single array
+ expect the output to be all odd numbers
+ expect the output to only contain one instance of a number
+ expect the numbers to be in ascending order
- expect an error if an array doesn't contain numbers i.e. strings


## Functional Test

1. A shopping cart checkout feature that allows a user to check out as guest ( without an account), or as a loggged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.

+ When a user checks out, they will be prompted if they want to make an account or log in if they are a guest
+ When a user checks out, they should be redirected to the checkout page
+ When a user checks out, if they are logged-in, there should be not be asked