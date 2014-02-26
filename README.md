#Even Fibonacci Numbers

##Challenge 2

    From Project Euler Problem 2

Each new term in the Fibonacci sequence is generated by adding the previous two terms. By starting with 1 and 2, the first 10 terms will be:

    1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...

By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the even-valued terms.

Clone this project, write the body of the function **sumOfEvenFibonacciNumbers** so that the jasmine tests pass.
The function will return the sum of all the even numbers in the fibonacci sequence where the value of the term does not exceed **n**.

Remember, **n** is not how many numbers in the fibonacci sequence, it is the **max value, the last term in a fibonacci sequence** where you will then add up all **even** numbers.

There are **2** tests, once the first test passes, uncomment the last test and fill in the correct result.

(you'll need jasmine-node)  
    npm install jasmine-node -g

run automated tests by running  
    jasmine-node --autotest .