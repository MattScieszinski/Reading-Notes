# Design Webpages With CSS
After having the structure of a webpage set and ready, *Cascading Style Sheets* (***CSS***) are the next step to creating a more vibrant, stylized site inviting all potential visitors to interact with. CSS allows you to change the apperance of the elements' contents on a webpage. Since line of code *cascades*, The interpretor will execute code when lines of code are ordered from top to bottom, in order of the HTML code written. Choosing the right colors and how they interact snd contrast with each other is key to a dynamic, efficient, and professinal looking website. Through *Jon Duckett's* ***HTML & CSS: Design and Build Websites***, These are some of the things I've learned.

## Ch. 10: Introducing CSS
`body{ 

       font-family: Times New Roman, serif; 

       color: maroon; 

       border: 25px solid black;
       
    }`

+  This is what the basic CSS code block will look like. CSS can be written and applied **externally** in a seperate file linked in the `<head>` element written in the `<style>` element. (recommended, especially for different pages and multiple elements), or it can be inserted **internally** by writing code in the same place. (not recommended, but useful for simple and short web pages)
#### **Key Components**
In the CSS code above, here are each label in the element 
+ Selector: This is the element being changed. EX: `body{`
+ Declaration: How the element is being changed. This sits inside the {} code block. EX: `color: maroon;`

In the declaration we have:
+ Property: Part of the element is being changed. EX: `color:`
+ Value: This specifies the change's setting. EX: `maroon;`
    
 *Id vs. Class*: When deciding how to explain & label HTML code, a `<div id=>` will label a unique line of code, a 
 `<div class=>` will group multiple lines of code under one label. Both are written and executed in the same way when written in CSS

## Ch. 11: Color
There are 4 types of color codes you can add in `color: ____;` 
+ Color Names: From 147 different names, type in the color name - e.g. `color: maroon;` - and it will show in you webpage
+ RGB: Values for red, green, and blue (like a television) a represented by a number between 0-255  `color: rgb(102,205,170)`
+ Hex: In hexadecimal code (6 characters), 2 red, 2 blue, and 2 green values are represented and executed `color: #ee3e80`

These codes let us change:
+ Hue: Refers to what is usually thought of when you here 'color'. 
+ Saturation: Refers to the amount of grey in a color
+ Brightness: Refers to the amount of black in a color
  + In CSS3, Using `opacity:` or `rgba()` (RGB value specific), these allow a color's opacity/translucency to be changed between 0.0-1 (00% to  100%) the 'a' in rgba is known as the *alpha* value, the value that changes a colors opacity.

Unique to CSS3, HSL is the fourth color code available. HSL allows us to change:
+ Hue: Between 0-360, a color represents an angle on the color wheel
+ Saturation: Refers to the amount of grey in a color; written in percentage (%), 
+ Lightness: Refers to both the amount of white (0%) to black (100%) in a color value; written in percentage (%)
  + Like `rgba()`, `hsla()` also uses the alpha value to change a color's opacity


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