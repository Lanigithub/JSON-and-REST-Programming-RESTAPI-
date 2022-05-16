***
## JSON and REST Programming (REST API)
***
### JSON(JavaScript Object Notation):
* ####  Data representation format
* #### Commonly used for APIs and configs
* #### Light weight and easy to read/write
* #### Integrates easily with most languages 

### JSON Types:
* #### Numbers: 8, 2.5, -3, 1.5e18
* #### Strings: " Hello World", "Name", "ID", "123"
* #### Booleans: true false
* ####  Array: [ " Hello", "World", "123"], [-8,3,10]
* #### Objects: {"key": "value"}{"Name": "Larry"}{"ID": 12345}

### Writing JSON( file.json)---objects in the key: value pairs (inside the curry brackets:
#### Example 1: user.json
```
{"name": " Donny Jackson",
" age" : " 25" ,
"gender" : "male",
"phone number" : " 925-217-9990",
"email" : "donnyjackson@gmail.com",
"hobbies" : [ "hiking", "reading", "skiing", "boating"],
"isCollege Graduate" : true,
" friends" : [ {"name": "Jenny Louis",
"age": ..
"gender" :...
....
"isCollegeGraduate": false,
"friends" : [ {}]
]

```
### Write JSON on visual studio---write objects inside the square brackets that's easy to copy and paste to the html scripts
** _Remember JSON is the JavaScript Object Notation._**
#### Example 2: companies.json: with two objects
```
[ {"name":"Big Solar ",
"type": "big corporation",
" numberOfEmployees": "1800",
"ceo": "Mike Madden",
"rating": 3.8
}
{"name" : "Voice",
"type": "small startup",
"numberaOfEmployeers" : 45,
"ceo": null
"rating" : 4.2
}

Inside HTML 
<script type="text/javasscript">
let companies= `[ copy the json objects codes from visual studio]
]`
console.log(Jason companies) 
</>script
```

#### Backticks`: Adding ' to the ` [square brackets ]` to make it a string.
#### Then display the string: 
#### console.log(Jason companies) 
// Inside HTML script 

#### Using console.log(json.parse (companies) to get It back to the json objects.

#### Backticks are an ES6 feature that allows you to create strings in JavaScript.

#### Although backticks are mostly used for HTML or code embedding purposes, they also act similar to single and double quotes. Besides, using backticks makes it easier for string operations.
### Template Literals
Template literals provide an easy and clean way create multi-line strings and perform string interpolation. Now we can embed variables or expressions into a string at any spot without any hassle.

Template literals are created using back-tick (` `) (grave accent) character instead of the usual double or single quotes. Variables or expressions can be placed inside the string using the ${...} syntax. Compare the following examples and see how much useful it is:
```
// Simple multi-line string
let str = `The quick brown fox
    jumps over the lazy dog.`;

// String with embedded variables and expression
let a = 10;
let b = 20;
let result = `The sum of ${a} and ${b} is ${a+b}.`;
console.log(result); // The sum of 10 and 20 is 30.
```
#### and without the ES6 features:
```
// Multi-line string
var str = 'The quick brown fox\n\t'
    + 'jumps over the lazy dog.';

// Creating string using variables and expression
var a = 10;
var b = 20;
var result = 'The sum of ' + a + ' and ' + b + ' is ' + (a+b) + '.';
console.log(result); // The sum of 10 and 20 is 30.
```


#### Then display the string: 
#### console.log(Jason companies) 
// Inside HTML script 

#### Using console.log(json.parse (companies) to get It back to the json objects.

References: 
(https://www.tutorialrepublic.com/javascript-tutorial/javascript-es6-features.php#:~:text=ES6%20brought%20significant%20changes%20to,programming%20easier%20and%20more%20fun. )
(https://youtu.be/iiADhChRriM)
***
## REST programing and REST API:

