[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly)
# Data Structures - Arrays

[VIDEO 3 - Arrays]()<br>

## Arrays

An array is an ordered collection of data combined into one variable.<br>
Each item in the list is assigned an index value which is how elements are accessed and updated.

```js
const fruits = ['banana', 'orange', 'apple']
```
In the above fruits array, banana is at index 0, orange is at index 1, and apple is at index 2.<br>
:bulb: Just remember to always start at ZERO!<br>
:mag_right: Review the syntax<br> 
Square brackets `[]` define an array, and you separate each element in the array with commas `,`.

### Accessing Array Values
Access elements in an array using the index value in square brackets.

```js
const fruits = ['banana', 'orange', 'apple']

fruits[0] //banana
fruits[1] //orange
fruits[2] //apple
```

### Updating Array Values
Updating elements is just like accessing, but we will use our assignment operator `=` to reassign the value of the specific element.

```js
const fruits = ['banana', 'orange', 'apple']

fruits[0] = 'kiwi'
fruits[1] = 'strawberry'
//fruits is now ['kiwi', 'strawberry', 'apple']
```

## YOU DO :computer:

[CodePen Arrays](https://codepen.io/Katie22/pen/MWxpXLQ)

## Array Methods

JavaScript has built-in functions called methods that assists in accessing and updating elements in arrays.<br>
:mag_right: Review the syntax<br>
arrayName.methodName(input/arguments if needed)

### Array Method - push() [W3 Schools - push()](https://www.w3schools.com/jsref/jsref_push.asp)

Adds an element to the end of an array<br>
:mag_right: Review the syntax<br>
Notice single quotes for the strings. Single or double work just fine. If you use single, and there is a contraction like Pan's Labyrinth below, you must escape it with `\`

```js

const movies = ['Pan\'s Labyrinth', 'Hellboy']
movies.push('Crimson Peak')

```

### Array Method - unshift() [W3 Schools - unshift()](https://www.w3schools.com/jsref/jsref_unshift.asp)

Adds an element to the front of an array

```js
const cars = ['Ferrari', 'Porsche']
cars.unshift('Aston Martin')
```

### Array Method - pop() [W3 Schools - pop()](https://www.w3schools.com/jsref/jsref_pop.asp)

Removes the last element from an array

```js
const animals = ['pig', 'cow', 'sheep']
animals.pop()
// ['pig', 'cow']
```

#### Tip! :bulb: - there are several methods, use google to research potential solutions for working with arrays. [W3 Schools](https://www.w3schools.com/jsref/jsref_obj_array.asp) and [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) are great resources.

## YOU DO :computer:

[CodePen Array Methods](https://codepen.io/Katie22/pen/KKEWPqq)