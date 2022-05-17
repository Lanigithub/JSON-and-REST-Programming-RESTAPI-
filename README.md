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

Template literals are created using back-tick (` `) (grave accent) character instead of the usual double or single quotes. Variables or expressions can be placed inside the string using the ${...} syntax--similar to the f-String in Python for shorthand formating. Compare the following examples and see how much useful it is:
```
// Simple multi-line string
let str = `Good morning my friend!
           Have a great week.`;

// String with embedded variables and expression
let n1= 15;
let n2 = 80;
let result = `The sum of ${n1} and ${n2} is ${n1+n2}.`;
console.log(result); // The sum of 15 and 80 is 95.
```
#### and without the ES6 features:
```
// Multi-line string with single quotation:
var str = 'Good morning my friend!\n\t'
    + 'Have a great week.';

// Creating string using variables and expression
var n1 = 15;
var n2 = 80;
var result = 'The sum of ' + n1 + ' and ' + n2 + ' is ' + (n1+n2) + '.';
console.log(result); // The sum of 15 and 80 is 95.
```



References: 
(https://www.tutorialrepublic.com/javascript-tutorial/javascript-es6-features.php#:~:text=ES6%20brought%20significant%20changes%20to,programming%20easier%20and%20more%20fun. )
(https://youtu.be/iiADhChRriM)

***
## REST programing and REST API:

### What is REST and REST APT?
* #### **_Representational state transfer (REST)_**  is a software architectural style that was created to guide the design and development of the architecture for the World Wide Web. REST defines guiding principles for creating  lightweighted(simple and straightforward),  stateless, reliable web APIs.
* #### REST API( Application programming interface: a connection between computers or between computer programs. It is a type of software interface, offering a service to other pieces of software) : an API implemented with the REST guidelines is called RESTFUL ( REST) API. 
* #### A REST API is a medium for two computers to communicate over HTTP (Hypertext Transfer Protocol), in the same way clients and servers communicate.
( RESTis an architectural style created by Roy Fielding in 2000 )

### Advantages of using REST API:
* #### In Web Development, REST APIs play an important role in ensuring smooth communication between the client(frontend) and the server (backend)
* #### REST API is lighter and faster( mostly use Json style payload), flexible ( access a list of itmes using URI/item,  and can be integrated to different security methods), cashable ( mark data as cashable and support for cashing). On the other hand, SOAP ( SIMPLE OBJECT ACCESS PROTOCOL) is a protocol that has more security than REST but less flexibility. 
* #### For security: REST API uses HTTPS(Hypertext Transfer Protocol Secure ) and SSL ( Secure Socket Layer)/ TLS ( Transport layer security for encryption and data strems. Using hashed(scrambled representaion) and salted(unique strings) password to shield RESTFUL services.    Also we could integrate different security methods to REST APIs like tokens, authentication and API gateways. 

### REST API methods: (VERBS from HTTP):
* #### GET: offering read-only access for the resources;
* #### POST: implemeted for creating a new resource;
* #### DELETE: implemented for removing a resource;
* #### PUT: Implemeted for updating an existing resource and creating a new resource. ( similar to upsert in DML)

### Richardson Maturity Model:
#### It is used to ranck API based on the checks corrlated to REST. The more restful your API isis for development and deployment  the more your API  fullfills the chechks and constraints; 
There are 4 levels or 4 stages in this Model:
Level 0:
Level 1:
Level 2:
Level 3: 

### Examples of SOAP vs REST APIs:




*** 





