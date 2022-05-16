## JSON and REST Programming (REST API)

JSON(JavaScript Object Notation):
​* Data representation format
​* Commonly used for APIs and configs
​*Light weight and easy to read/write
​* Integrates easily with most languages 

​JSON Types:
​* Numbers: 8, 2.5, -3, 1.5e18
​*Strings: " Hello World", "Name", "ID", "123"
​*Booleans: true false
​* Array: [ " Hello", "World", "123"], [-8,3,10]
​Objects: {"key": "value"}{"Name": "Larry"}{"ID": 12345}
​
​Writing JSON( file.json)---objects in the key: value pairs (inside the curry brackets:
Example 1: user.json
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
}

Write JSON on visual studio---write objects inside the square brackets that's easy to copy and paste to the html scripts
Remember JSON is the JavaScript Object Notation.
Example: companies.json: with tow objects
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
}
Inside HTML <script type="text/javasscript">
let companies= [ copy the json objects codes from visual studio]
]
</>script

Backtocks`: Adding ' to the ` [square brackets ]` to make it a string.
Backticks are an ES6 feature that allows you to create strings in JavaScript.

Although backticks are mostly used for HTML or code embedding purposes, they also act similar to single and double quotes. Besides, using backticks makes it easier for string operations.

​
then display the objects: 
console.log(Jason companies) 
// Inside HTML script 

Using console.log(json.parse (companies) to get It back to the json objects.

(https://youtu.be/iiADhChRriM)
