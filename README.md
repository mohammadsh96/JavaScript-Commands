# JavaScript-Commands

LIST OF 50 JAVASCRIPT COMMANDS 
As the most common programming language, it is imperative that programmers and developers understand JavaScript code and JS commands. Developers with mastery over JavaScript code are the most valuable to employers. If you are new to web development and programming language, you will want to familiarize yourself with the JavaScript commands list.

In learning JavaScript, it is essential that you learn about the best JS commands because this will allow you to craft JavaScript code with more precision. Here, you will find a detailed JavaScript developer tutorial with everything you need to know about the top 20 in the JavaScript list of commands.

### The Three Data Types of JavaScript Code

There are only three data types in JS commands that are considered primitive. This means that more complex operations can be built using these three data types, but the data types are not derived from other procedures themselves. Additional properties cannot be added to the primitive data types. These data types are number, string, and boolean.

#### Number :

The Number() function returns the solution to an equation. The Number() function can also return a value of NaN, meaning not a number. This happens when a calculation is impossible to perform, as an attempt to divide 0 by 0. Any mathematical expression that is undefined will result in NaN. For example, a line of JS code that reads Number(“JS tutorials for developers”) will return NaN because this is not a numerical value. You would need to use the String() function for this object. The Number() function will return a value of 0 if there is no argument provided within the object’s parameters.

#### String:

The String() function of JavaScript code returns a value containing alphabetic characters. For example, a line of code that reads String a=new String(“There are three primitive data types”); will print the phrase There are only three primitive data types. The character, a, is a reference variable. The words in parentheses are known as the object. It is important to remember that you cannot make changes to a String() method after it is created.

#### Boolean:
The Boolean() function converts an object into one of two responses. A Boolean returns a value of either `true` or `false` . The instances in which a Boolean object has a value of `false` are…

when the value parameter is `null`
when the value parameter is `undefined`
when the value parameter is ` 0`
when the value parameter is `-0`
when the value parameter is ` not included`
when the string is `empty`

Importance of Semicolons

When working with JS code, it is important that you properly execute line termination. The best practice for terminating a line of code is to place a semicolon at the end, though if you forget, JavaScript software will insert one on your behalf. In the case of JavaScript malfunctions, you could end up with a line of code that has not been properly terminated. This is a rarity. However, it could happen and potentially cause an error in your JavaScript coding. Manually inserting semicolons should be a habit that you adopt, even with JavaScript’s automatic insertion of semicolons. Semicolons make JS code easily readable by everyone.

Just about every webpage, mobile app, and web application use some JavaScript. The open-source programming language allows for more dynamic and engaging applications. It is also very easy to learn because it only has a few rules, letting you achieve simple tasks with just a few lines of code. You do not need to import packages or declare namespaces. You just write some code, and it works. However, the lack of structure can lead many beginner developers to write unstructured, fragile code that can lead to unexpected, difficult-to-find bugs.

Because of this, it might be wise to develop a JavaScript cheat sheet for yourself. You would then have a list of useful commands you can reference when you need help completing a project. With the flexibility of the language, you will never find a definitive list of the best JavaScript keywords. Every programmer is different and your particular needs can vary wildly from everyone else.

Still, here’s a `list of the most popular commands` that are worth keeping up your sleeve:
  
:small_red_triangle_down: :small_red_triangle_down: :small_red_triangle_down: :small_red_triangle_down: :small_red_triangle_down: :small_red_triangle_down:
  
`1.document.getElementById()`
:small_red_triangle_down:
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>


JavaScript and its many frameworks such as JQuery let you process code based on a particular HTML name or class. While this works, it can slow your script as it must go through the entire script to find the right tag. You can speed up this search through your application’s document object model (DOM) by using element ID.

</div>
</details>


`2.Basic Input / Output :`  

<details>
<summary> <span style="color: red;">  see more  :small_red_triangle_down:   </span></summary>
<div>
Except for the most basic scripts, all applications require some user interaction. With JavaScript, this function comes in the form of the ```alert() and prompt()``` commands. Alert sends info to the user through a dialogue box, while the prompt asks for a response.

Syntax : 

```js
alert("message");

stringVar = prompt("message")
```
</div>
</details>


`3.SetTimeout()`
<details>
<summary> see more :small_red_triangle_down: </summary>
<div>

The setTimeout function is a native JavaScript function. SetTimeout lets you automatically run commands at a specific time without user input. This simple JS command just requires the command you want to run and when you want to run it. It sets a timer (a countdown set in milliseconds) for the execution of a callback function, calling the function upon completion of the timer.

