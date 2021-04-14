## Read: 04a - Dynamic web pages with JavaScript

**dynamic web page and how we can change in the web page that we can make this change by useing JavaScript in html [main atructur of the page ]**

- PROPERTIES
Properties describe characteristics of the current
web page (such as the title of the page).
- METHODS
Methods perform tasks associated with the
document currently loaded in the browser (such
as getting information from a specified element or
adding new content).
- EVENTS
You can respond to events, such as a user clicking or
tapping on an element.


### the stuctur of the page 
- CREATE A MODEL how the page should look 
- HTML which the beging of the page with the main stuctur.
- USE A RENDERINGENGINE TO SHOW THE PAGE ON SCREEN by useing css .
![page stuctur](https://www.researchgate.net/profile/Muhammad-Pasha-6/publication/323869270/figure/fig3/AS:606182121164801@1521536488788/Structure-of-an-HTML5-Web-Page.png)


***All major browsers use a JavaScript interpreter to translate your
instructions (in JavaScript) into instructions the computer can follow. ***


## HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER 
> in any page we start with the structur in our case html 
and we do css to make it live and make change by JavaScript
![structur page](https://slideplayer.com/slide/16324903/95/images/2/How+HTML%2C+CSS%2C+and+JS+Fit+Together.jpg) 

  
 
 **JavaScript**

 > JavaScript are more inter active language that we use to make our web page more life and to inter act with the user it self .


 #### JavaScript are best practics in the end of the body and it can be external SRC or internal SRC .

 - internal source 
![internal](https://user-images.githubusercontent.com/8504000/40852780-4a8f9cf8-6591-11e8-8204-4d3642cf905e.png)


- extrnal SRC
![external](https://www.homeandlearn.co.uk/javascript/images/chapter_1/first_script_alert.gif)


***javascript have easy way to writ and to understand  ***
> its logic language to use and the this example 
![javascript](https://i.stack.imgur.com/ANAYh.png)


**how its work**
***How it Works?
Line 8 declares a variable called username, via the keyword var. A variable is a named storage location that holds a value. Once the variable is declared, you can assign (and re-assign) a value to that variable, via the assignment operator '=' (Line 9).
Line 9 invokes the prompt(promptingString, defaultString?) function to pop out a dialog box, and reads in the string entered by the user. The string read is assigned to the variable username. The function prompt() is similar to the alert(), but it accepts a user's input.
In Line 10, the confirm(aString) function puts up the message and returns either true or false, depending on whether the user hits the OK or Cancel button.
If the result is true, Line 11 prints "Hello, username!". Otherwise, Line 13 prints "Hello, world!".***

for example:


<!DOCTYPE html>
<!-- JSExVar.html -->
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>JavaScript Example: Variables and functions prompt() and confirm()</title>
  <script>
    var username = prompt("Enter your name: ", "");
    if (confirm("Your name is " + username)) {
       document.write("<h1>Hello, " + username + "!</h1>");
    } else {
       document.write("<h1>Hello, world!</h1>");
    }
  </script>
</head>
<body>
  <p>Welcome to JavaScript!</p>
</body>
</html>






### Fill-in-the-blank
<!DOCTYPE html>
<!-- JSExVar.html -->
<html lang="en">
<head>
  <meta.........="utf-8">
  <title>JavaScript Example: Variables and functions prompt() and confirm()</title>
  <script>
    var username = prompt("Enter your name: ", "");
    if (confirm("Your name is " + username)) {
       document.write("<h1>......, " + username + "!</h1>");
    } else {
       document.write("<h1>Hello, world!</h1>");
    }
  </.........>
</head>
<body>
  <p>Welcome to JavaScript!</p>
</body>
</html>



**thank you**