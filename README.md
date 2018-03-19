# JavaScript Iterators

Open a [Repl](repl.it/languages/javascript) to do the following exercises. Submit your REPL link to the Project Submission Doc.

## `.forEach()`
- `getCounter` – counts how many of each charater are in a string and returns in an object
	- ex: `getCounter('mom') => {m: 2, o: 1}`
	- ex: `getCounter('caterpillar') => {c: 1, a: 2, t: 1, e: 1, r: 2, i: 1, l: 2}`
- `countIntegers` – counts how many integers there are in an array
	- ex: `countIntegers([4, 2.2, 5, 6, 4.2, 8.2, 4]) // => 4`
	- Hint: Google how you can check if a number is an integer in JavaScript
- `sumIsDivisibleBy5` – adds all numbers in an array and returns if the sum is divisible by 5
	- ex. `sumIsDivisibleBy5([1, 2, 3, 4, 5]) // => true (bc 1 + 2 + 3 + 4 + 5 = 15, and 15 is divisible by 5)`
	- Hint: define `var totalSum = 0;` in the beginning, and remember what modulus does
- `getPersonSentence` – formats an object (with `name`, `yearOfBirth`, and `city` keys) into a sentence
	- ex. `getPersonSentence({name: ’Sam’, yearOfBirth: 1990, city: 'Los Angeles'}) // => 'Sam is 28 years old and lives in Los Angeles'`
	- Hint: Google how you can get the current year in JavaScript (without hard-coding in `var currentYear = 2018`)
- `getLongestName` – takes in an array of objects (with `name` and `age` keys), and prints out the longest name
	- ex: `getLongestName([{name: ’Sam’, age: 20}, {name: ’Charlotte’, age: 30}, {name: ’Dany’, age: 40}]) => ‘Charlotte’`

## `.map()`
Write code using `.map()` to have the following input and output:

- `getSquares` – takes in an array of numbers and returns an array of their squares
  - ex: `getSquares([1, 2, 3, 4, 5]) => [1, 4, 9, 16, 25]`
  
- `isDivisibleBy3` – takes in an array of numbers and returns an array of booleans indicating whether each element is divisible by 3
  - ex: `isDivisibleBy3[1, 3, 4, 6, 7, 8, 9] => [false, true, false, true, false, false true]`
  
- `getColors` – takes in an array of objects (with `name` and `color` keys) and returns an array of each object’s color
  - ex: `getColors([{name: ’apple’, color: 'red'}, {name: ’banana’, color: 'yellow'}, {name: ’kiwi’, color: 'green'}]) => ['red', 'yellow', 'green']`
  
- `getCities` – takes in an array of objects (with `city` and `state` keys) and returns an array of each object’s city
  - ex: `getNames([{city: ’Nashville’, state: 'Tennessee'}, {city: ’Portland’, state: 'Maine'}, {city: ’New York City’, state: 'New York'}]) => ['Nashville', 'Portland', 'New York City']`

## `.filter()`
Write code using `.filter()` to have the following input and output:

- `getOdds` – takes in an array of numbers and returns an array of only odd numbers
  - ex: `getOdds([1, 2, 3, 4, 5, 6, 7, 8, 9, 10]) => [1, 3, 5, 7, 9]`

- `getEvens` – takes in an array of numbers and returns an array of only even numbers
  - ex: `getEvens([1, 2, 3, 4, 5, 6, 7, 8, 9, 10]) => [2, 4, 6, 8, 10]`
  
- `getDivisibleBy4` – takes in an array of numbers and returns an array of only numbers that are divisible by 4
  - ex: `getDivisibleBy4([1, 4, 6, 8, 12, 13]) => [4, 8, 12]`
  
- `getCWords` – takes in an array of words and returns an array of only words that start with C (uppercase OR lowercase)
  - ex: `getCWords(['Carl', 'Allie', 'Ben', 'car', 'Carmen']) => ['Carl', 'car', 'Carmen']`

- `getSquares` – takes in an array of numbers and returns an array of only numbers that have an integer square root
  - ex: `getSquares([1, 2, 4, 6, 7, 9, 12, 16, 20, 25]) => [1, 4, 9, 16, 25]`
  - Hint: Figure out how to get the square root of each number, then test if that square root is an integer
  
- `getCNamedObjects` – takes in an array of objects and returns an array of only objects with a nam that start with C (uppercase OR lowercase) 
  - ex: `getCNamedObjects([{name: 'Carl', age: 30}, {name: 'Allie', age: 20}, {name: 'Ben', age: 40}, {name: 'Cara', age: 10}, {name: 'Carmen', age: 15}]) => [{name: 'Carl', age: 30}, {name: 'Cara', age: 10}, {name: 'Carmen', age: 15}]` 
  - Hint: Look at your previously written `getCWords` function for some inspiration

## `.reduce()`
Write code using `.reduce()` to have the following input and output:

- `addUpAll` – add up all numbers in a given array
  - ex. `addUpAll([1, 2, 3, 4, 5, 6, 7, 8, 9, 10]) => 55` 

- `multiplyAllNums` – multiply all numbers in a given array
  - ex. `multiplyAllNums([1, 2, 3, 4, 5]) => 120`
  
- `squareAllNums` – power up all numbers in a given array
  - ex. `squareAllNums([3, 2, 3]) => 729, bc (3 ^ 2) = 9, and (9 ^ 3) = 729`

- `addUpAllAges` – add up all the ages in an array of objects
  - ex. `addUpAllAges([{name: 'Carl', age: 30}, {name: 'Cara', age: 10}, {name: 'Carmen', age: 15}]) => 55` 
