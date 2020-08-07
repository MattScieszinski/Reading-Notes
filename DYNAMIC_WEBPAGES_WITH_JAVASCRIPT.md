#  Dynamic Webpages with JavaScript

JavaScript is the interactive layer of webpages; it allows me to program the behaviors of elements in my site. Using the `<script>` element within my HTML coding, I allow access for JavaScript to manipulate the infomation and data I want visible on my site. In *Jon Duckett's* ***JavaScript & jQuery: Interactive Front-End Web Development***, This is the new information I learned.

## Pages 44-69
+ JavaScript works by linking a .js file into the line of HTML code where it needs to appears. This way all code blocks, formulas, variables & instructions are group into one file for optimal finding and orderliness.
+ For JS to appear in the page, I would write a line of script with an object and method like so:
`document.write('Bonne Soir !');`. 

Here's how the code breaks down.
  + Object: `document` -- This calls to subject of the JS script in question
  + Member Operator: `.` -- Allows access to the method and which line of script to call
  + Method: `write('Bonne Soir !')` -- The method will be what is perfomed in the webpage
  + Parameters: `('Bonne Soir !')` -- Details the execution of the method

When it comes to writing the script in the .js file, it is written out in *code blocks*. In each code block will be a set of *statements* or the step by step instuctions that will be called in the HTML code. When **calling** a method of an object, it refers to executing the statements in order inside a code's code block `{}`. For all the terms layed out, refer to the next line of code:

`if(hourNow > 18) {
  greeting = 'Bonne Soir !';
}`

+ Especially when working with clients and team members, it is important to write comments next to your code to explain what your code is and how it pertains to its execution.
  + `// short lines of code use these double slash tags`
  + `/* If you happen to need a longer explanation of your code, whether it be for general statements and very specific rules, use these tags for comments longer than one line*/`

JavaScript implements the use of *variables* to represent bits of data to store so it can be called and computed. with enought defined variables, JS can compute multiple different outputs with the variables interchanged, however I see fit and need to create my desired outlook for my webpage.

`var greeting;

greeting = Bonne Soir !`

+ If I want my code to compute with variables, I need them to be named with a key identifier, or else the variable's value will be left undefined. With `greeting = Bonne Soir !` the " = " assigns the value of my variable's name & will now execute the message "Bonne Soir !" into my webpage.

JS determines values as either **Numbers**, **Strings (phrases and letters)**, and **Boolean (true or false / absolutes)**
+ Number values allow for JS to perform arithmatic and mathematics in our code.
+ String values allow phrases and messages to appear in execution
+ Boolean values are absolute values like "On or Off" "This of That" etc. and they are displayed as either True or False 

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