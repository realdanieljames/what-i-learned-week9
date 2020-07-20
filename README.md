# what-i-learned-week9


.concat()
concatenation, get both togeteher

<hr>

# 2 DIMENSIONSAL ARRAYS  

![cells description](https://files.slack.com/files-pri/T013BDPUM7X-F016N0GD8J3/image.png)

Array methods explained visually :arrow_down:
🟥 🟦 🟩 .map( ):red_circle::large_blue_circle: 🟢
🟨 🟪 🟠 .filter( ) 🟨 🟪
🟦:yellow_heart:🟢 .find( ) :yellow_heart:
🟨 🟦 🟩 .findIndex( 🟦 ) 1
🟠 🟦 🟩 .some( 🟩 ) true
🟥:red_circle:🟠 .every( 🟠 ) false
works well with Indices rule

# API (APPLICATION PROGRAM INTERFACE)

- a way to get free data
- no copyright



# CALLBACKS







  
  ## MARKDOWN UPGRADE
  add ``` javascript in readme to activate coloration while viewing a markdown in GitHub.ft
<hr>


## COMMA SEPARATED VALUES (CSV)

```javascript
const fs = require('fs');

const file = fs.readFileSync('./example.csv', 'utf-8')
console.log(file)
```
- it takes in two things: a file to read, always UTF-8 for character interpretation

- telling it what to read(example.csv), and how to read it(utf-8)
  




<hr>

## METHODS INTRODUCED IN WEEK 9

#### Array.isArray()
- returns a boolean value (true or false)
The Array.isArray() method determines whether the passed value is an Array.

#### Array.isArray() **syntax**
```javascript
Array.isArray([1, 2, 3]);  // true
Array.isArray({foo: 123}); // false
Array.isArray('foobar');   // false
Array.isArray(undefined);  // false
```
<hr>


### to.String()


## .split()
- works only on strings
- returns an array
- opposite function = .join()
<hr>

## .join()
- works on arrays
- returns strings
- opppsite function = .split()
<hr>

### throw
- throws a user-defined exception
- a quick way to make an error happen 
-helpful for debugging - error checking

## typeof 

## new


## setTimeout()  
```javascript
setTimeout(function, milliseconds)
```
-- run this functions after after given amount of time. (time in milliseconds)
## clearTimeout()
-when that gets passed to clear timeout it cancels the timer on the calue set by setTimeout()


## setInterval()

## clearInterval()
X

## TIPS AND TRICKS
F12 -  in vs code while a function, variable is highlighted, navigates to highleted value
Shift + F12 - shows all locations if highlighted value.


## Escape Character (backslash \)
\r
\t
\n - new line