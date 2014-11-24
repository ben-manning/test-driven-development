# Test Driven Development Lab

1. `$ cd` into your `sf-wdi-14` directory
2. Clone https://github.com/sf-wdi-14/test-driven-development and `$ cd` into it
3. Run `$ mocha`
4. Write tests for the following functions and then make the tests pass (files prepared in `/test`)
5. Run specs by running `$ mocha`; if this command cannot be found, run `$ npm install mocha chai -g` first
6. Push to your own branch (named after your first name) of the test-driven-development repository: `$ git push origin HEAD:firstname` (replace 'firstname' with your first name)

```javascript
// Pass in a string and return the second to last word.
// Example: findPenultimateWord("this is me") should return "is"
penultimateWord()

// Calculate the sum of all digits of an integer.
// Example: sumOfDigits(123) should return 6
// Also: sumOfDigits("123") should return 6 as well
sumOfDigits()

// Find the highest value in an array of integers.
// Example: highestValue([1, 2, 3]) should return 3
highestValue()

// Find the longest word of a string.
// Example: longestWord("one two three") should return "three"
longestWord()

// Find the nth number of the Fibonacci sequence.
// Example: nthFibonacciNumber(4) should return 2
nthFibonacciNumber()
```
