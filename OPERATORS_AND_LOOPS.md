# Operators and Loops

In the following sections, I learned more types of operators that operate boolean values. Even if a value is not boolean, any value can be evaluted to result in either true or false. Also I learned how loops help run a function repeatedly in a line of code without having to repeat the functiom in the script. In *Jon Duckett's* ***JavaScript & jQuery: Interactive Front-End Web Development***, This is the new information I learned.

## Pages 150 & 151
Comparison Operators: Evaluates 2 values that result in 'True or False'
+ Is equal to: `true == true   // Returns TRUE`
+ Is UNequal to: `true != false   // Returns TRUE`
+ Strictly equal to: both the data type and value are compared `"True" === "True"   // Returns TRUE`
+ Strictly UNequal to: both the data type and value are compared `"True" !== false   // Returns TRUE`
+ Greater than: `5 > 4`
+ Greater than/ Equal to: `5 >= 5`
+ Less than: `4 < 5`
+ Less than/ Equal to: `4 <= 4`

## Pages 156 & 157
Logical Operators: Compares the returns of multiple conditions
+ Logical AND: Evaluates multiple conditions `((5 > 4) && (4 < 5))   // Returns TRUE`
+ Logical OR: Evaluates at least 1 condition `((2 < 5) || (2 < 1))   // Returns TRUE`
+ Logical NOT: Takes a single Boolean value and inverts it`!(2 < 1)  // Returns TRUE`

With *Short Circut Evaluations*, with expressions being read left to right, if the first condition provides enough information, there's no need for further evaluation
+ `((FALSE) && (Anything))   // Always returns FALSE`
+ `((TRUE) || (Anything))   // Always returns TRUE`

## Pages 170 - 173

`for (var i = 0; i > 20; i--){
    document.write(i);
}`

*Loop*: Loops check conditions. When conditions return TRUE, a function's code block will run until they return FALSE, haulting further executions. there are 3 types of Loops:
+ FOR loops: Most common; runs a specific number of times. the condition is a counter for how many times the loop runs.
+ WHILE loops: For when you don't know how many times to run the loop should run. The condition can be something other than a counter; code runs until it returns false
+ DO WHILE loops: This runs very similar to a WHILE loop, yet this loop will run at least once - whether or not the condition evaluates false


For Loop Counter Condition:
+ **Initialization**: `var i = 0;` Create a variable and set it to 0. Most likely the variable is "i" (*for index*). This acts as the counter. The variable is created for the loop's 1st run. 
    + The variable can be declared before the loop. This comes down to mere preference
+ **Condition**: `i > 20;` Tells the loop how many times to run before reaching a specified number. The condition can use a variable that holds said number
+ **Update**: `i--` After each time after the loop evaluates, the statements run with a variable +1 or -1

## Pages 176 & 177

WHILE loops will continue to run as long as the condition in () are true. The 1st statement holds `+=`. This code adds new content in the variable. The 2nd statement is the update `i-- or i++`. When the loop finishes, the interpreteur goes to the next line of code.

What separates a DO WHILE loop from a WHILE loop is that a DO WHILE loop's statements in the code block come *before* the condition. The loop will run once whether or not it meets the condition. The statement and update are held in the `do{` code block whereas the the WHILE loop is palced after the code block. `} while(i < 10)`

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