##Prime Factors

A prime number is only evenly divisible by itself and 1.

Note that 1 is not a prime number.

##Example

What are the prime factors of 60?

- Our first divisor is 2. 2 goes into 60, leaving 30.
- 2 goes into 30, leaving 15.
  - 2 doesn't go cleanly into 15. So let's move on to our next divisor, 3.
- 3 goes cleanly into 15, leaving 5.
  - 3 does not go cleanly into 5. The next possible factor is 4.
  - 4 does not go cleanly into 5. The next possible factor is 5.
- 5 does go cleanly into 5.
- We're left only with 1, so now, we're done.

Our successful divisors in that computation represent the list of prime
factors of 60: 2, 2, 3, and 5.

You can check this yourself:

- 2 * 2 * 3 * 5
- = 4 * 15
- = 60
- Success!x


### How to Run this Lab

+ Clone the repository
+ Open **index.html** in your browser to see the currently failing test specs you are to pass
+ Open the repository in your favorite text editor to explore the different files
+ Open **js\prime-factor.js** and write the function(s) or lines of code to pass the tests
+ You could refresh **index.html** in your browser intermittently to see the status of test specs.


###Notes

+ Prior understanding of Javascript classes, returning, and conditional statements will be required to complete this exercise.

+ Remember that passing code is just the first step. The goal is to work towards a solution that is as readable and expressive as you can make
it.

+ Please make your solution as general as possible. Good code doesn't just pass the test suite, it works with any input that fits the specification.

Have fun!
