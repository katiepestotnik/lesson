[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly)

# Data Structures - Objects

[VIDEO 4 - Objects]()

## Objects

<p>An object is a collection of properties associated as pairs of keys and values.  A good example is an employee of General Assembly.</p>
:mag_right: Review the syntax <br>
Curly brackets define an object and you separate each property with a comma and you separate the key/values with a colon.

```js
const instructor = {
  name: 'Katie',
  company: 'General Assembly',
  yearsActive: 2,
}
```
<p>The instructor object has three properties.<br>
The keys are: name, company, yearsActive<br>
The values are: 'Katie', 'General Assembly', 2</p>

### Accessing Object Values

#### Dot Notation (preferred)
:mag_right: Review the syntax <br>
object.key

```js
const instructor = {
  name: 'Katie',
  company: 'General Assembly',
  yearsActive: 2,
}
instructor.name //'Katie'
instructor.yearsActive // 2
```

#### Bracket Notation
:mag_right: Review the syntax <br>
object['key']

```js
const instructor = {
  name: 'Katie',
  company: 'General Assembly',
  yearsActive: 2,
}
instructor['name'] //'Katie'
instructor['yearsActive'] // 2
```

### Updating Object Values
<p>Same as accessing however you will use the assignment operator (=) to change the value.</p>

#### Dot Notation (preferred)

```js
const instructor = {
  name: 'Katie',
  company: 'General Assembly',
  yearsActive: 2,
}
instructor.name = 'Katie Pestotnik'
```
#### Bracket Notation
```js
const instructor = {
  name: 'Katie',
  company: 'General Assembly',
  yearsActive: 2,
}
instructor['name'] = 'Katie Pestotnik'
```
#### Note - You can add properties to an object just like you update values.
```js
instructor.location = 'Colorado'

```

## YOU DO :computer:

[CodePen Objects](https://codepen.io/Katie22/pen/XWGMWmG)