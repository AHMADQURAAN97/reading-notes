## Links

Links are the defining feature of the web 
because they allow you to move from 
one web page to another and enabling the 
very idea of browsing or surfing.

**types of links**:
- Links from one website to another
- Links from one page to another on the same website
- Links from one part of a web page to another part of the 
same page
- Links that open in a new browser window
- Links that start up your email program and address a new 
email to someone.

*Links* in html are created using the <a> element. Users can click on anything 
between the opening <a> tag and the closing </a> tag. You specify 
which page you want to link to using the href attribute.

***Relative URLs*** can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

Also.You can **Email Links** such as in the image below and directly go to email.

![f](https://csharpcorner-mindcrackerinc.netdna-ssl.com/UploadFile/BlogImages/07302013064052AM/Image1.jpg)

**Linking to a Specific Part of the Same Page**
At the top of a long page 
you might want to add a list 
of contents that links to the 
corresponding sections lower 
down. Or you might want to add 
a link from part way down the 
page back to the top of it to save 
users from having to scroll back 
to the top.
Before you can link to a specific 
part of a page, you need to 
identify the points in the page 
that the link will go to. You do 
this using the id attribute (which 
can be used on every HTML 
element). You can see that the 
<h1> and <h2> elements in this 
example have been given id
attributes that identify those 
sections of the page.
The value of the id attribute 
should start with a letter or an 
underscore (not a number or 
any other character) and, on a 
single page, no two id attributes 
should have the same value.
To link to an element that uses 
an id attribute you use the <a>
element again, but the value of 
the href attribute starts with 
the # symbol, followed by the 
value of the id attribute of the 
element you want to link to. In 
this example, <a href="#top">
links to the <h1> element at 
the top of the page whose id
attribute has a value of top.


## Layout
 it is for Controlling the position of elements, Creating site layouts and Designing for different sized screen.

 ***Building Blocks*** : either be a block-level
box or an inline box . Block-level boxes start on a new line and act as the main building blocks 
of any layout Examples include:
<h1> <p> <ul> <li>, while inline boxes flow between surrounding text Examples include:
<img> <b> <i>. You can 
control how much space each box takes up by setting the width of the 
boxes (and sometimes the height, too). To separate boxes, you can use 
borders, margins, padding, and background colors. 


## Functions, Methods, and Objects in JS

*Functions* : consist of aseries of statements that have been grouped together because they perform a specific task. 

*A method* : is the same as a function, except methods are created inside (and are part of) an object. 

![c](https://a.ilovecoding.org/img/self-invokingsc1.png)

**GETTING MULTIPLE VALUES OUT OF A FUNCTION **

Functions can return more than one value using an array. 
For example, this function calculates the area and volume of a box.

function getSize (width, height, depth) { 

var area = width * height; 
} 

var volume = width * height * depth; 
var sizes= [area , volume]; 
return sizes; 

var areaOne = getSize (3, 2, 3)[0]; 
var volumeOne = getSize (3, 2, 3)[1];

***FUNCTION DECLARATION*** 
A function declaration creates a function that you 
can call later in your code. It is the type of function 
you have seen so far in this book. 
In order to call the function later in your code, you 
must give it a name, so these are known as named 
functions. Below, a function called area() is 
declared, which can then be called using its name. 

***FUNCTION EXPRESSION ***
If you put a function where the interpreter would 
expect to see an expression, then it is treated as an 
expression, and it is known as a function expression. 
In function expressions, the name is usually omitted. 
A function with no name is called an anonymous 
function. Below, the function is stored in a variable 
called area. It can be called like any function created 
with a function declaration.

VARIABLE SCOPE :

The location where you declare a variable will affect where it can be used 
within your code. If you declare it within a function, it can only be used 
within that function. This is known as the variable's scope.

To types of variables :

1.LOCAL VARIABLES 
2.GLOBAL VARIABLES 

 # Pair Programming

 ### How does pair programming work?

 While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

 ### For what pair programming ?

 Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

During a five-hour paired lab session, Code Fellows students work on all four of these language-specific skills. The abilities they foster will serve them well in completing assignments, in their own communication and learning, in interviews, and in readiness for a job at a company that utilizes this agile practice.

***it's back benefits to programmer for :***
- Greater efficiency
- Engaged collaboration
-  Learning from fellow students
- Social skills
- Job interview readiness
- Work environment readiness

to read more about it click [Here!](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)