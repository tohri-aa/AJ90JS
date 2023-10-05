#### _Day 01_
___

##### **About JS**
---

- JS is a programming language designed to interact withh elements of webb pagges. It allows you add interactivity to a web page. 
- JS is used with HTML & CSS to enhance a web page's functionality.
- It is also known as the scripting language for web pages.
- It can run on both web browsers andd servers.
- It supports several data types including strings, numbers, booleans, arrays etc.
- It is object-oriented and is supported by major web browsers.
- It has an ecosystem of libraries and frameworks including React.js, Angular.js, Vue.js on the front-end and Node.js on the back-end.




#### _Day 02_
---

##### **Uses and Roles of JS in Web Development**
---
1. JS allows devs to add dynamic and interactive effect to a web page.
2. It is also usedd to manipulate content of CSS, load data from remote servers and build entire apps in the browser that are called web apps.
3. It can run outside browsers using Node.js whichh allows it to create back-end apps. JS used on the browser is used to create front-end apps.
4. It is used to build native apps and desktop apps using tools like react native, the iconic framework and electron. There's really nothhing one can't do when super good in writing JS.


#### _Day 03_
___

##### **Setting up the Developer Environment withh a Code Editor**

I caught up with Ajay's video on "Everything about Github Markdown, README file, Git and GitHub". I learnt about how to properly document on Github using markdown language. Documenting would bbe so muchh easier, all thanks to Ajay!


#### _Day 04_
___
I already have my development environment set up. I'd be using VSCode as my preferred IDE of choice.

**Development Environment**
___

A development environment (DE) is a setup used by software developers to create and test software. It includes a text editor, compiler or interpreter, and other tools.

A DE can be as simple as a text editor and a compiler, or it can be a complex integrated development environment (IDE) that provides a wide range of features to help developers write, compile, debug, and test their code.

**Web Development Tools**
___
- Web dev tools allow you to test and debug the JS code.
- They are often called devtools.

- Modern web browsers such as Google Chrome, Firefox, Edge, Safari, and Opera provide the devtools as built-in features.

- Devtools allow you to work with a variety of web technologies such as HTML, CSS, DOM, and JavaScript.


**The 'script' tag**
___

To insert JavaScript into an HTML page, you use the `script` element. There are two ways to use the `script` element in an HTML page:

>Embed JS code directly into the HTML page.

>Reference an external JS code file.

>Only the simplest scripts are put into HTML, more complex ones reside in separate files.

>A single `script` tag can't have both the src attribute and code inside. You either choose an external `<script src='...>'` or a regular `<script>` with code.



#### Day 5
___

Write your first "hello world" code
___

``` js
alert('Hello World!')
```

``` js
let js = "fantastic";

if (js === "fantastic"){
    console.log("JS is fun!")
} else {
    console.log("I don't have a choice but to learn!");
```

**Code structure**
___
- Statements: are regular syntax constructs and commands that perform actions. We can have as many statement as we want and they're separated a semi-colon.

- Semi-colon: it is recommended to put semi-colon after each statement even if they're separated by new lines.

- Comments: as code becomes complex, it is necessary to add comments which describes what the code and why. It can be added anywhere in the script and does not affec its execution as the engine ignores them. For one-line comment, use **//** and for multi-line comments, start with **/*** and end with ***/**.


'use script'
___

- This looks like a string. When used at the top of a script, the whole script works the modern way. Once we enter strict mode, no going back.

- Should we use 'use strict'?
Modern JS supports classes and modules, advanced language structures, that enable 'use strict' automatically. So when your code is all in classes and modules, you may omit 'use strict'.




