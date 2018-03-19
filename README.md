# JavaScript Iterators

Open a [Repl](repl.it/languages/javascript) to do the following exercises. Submit your REPL link to the Project Submission Doc.

## `.forEach()`
- `countZeros` – counts how many 0s there are in an array
	- ex: `countZeros([0, 2, 0, 6, 4, 0]) // => 3`
- `addUpTo` – adds all numbers up to a given max number
	- ex. `addUpTo(5) // => 15 (bc 1 + 2 + 3 + 4 + 5 = 15`
	- Hint: define a `var currentSum = 0;` variable in the beginning, and keep adding to it as you loop through all the numbers in the array
- `getPersonSentence` – formats an object (with `name`, `age`, and `city` keys) into a sentence
	- ex. `getPersonSentence({name: ’Sam’, age: 28, city: 'Los Angeles'}) // => 'Sam is 28 years old and lives in Los Angeles'`
	- `getDifference` – takes in an array of numbers and returns a sentence with the highest number, lowest number, and the difference between them
	- ex: `getDifference([5, 2, 3, 8, 1]) // => 'The highest number is 8. The lowest number is 1. The difference is 7'`
	    
- `countVowels` – counts how many vowels there are in an array
	- ex: `countVowels(['a', 'b', 'u', 'c', 'g', 'o']) // => 3`
	
- `getPersonSentence_v2` – formats an object (with `name`, `yearOfBirth`, and `city` keys) into a sentence
	- ex. `getPersonSentence_v2({name: ’Sam’, yearOfBirth: 1990, city: 'Los Angeles'}) // => 'Sam is 28 years old and lives in Los Angeles'`

- `getLongestName` – takes in an array of objects (with `name` and `age` keys), and prints out the longest name
	- ex: `getLongestName([{name: ’Sam’, age: 20}, {name: ’Charlotte’, age: 30}, {name: ’Dany’, age: 40}]) => ‘Charlotte’`
	- Hint: Use the previously written `getNames()` function to help you

## `.map()`
Write code using `.map()` to have the following input and output:

- `getSquares` – takes in an array of numbers and returns an array of their squares
  - ex: `getSquares([1, 2, 3, 4, 5]) => [1, 4, 9, 16, 25]`
  
- `isDivisibleBy3` – takes in an array of numbers and returns an array of booleans indicating whether each element is divisible by 3
  - ex: `isDivisibleBy3[1, 3, 4, 6, 7, 8, 9] => [false, true, false, true, false, false true]`
  
- `getAges` – takes in an array of objects (with `name` and `age` keys) and returns an array of each object’s age
  - ex: `getAges([{name: ’Sam’, age: 20}, {name: ’Charlotte’, age: 30}, {name: ’Dany’, age: 40}]) => [20, 30, 40]`
  
- `getNames` – takes in an array of objects (with `name` and `age` keys) and returns an array of each object’s name
  - ex: `getNames([{name: ’Sam’, age: 20}, {name: ’Charlotte’, age: 30}, {name: ’Dany’, age: 40}]) => [‘Sam’, ‘Charlotte’, ‘Dany’]`

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
