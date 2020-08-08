# Programming With JavaScript

When it comes to programming JavaScript into webpage, The goal it should acheive is creating an interchanging and dynamic site that the user can come back to and access different sets of information and stimuli, all while the site uses the same groups of functions to process and execute. In *Jon Duckett's* ***JavaScript & jQuery: Interactive Front-End Web Development***, This is the new information I learned.

## Pages 1-24
+ JS makes websites more interactive
+ JS allows you to access & modify the content and markup used in webpages while being viewed in the browser
+ follows the traditional rules of coding with its vocabulary and syntax 
+ Specfify rule sets for code to follow, react to events and actions, add and remove elements,tags and text in a page, select elements
+ Perfoms error reports and calculations, update parts of pages, filter webpage data
+ **jQuery** helps solve problems with cross-browser inconsistecies
+ Scripts are set of instructions a computer perfoms to acheive desired goals
+ Scripts are required to be precise, to flow, and possibly execute repeatedly to work in a website
+ Flow charts are helpful diagrams that help visualize how we want script to perfom and appear

## Pages 74-79
+ *Expressions* - evaluates into a single value
   + Assign value to a variable `var color = beige;`
   + 2 or more values that reult into 1 value `var area = 3 * 4;`

+ *Operators* - allow programmers to create a single value from 1 to multiple other values. Expressions rely on opertors to be called
   + Assignment - Assign value to a variable
   + Arithmatic - Perfom basic math expressions
   + String - combine 2 strings
   + Comparison - The true or false result of comparing 2 Boolean expressions
   + Logical - The true or false result of combining 2 Boolean expressions

***Arithmatic Operators:***
+ '+' addition `1 + 1   // Results 2`
+ '-' subtraction `2 - 1    // Results 1`
+ '*' multiplication `2 * 4    // Results 8`
+ '/' division `4 / 2    // Results 2`
+ '++' *Increment*: adds 1 to current value `i = 10; i++;    // Results  11`
+ '--' *Decrement*: subtracts 1 from current value `i = 11; i--;   // Results 10`
+ '%' *Modulus*: sign divides 2 numbers and feeds back the remainder of the values `10 % 3   // Results 1`
  + Arithmatic is read from left to right in proper order of operation

***String operators only use '+'***
+ Number values can be added in string values as well. When reside in single quotes '_', numbers can be strung together instead of computed.
+ *Concentration*: joining 2 or more strings to form 1 new string
    + String values can not be computed like Arithmatic, they result in **NaN**: Not a Number     

## Pages 88-94
` function sayHello(greeting){
    document.write('Bonjour !');
}`


Written in a JavaScript file (file.js), functions and JS methods are stored
+  *Function*: groups a series of statements together to perform a task
+  *Calling*: on the last line of code, the interpreteur asks a function to perform a task
+  *Parameters*: pieces of information given to a function
+  *Return Value*: the solution of a called function
    + Program languages rely on name & value pairs in JS to process the information 
+  *Anonymous Function*: functions without names that cannot be called unless an interpreteur locates them and manually calls them


+ Functions need to perfom a specific task when called upon in the script 
+ Though it is more reliable to have the declaration before the function calling, sometimes functions can be called before they declared in the code
+ Parameters act like functions: They are placed in parentheses () to provide information. This lets functions perform without knowing exact details

+ *Arguements*: When you call a function with parameters, specify the values it should use in () that follow its name. These can be values or variables
  + Parameters are found in the **Declaration**
  + Arguements are found in the **Calling**
+ *Return*: returns a value to the code that called the function




### Table of Contents
- [About Me/Home](README.md)
- [Growth Mindset](/GROWTH_MINDSET.md)
- [Section One Summary](/SectionOne.md)
- [What is Markdown?](/LEARNING_MARKDOWN.md)
- [Coder's Computer](CODERS_COMPUTER.md)
- [Git Clone Exercise](GIT_CLONE.md)
- [Revisions and the Cloud](REVISIONS_AND_THE_CLOUD.md)
- [Structure Pages With HTML](STRUCTURE_PAGES_WITH_HTML.md)
- [Design Webpages With CSS](DESIGN_WEBPAGES_WITH_CSS.md)
- [Dynamic Webpages With JavaScript](DYNAMIC_WEBPAGES_WITH_JAVASCRIPT.md)
- [Computer Architecture and Logic](COMPUTER_ARCHITECTURE_AND_LOGIC.md)
- [Programming With JavaScript](PROGRAMMING_WITH_JAVASCRIPT.md)
- [Operators and Loops](OPERATORS_AND_LOOPS.md)