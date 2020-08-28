# Hungry for More?

## Prerequisites
* Javascript functions
* Javascript conditionals

### 1. Digit Sum

Write a function `sumDigits` that accepts a number and returns the sum of its digits.

```
console.log(sumDigits(42));
```

> => 6

### 2. Pythagoras

Write a function `calculateSide` that takes two arguments: `sideA` and `sideB`, and returns the solution for sideC using the Pythagorean theorem.
  
_hint:_ discover the Pythagorean Theorem on a website called google.com  
_hint:_ checkout the [Math methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math) in javascript
```
console.log(calculateSide(8, 6));
=> 10
```

### 3. Triangles

Write a function called `drawTriangle` that takes 2 paramenters: `size` and `orientation`. Your function will console log a **right isosceles triangle** made of '#' that has the height and length of the `size` argument. The point of the triangle should be upright if the second argument is `'up'`, but it should be flipped upside down if the second argument is `'down'`.

>Ex: `drawTriangle(7, 'up')
```
#
##
###
####
#####
######
#######
```

>Ex: `drawTriangle(6, 'down')`
```
######
#####
####
###
##
#
```

### 4. "Second" Numbers

Write a function `secondNumbers` that takes an **array** as an argument and returns the second highest and second lowest numbers. Make it so that it works even if the array is out of order. 

```
console.log(secondNumbers([4,2,6,9,5]));
=> second highest: 6
=> second lowest: 4
```

### 5. Unique String

Write a function `uniqueString` that takes a string as an argument and returns the string with any duplicate letters taken out. Meaning, only the first instance of a letter should remain in the string, thus returning a full string of unique characters (e.g. icecream => iceram). Make it work for just a single string with no spaces or punctuation. 

```
console.log(uniqueString("helloworld));
=> helowrd
```

### 6. Insert Dash
Write a function `insertDash` that accepts a number as a parameter and returns a string with a dash inserted between any consecutive **odd numbers**. There should not be a dash at the end, it goes only between numbers.
```javascript
console.log(insertDash(454793));

> => 4547-9-3
```

## Bonus: Handle Bad Input

Add conditions to your function so there is error handling for bad input. For example, if you are expecting an `integer` argument, but you give you function a `string` argument instead, it could print out the message `error: Bad Input! Please try again with an integer.`

---

Adapted from [SEI-MAE](https://git.generalassemb.ly/Software-Engineering-Immersive-Remote/SEIR-MAE-INSTRUCTORS/tree/master/unit_1/w02d3/homework/JS_Functions_Scope_Problem_Solving)
