# React and Forms

## Forms
> HTML Form is a document which stores information of a user on a web server using interactive controls. An HTML form contains different kind of information such as username, password, contact number, email id etc. The elements used in an HTML form are check box, input box, radio buttons, submit buttons .

>HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state. For example, this form in plain HTML accepts a single name

![](https://miro.medium.com/max/2178/1*lPa4yO4rACiK244hdyRYXw.png)

## Controlled Components
> In HTML, form elements such as <input, <textarea, and <select typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState(.if we want to make the previous example log the name when it is submitted, we can write the form as a controlled component

![](https://www.htmlgoodies.com/wp-content/uploads/2021/04/HTML-Form.png)




> class NameForm extends React. Component {
constructor(props) {
super(props);
this. state = {value: ''};
this. handleChange = this. handleChange. bind(this);
this. handleSubmit = this. handleSubmit. bind(this);
}
​


### user intreance 
>Get the value of input type checkbox
function getChecked() {
const checkBox = document. getElementById('check1'). checked;
if (checkBox === true) {
console. log(true);
} else {
console. log(false);

First, select the <input> element with the id message and the <p> element with the id result .
Then, attach an event handler to the input event of the <input> element. Inside the input event handler, update the textContent property of the <p> element.
![](https://dcv19h61vib2d.cloudfront.net/thumbs/egghead-make-controlled-react-components-with-control-props/egghead-make-controlled-react-components-with-control-props.jpg)


##  ternary operator
> Use the ternary operator to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms

* What is the use of ternary operator in C?
>The conditional (ternary) operator is the only JavaScript operator that takes three operands: a condition followed by a question mark ( ? ), then an expression to execute if the condition is truthy followed by a colon ( : ), and finally the expression to execute if the condition is falsy.

![](https://bennadel-cdn.com/resources/uploads/2016/conditional-ternary-operator-format-coldfusion-javascript.png)

## Things I want to know more about
> know more about how to creat a form in parctic 


for more info please visit my github
[qusaiqeisi](https://github.com/qusaiqeisi)


***best regard***