Syntax
```js
setTimeout(command, time);
```
You must express the time in milliseconds, but you can use any JavaScript statement as the command. For example, the following code runs the myfunction command after 5 seconds.

Example
```js
setTimeout(myfunction, 5000);
```

</div>
</details>

`4.Setinterval()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>


You can also repeatedly run JavaScript commands using the setinterval command. The setInterval() method calls a function at specified intervals (in milliseconds). Setinterval is great when you need your application to refresh its data from the database at desired intervals of time.

</div>
</details>

`5.ClearTimeout`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
If you will use either settimeout or setinterval, you will want to use their associated clear command as well. ClearTimeout and ClearInterval take the variable name for a set command and then delete it from memory.

The number id value returned by the setTimeout() function is stored in a variable and it’s passed into the clearTimeout() function to clear the timer. Similarly, the same process is carried out for setInterval() and clearInterval().

Example
```js
$timer = setInterval(command, 5000);
clearInterval($timer);
```

</div>
</details>

`6.Var`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
It’s a simple command, but most JavaScript developers forget to use it. Var formally creates your variables. While you can create and use JavaScript variables without it, the language treats these variables as global variables. This is fine if that is your intention, but risks overriding something if you are not careful. It also uses more resources. You can improve the performance of your app just by formally declaring your variables.

Variables are declared in various data types which are the prefixes while writing the code. Accordingly, the size, as well as the function of the variable, is decided.

</div>
</details>

`7.Self-calling`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

A self-calling function is a JavaScript command that runs as soon as you create it. Function expressions will execute automatically if the expression is followed by (). However, you cannot self-invoke a function declaration. These commands are also called Self-Invoked Anonymous Functions or Immediately Invoked Function Expressions (IIFE).

Example
```js
(function(){    // some private code that will be executed automatically})
```

</div>
</details>

`8.Math`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The Math.random command generates random numbers. More precisely, it returns a floating-point, pseudo-random number in the range 0 to less than 1 (inclusive of 0, but not 1) with approximately uniform distribution over that range — which you can then scale to your desired range.

</div>
</details>

`9.Map`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>


The map() command lets you loop through an array or collection. In JavaScript, the map() method builds an array by running a given function on each member of the parent array. It’s an approach that doesn’t change anything. The map() method is often used to traverse over an array and run a function on each entry. This is perfect for running the same command over a large array.


</div>
</details>

`10.Debounce`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
Debounce limits how often a JS command will run. Functionally, it is the opposite of timeout. It is especially good if some repeated user interaction would slow down performance or cause other problems.

A debounce function makes sure that your code is only triggered once per user input. Search box suggestions, text-field auto-saves, and eliminating double-button clicks are all use cases for debounce.


</div>
</details>

`11.Poll`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
Many JavaScript commands do not warn the system when they finish running. Sometimes, you must manually poll to see if something stops or if there is an exception. It is a complex command to use though, but it is worth the effort.

</div>
</details>

`12.Once`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
Once lets you run a command once and only once during the execution of an application. Even though we execute or call this function multiple times then also it will have no effect. The original function’s values will only be returned each time it is called. You mostly find these commands in event listeners.
</div>
</details>


`13.GetAbsoluteUrl()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
This JavaScript command gets you the actual URL of a web address, especially if it is contained in a string. It just takes the URL string and it gives back the address with all the queries and other elements removed.

Example 
```js
var getAbsoluteUrl = (function() {var a;return function(url) {if(!a) a = document.createElement('a');a.href = url;return a.href;};})();// UsagegetAbsoluteUrl('/something'); //
```
</div>
</details>

`14.String.replace()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The replace command lets you change the text in a string. It searches the string for the text you want to be replaced and switches it out for what you want. The search pattern can be either a simple text string or a regular expression. The command then returns this new string, leaving the original string unmodified. This can be used to search and replace certain substrings from a long and iterative main string.

</div>
</details>

`15.Array.Push()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
Push adds items to arrays. The push() method changes the length of the array. The push() method produces a new length. It changes the array directly without returning anything.


</div>
</details>

`16.Array.filter()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The filter takes items out of an array based on some criteria and then creates a new array with just those items. The filter function iterates over the existing values in an array and returns the values that pass.


</div>
</details>

`17.Array.reduce()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

Reduce is an often-overlooked array command. It converts the items of an array into a single item. The reduce() method does not execute the function for empty array elements. The reduce() method does not change the original array. Perfect for calculations, it can return any type of variable.

</div>
</details>

`18.String.toLowerCase()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

ToLowerCase sounds like what it does. It converts a string to all lower-case letters. It does not change or tamper with the original string, its content, or its length. This popular command lets you convert data into standard URL formats that most web browsers will understand.

</div>
</details>

`19.IsNative()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
This function indicates if a given browser feature is native to a particular browser or if it comes from a third-party app.


</div>
</details>

`20.String.substr()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

Substr dives into a string and returns text based on the provided criteria. You must specify where you want it to start, and how many characters you want the command to retrieve.
Some of these twenty commands are built into the language. Others are useful snippets of code that the JavaScript developer community saw fit to create. Either way, all JavaScript commands will help you improve your knowledge and skills.

</div>
</details>

`21.debug(massage)`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

This is one of the most important Javascript commands. This command is used to send messages to the console window. The debugger statement invokes any available debugging functionality, such as setting a breakpoint. If no debugging functionality is available, this statement has no effect.

Example
console.debug("log message");

The above command is sending the log message to the console window. This command is equal to console.log command. Objects that are transferred by applying the command are transformed into a string value. This is mostly used in Microsoft Visual studio as a console log command.

</div>
</details>

`22.string.toLowerCase()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The toLowerCase() function does precisely what you believe it would. It just delivers a new string that has been transformed to all lower cases from the old string. The initial string is not modified. For example, if your text is in the capital and now if you want it in the lower case then this function helps you to get that output.

</div>
</details>

`23.Function Return`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
When JavaScript arrives at a return statement, the function will terminate performing. If the function was requested from a Javascript statement then JavaScript will “return” to perform the code after the beginning statement. Functions usually calculate a return value. You can always reuse this code. The return value is “reflected” back to the “visitor”.

Example
```js
var a = newFunction(6, 4);   // called Function, the return value will       be in a
function newFunction(x, y) {
  return x * y;             // Function returns the multiplication of x and y
}
```
The output of the above function is 24   

</div>
</details>

`24.floor()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

The floor is one of the most important javascript methods. The floor() method spins a number to the most next integer and delivers the result. If the given parameter is an integer, the argument will not be rounded. For example, the below command will round the entered argument to the nearest integer.

Example
```js
`Math.floor(1.6);`
```
</div>
</details>

`25.For loop`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

JavaScript contains loop commands like Java and C.If you want to execute some code repeatedly then the For loop command is crucial. It is an iterative loop to carry out a process which we require to carry out for a specific number of times. The syntax of this command is as follows.

Syntax
```js
for(initialize; condition; iteration)
{
    // Code
}
for (var a = 0; i < 10; a++) { console.log(a); }
```
The for the loop needs the three sections. The first one is Initializer which initializes a variable, to begin with. The second section is a condition where you define a situation that must decide to be true for the next repetition. The third segment is Iteration which is used to increase or decrease the counter.

</div>
</details>

`26.The If-Else`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The if/else command performs a section of code if a defined condition is valid. If the condition is invalid, another section of the code can be performed. The if/else command is a piece of JavaScript’s “Conditional” commands, which are utilized to execute various activities based on various circumstances. For example, the following command is displaying the use of the command.

Example
```js
var time = new Date().getHours();
if(hours<12)
document.write("Hello, We will meet tomorrow morning<br />"); else
 document.write("Hello, We will meet tomorrow afternoon<br />")
```
The above example shows that the conditional command is used to determine the course of the execution on various conditions. As mentioned earlier, if a condition is valid, you can complete one step and if the condition is invalid, you can complete a different step.

</div>
</details>

`27.constructor()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
These JavaScript Commands are useful for creating special methods. Now, if you want to make a special method for creating and initializing an object created within a class the constructor() can be used. Moreover, you can also carry out various different operations using constructors such as overloading and overriding of constructors. To create an object from a constructor function, we use the new keyword. You just have to mention it in the following format.

Example
```js
constructor([arguments]) { ... }
```
</div>
</details>

`28.Math Object`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
These best JS Commands are also known as objects which are essential for making a dynamic application. The Math object allows users to complete mathematical assignments. Math is not a constructor. All features/techniques of Math can be summoned by applying Math as an object, without building it. All the properties and methods of Math are static and can be called by using Math as an object without creating it.

Example
```js
Math.sqrt(25);
```
</div>
</details>

`29.JS Date`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The date is an important member of the JavaScript Command List. The Date object is applied to operate with dates and times. These objects are constructed with a new Date().

Example 
```js
var a = new Date();
```
</div>
</details>

`30.Error Object`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The Error object gives an error message when an error happens. Out of all the JavaScript List of Commands, the Error object is crucial for identifying and presenting error messages. They are produced when a runtime error occurs. The Error object can also be used as a base object for user-defined exceptions.

Example
```js
try {
myalert("Hello");
}
catch(err) {
  document.getElementById("task").innerHTML =
  err.name + "<br>" + err.message;
}
```
</div>
</details>

`31.toExponential()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
These JavaScript commands are part of the numerical methods and properties. This toExponential() method gives a string, with a number wheeled and formulated using exponential representation. For example, a parameter specifies the number of characters following the decimal point.

Example
```js
var y = 9.656;
y.toExponential(2);   will return 9.66e+0
```
</div>
</details>

`32.toFixed()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

with JavaScript, methods, and features are also possible to use for fundamental values. This is because JavaScript uses primitive values as objects when executing systems and characteristics. toFixed() passes a string, with the number addressed with a detailed number of decimals.

Example
```js
var y = 9.656;
y.toFixed(6); will return 9.656000
```
</div>
</details>

`33.toPrecision()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The toPrecision() gives a string. It returns a number addressed with a detailed length. In JavaScript, toPrecision() is applied to change a number to accuracy like spinning the result where required and deliver its content as a string. It must be called through a special case of the Number class.

Example
```js
var y = 9.656;
y.toPrecision(2) will return 9.7
```
</div>
</details>

`34.valueOf()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The valueOf method delivers the appropriate Number Object containing the value of the argument declared. The parameter can be a primitive data type. This is static. The method can accept two parameters.

Example
```js
var y = 125
;
y.valueOf(); will return 125 from variable 
y (123).valueOf(); will returns 125 from literal 125
```

</div>
</details>

`35.parseInt()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

The parseInt() parses a string parameter and gives an integer of the stipulated radix. You can also say that it returns the base in analytical number systems. In this, the spaces are allowed and only the first number is passed.

Example
```js
parseInt("20");  will return 20
```
</div>
</details>

`36.normalize()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

The normalize is a browser-based Javascript method. It merges neighboring text nodes into a separate text node and eliminates void text nodes. It has a return value and in Internet Explorer, this method does not remove empty text nodes.

This method is also used to obtain the Unicode Normalization Form also called a code point of the string. It creates unique numerical value and is one of the most important members of the String family.

Syntax
```js
string.normalize()

Example
var a = "Hello World";
b= a.normalize('NFC')
```
</div>
</details>

`37.slice(start,end)`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
arr.slice() is a javascript function that returns a new array holding a part of the array on which it is executed. For example, the primary array remains constant. This function accepts two parameters and it is an inbuilt function in Javascript. The parameters are the start index and the end index.

This function only copies the array and creates a new one. It does not change the original array. The following example is displaying the use of the slice function. It is only copying and creating a new array.

Example
```js
var myarr = [20,30,40,50,60,70];
var my_new_arr = arr.slice();
console.log(myarr);
console.log(my_new_arr);

Output
[20,30,40,50,60,70]
[20,30,40,50,60,70]
```
</div>
</details>

`38.Epsilon`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
EPSILON is one of the static properties of javascript that is applied to give the smallest positive number nearing zero (ie: a positive tiny number). EPSILON is a number object property and can be called through the Number object.

Syntax
```js
Number.EPSILON;

Example
console.log(Number.EPSILON);
Output: 2.220446049250313e-16
```
</div>
</details>

`39.toJSON()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The JSON is a JavaScript Object Notation. This function is a common setup to express conditions and objects. The JSON function can be used for data exchange when the client utilizes JavaScript and the server is based on Ruby/PHP. It gives two methods JSON.stringify and JSON.parse. The JSON.strigify is used to convert objects into JSON and the JSON.parse is used to convert JSON back into an object.

</div>
</details>


`40.toISOString()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

The toISOString() is a function of the date object in Javascript. This function gives the obvious extensive ISO format of the date. It is one of the most important functions of data objects. To use this function it is necessary to create a Date object. After creating the data object, there are a number of methods that allow users to work on the created object. Most methods only enable users to retrieve various elements of the calendar such as the year, month, day, hour, minute, second, and millisecond. These factors can be obtained by using local time, UTC, or GMT.

Syntax
```js
dateObj.toISOString();

Example
document.write("Current Date: "+dateObj.toISOString());
```

</div>
</details>

`41.Proxy()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
A Proxy object covers a single or many other objects and blocks methods, like writing properties. Proxies are utilized in many libraries and frameworks. A proxy is a unique object. It doesn’t hold its own properties. With a void handler, it just sends operations to the destination. Many proxy methods can be used as internal methods. For example, GET, SET, DELETE are some of the proxy’s internal methods that get triggers when respective events occur. The following is an example of a proxy to store user data.

Example
```js
const proxyUser = new Proxy(user, handler);
```
</div>
</details>

`42.Promise`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
A promise is a specific JavaScript object that combines the “building code” and the “utilizing code” collectively. In terms of the relationship: this is the “recommendation list”. The “building code” accepts whatever event it requires to deliver the promised outcome, and the “promise” makes that outcome accessible to all of the recommended code when it’s available. It is like fulfilling the promise. This is one of the most important javascript codes. It is used in many event-driven software applications. It is also used to handle asynchronous operations. Following is the example of Promise.

Example
```js
promise
then(function () {
console.log('Life is Beautiful');
})
```
</div>
</details>

`43.Mixins`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
Mixin is a style in which attributes are appended to objects without utilizing inheritance. It gives an alternative method of designing the application that isn’t explicitly included in chapters on design models. Mixins are a kind of object creation, where element characteristics get merged into a composite object so that attributes of each mixin display characteristics of the composite object. The Javascript does not support multiple inheritances this is the reason why Mixin is used to add various properties to objects without using inheritance. The following example is showing the use of Mixin.

Example
```js
let myMixin = {
sayHello() {
console.log(`Hi ${this.name}`);
```
</div>
</details>

`44.Autocorrection`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

The autocorrection is a really beneficial feature of Date objects. In this, users can configure a range of values, and it also auto-adjusts itself. For example, if you want to increase the date “28 August 2020” by 2 days. It is “30 August” then you just have to add 2 days. The Date object will execute it properly. This function is often applied to receive the date after the assigned period.

Example
```js
let date = new Date(2020, 8, 28);
date.setDate(date.getDate() + 2);
```

</div>
</details>

`45.unescape()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

The unescape() function calculates a new string in which hexadecimal escape strings are substituted with the number that it describes. The escape series might be presented by a function like escape. Normally, decodeURI or decodeURIComponent are used instead of unescape. This function was introduced in Javascript version 1.5 and it is mostly used to decode the encoded string. The escape function is used to create a string portable to send it using a network and in return, users can use unscape() function to decode the original string. These functions are useful in preventing the Cross-Site Scripting (XSS) attack. This feature has been removed from the web standards but some browsers still support these functions.

Example
```js
unescape('xyz123');
```
</div>
</details>

`46.Generate an array of numbers`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The following script can be used to create an array. An array is a group of objects collected at adjacent memory locations. The following script is used to generate the array with numbers from 0 to 500.

Example
```js
var numbersArray = [] , max = 500;
for( var a=1; numbersArray.push(i++) < max;); // numbers = [1,2,3 ... 500]
```
</div>
</details>

`47.Verify`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The verify is one of the most widely used JS commands. It is used to verify that a given or an inserted argument is a number or not. The following script is used to verify the given argument.

Example
```js
function isNum(a){
return !isNaN(parseFloat(a)) && isFinite(a);
}
```
</div>
</details>

`48.Create a Cookie`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

The most simplistic approach to design a cookie is to select a string value to the document.cookie object. The following script is displaying how to generate a cookie:

Example
```js
document.cookie = “key1 = value1; key2 = value2; expires = date”;
```
Here expires is an alternative. If users give this attribute with a confirmed date or time then the cookie will terminate at the given date or time and after that cookies’ content will not be available.

</div>
</details>

`49.Shift()`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>
The shift() method is related to the pop() method but the exception is that the Shift method operates at the commencement of the array. The shift() method accepts the first component off of the entered array and reverses it.

</div>
</details>

`50.Bonus query – NEGATIVE_INFINITY`
<details>
<summary style ="font-color : red ">  see more   :small_red_triangle_down:  </summary>
<div>

The negative infinity in JavaScript is a fixed value that is applied to describe a value that is the most moderate. This indicates that no other figure is more inferior to this number. It can be made by applying a self-made procedure or by an arithmetic progression.

Example
```js
var y = Number.NEGATIVE_INFINITY;
```

</div>
</details>

