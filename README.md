# JavaScript Iterators

Open a [Repl](repl.it/languages/javascript) to do the following exercises. Submit your REPL link to the Project Submission Doc.

## `.forEach()`
- `countIntegers` – counts how many integers there are in an array
	- ex: `countIntegers([4, 2.2, 5, 6, 4.2, 8.2, 4]) // => 4`
- `addUpTo` – adds all numbers up to a given max number
	- ex. `addUpTo(5) // => 15 (bc 1 + 2 + 3 + 4 + 5 = 15`
	- Hint: define `var totalSum = 0;` in the beginning
- `getPersonSentence` – formats an object (with `name`, `yearOfBirth`, and `city` keys) into a sentence
	- ex. `getPersonSentence({name: ’Sam’, yearOfBirth: 1990, city: 'Los Angeles'}) // => 'Sam is 28 years old and lives in Los Angeles'`
	- ex: `getDifference([5, 2, 3, 8, 1]) // => 'The highest number is 8. The lowest number is 1. The difference is 7'`
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

- `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]` 

  --> `[1, 3, 5, 7, 9]`
- `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]` 
  
  --> `[3, 6, 9]`
- `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]` 
  
  --> `[1, 4, 9]`
- `['Carl', 'Allie', 'Ben', 'Cara', 'Carmen']` 
  
  --> `['Carl', 'Cara', 'Carmen']`
- `[{name: 'Carl', age: 30}, {name: 'Allie', age: 20}, {name: 'Ben', age: 40}, {name: 'Cara', age: 10}, {name: 'Carmen', age: 15}]` 
  
  --> `[{name: 'Carl', age: 30}, {name: 'Cara', age: 10}, {name: 'Carmen', age: 15}]`

## `.reduce()`
Write code using `.reduce()` to have the following input and output:

- `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]` 

  --> `55`
- `[1, 2, 3, 4, 5]` 

  --> `120`
- `[100, 4, 5]` 

  --> `5`
- `[5, 2, 2]` 

  --> `625`
